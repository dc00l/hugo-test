---
title: "Vm"
date: 2022-07-03T19:19:00Z
draft: true
---
# Listing VMs
{{ range $.Site.Data.resources.all }}{{ $tpl := print .assetType ".html" }}{{ partial $tpl . }}{{ end }}
