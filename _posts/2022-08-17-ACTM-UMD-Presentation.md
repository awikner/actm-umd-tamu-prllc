---
layout: post
title: August ACTM PI Meeting Presentation
category: presentations
image-folder: 2022-08-17-ACTM-UMD-Presentation-media
---
{% include base.html %}
<div id="adobe-dc-view" style="height: 576px; width: 800px;"></div>
<script src="https://documentcloud.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
  document.addEventListener("adobe_dc_view_sdk.ready", function(){
    var adobeDCView = new AdobeDC.View({clientId: "fb1b04b20faa4b3c81d632bd8a00270e", divId: "adobe-dc-view"});
    adobeDCView.previewFile({
      content:{location: {url: "{{base}}/images/{{page.image-folder}}/darpa_actm_vsv_presentation_July28_22.pdf"}},
      metaData:{ fileName: "darpa_actm_vsv_presentation_July28_22.pdf" }
    }, {embedMode: "SIZED_CONTAINER"});
  });
</script>
