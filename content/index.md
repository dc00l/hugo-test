---
title: ""
date: 2022-07-04T10:06:38Z
draft: true
---


#instance-1

  <h4>Labels</h4>
  <ul>
    
      <li>test123:456</li>
    
  </ul>

  <h4>Disks</h4>
  <ul>
    
      <li>Name:instance-1</li>
      <li>Size:10 GB</li>
map[autoDelete:true boot:true deviceName:instance-1 diskSizeGb:10 guestOsFeatures:[map[type:UEFI_COMPATIBLE] map[type:VIRTIO_SCSI_MULTIQUEUE] map[type:GVNIC]] index:0 interface:SCSI kind:compute#attachedDisk licenses:[https://www.googleapis.com/compute/v1/projects/debian-cloud/global/licenses/debian-11-bullseye] mode:READ_WRITE source:https://www.googleapis.com/compute/v1/projects/serene-courier-331011/zones/us-central1-a/disks/instance-1 type:PERSISTENT]
    
  </ul>

  <h4>Network</h4>
  <ul>
    
      <li>Network: https://www.googleapis.com/compute/v1/projects/serene-courier-331011/global/networks/default
      <li>Sub-Network: https://www.googleapis.com/compute/v1/projects/serene-courier-331011/regions/us-central1/subnetworks/default
      <li>NetworkIp: 10.128.0.3
    
  </ul>

#instance-2

  <h4>Labels</h4>
  <ul>
    
  </ul>

  <h4>Disks</h4>
  <ul>
    
      <li>Name:instance-2</li>
      <li>Size:10 GB</li>
map[autoDelete:true boot:true deviceName:instance-2 diskSizeGb:10 guestOsFeatures:[map[type:UEFI_COMPATIBLE] map[type:VIRTIO_SCSI_MULTIQUEUE] map[type:GVNIC]] index:0 interface:SCSI kind:compute#attachedDisk licenses:[https://www.googleapis.com/compute/v1/projects/debian-cloud/global/licenses/debian-11-bullseye] mode:READ_WRITE source:https://www.googleapis.com/compute/v1/projects/serene-courier-331011/zones/us-central1-a/disks/instance-2 type:PERSISTENT]
    
  </ul>

  <h4>Network</h4>
  <ul>
    
      <li>Network: https://www.googleapis.com/compute/v1/projects/serene-courier-331011/global/networks/default
      <li>Sub-Network: https://www.googleapis.com/compute/v1/projects/serene-courier-331011/regions/us-central1/subnetworks/default
      <li>NetworkIp: 10.128.0.4
    
  </ul>


<h4>Appengine - Application</h4>
map[string]interface {}{&#34;additionalAttributes&#34;:map[string]interface {}{&#34;defaultBucket&#34;:&#34;serene-courier-331011.appspot.com&#34;, &#34;defaultHostname&#34;:&#34;serene-courier-331011.ey.r.appspot.com&#34;}, &#34;assetType&#34;:&#34;appengine.googleapis.com/Application&#34;, &#34;displayName&#34;:&#34;serene-courier-331011&#34;, &#34;location&#34;:&#34;europe-west3&#34;, &#34;name&#34;:&#34;//appengine.googleapis.com/apps/serene-courier-331011&#34;, &#34;parentAssetType&#34;:&#34;cloudresourcemanager.googleapis.com/Project&#34;, &#34;parentFullResourceName&#34;:&#34;//cloudresourcemanager.googleapis.com/projects/serene-courier-331011&#34;, &#34;project&#34;:&#34;projects/740535132954&#34;, &#34;state&#34;:&#34;SERVING&#34;, &#34;versionedResources&#34;:[]interface {}{map[string]interface {}{&#34;resource&#34;:map[string]interface {}{&#34;authDomain&#34;:&#34;gmail.com&#34;, &#34;codeBucket&#34;:&#34;staging.serene-courier-331011.appspot.com&#34;, &#34;databaseType&#34;:&#34;CLOUD_DATASTORE_COMPATIBILITY&#34;, &#34;defaultBucket&#34;:&#34;serene-courier-331011.appspot.com&#34;, &#34;defaultHostname&#34;:&#34;serene-courier-331011.ey.r.appspot.com&#34;, &#34;dispatchRules&#34;:[]interface {}{map[string]interface {}{&#34;domain&#34;:&#34;api.priceline.azuresucks.de&#34;, &#34;path&#34;:&#34;/*&#34;, &#34;service&#34;:&#34;deal-checker-api&#34;}, map[string]interface {}{&#34;domain&#34;:&#34;api.priceline.gcprocks.de&#34;, &#34;path&#34;:&#34;/*&#34;, &#34;service&#34;:&#34;deal-checker-api&#34;}, map[string]interface {}{&#34;domain&#34;:&#34;priceline.azuresucks.de&#34;, &#34;path&#34;:&#34;/*&#34;, &#34;service&#34;:&#34;deal-checker-frontend&#34;}, map[string]interface {}{&#34;domain&#34;:&#34;priceline.gcprocks.de&#34;, &#34;path&#34;:&#34;/*&#34;, &#34;service&#34;:&#34;deal-checker-frontend&#34;}, map[string]interface {}{&#34;domain&#34;:&#34;azuresucks.de&#34;, &#34;path&#34;:&#34;/*&#34;, &#34;service&#34;:&#34;deal-checker-frontend&#34;}, map[string]interface {}{&#34;domain&#34;:&#34;www.azuresucks.de&#34;, &#34;path&#34;:&#34;/*&#34;, &#34;service&#34;:&#34;deal-checker-frontend&#34;}, map[string]interface {}{&#34;domain&#34;:&#34;api.gluco.azuresucks.de&#34;, &#34;path&#34;:&#34;/*&#34;, &#34;service&#34;:&#34;gluco-api&#34;}, map[string]interface {}{&#34;domain&#34;:&#34;api.gluco.gcprocks.de&#34;, &#34;path&#34;:&#34;/*&#34;, &#34;service&#34;:&#34;gluco-api&#34;}, map[string]interface {}{&#34;domain&#34;:&#34;*&#34;, &#34;path&#34;:&#34;/gluco/api/*&#34;, &#34;service&#34;:&#34;gluco-api&#34;}, map[string]interface {}{&#34;domain&#34;:&#34;hertz.azuresucks.de&#34;, &#34;path&#34;:&#34;/*&#34;, &#34;service&#34;:&#34;hertz-prices&#34;}, map[string]interface {}{&#34;domain&#34;:&#34;*&#34;, &#34;path&#34;:&#34;/tasks/hertz-prices&#34;, &#34;service&#34;:&#34;hertz-prices&#34;}, map[string]interface {}{&#34;domain&#34;:&#34;filmlist.azuresucks.de&#34;, &#34;path&#34;:&#34;/*&#34;, &#34;service&#34;:&#34;filmlist&#34;}}, &#34;featureSettings&#34;:map[string]interface {}{&#34;splitHealthChecks&#34;:true, &#34;useContainerOptimizedOs&#34;:true}, &#34;gcrDomain&#34;:&#34;eu.gcr.io&#34;, &#34;iap&#34;:map[string]interface {}{&#34;enabled&#34;:true, &#34;oauth2ClientId&#34;:&#34;740535132954-m422lr23gunkq2s00knv648rljjo742p.apps.googleusercontent.com&#34;, &#34;oauth2ClientSecretSha256&#34;:&#34;075cd34cafec0276dc28aec001a34ca910fd2e5bf8ffbd527bdf8b4440704e06&#34;}, &#34;id&#34;:&#34;serene-courier-331011&#34;, &#34;locationId&#34;:&#34;europe-west3&#34;, &#34;name&#34;:&#34;apps/serene-courier-331011&#34;, &#34;servingStatus&#34;:&#34;SERVING&#34;}, &#34;version&#34;:&#34;v1&#34;}}}

