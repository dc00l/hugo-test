---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
---
{{ $vms := $.Site.Data.vm.test }}
{{ range $i, $vm := $vms }}
#{{ .name }}

  <h4>Labels</h4>
  <ul>
    {{ range $j, $label := $vm.metadata.items }}
      <li>{{ $label.key }}:{{ $label.value }}</li>
    {{ end  }}
  </ul>

  <h4>Disks</h4>
  <ul>
    {{ range $k, $disk := $vm.disks }}
      <li>Name:{{ $disk.deviceName }}</li>
      <li>Size:{{ $disk.diskSizeGb }} GB</li>
{{ . }}
    {{ end  }}
  </ul>

  <h4>Network</h4>
  <ul>
    {{ range $k, $network := $vm.networkInterfaces }}
      <li>Network: {{ $network.network }}
      <li>Sub-Network: {{ $network.subnetwork }}
      <li>NetworkIp: {{ $network.networkIP }}
    {{ end }}
  </ul>
{{ end }}

{{ range $.Site.Data.resources.all }}{{ $tpl := print .assetType ".html" }}{{ partial $tpl . }}{{ end }}
