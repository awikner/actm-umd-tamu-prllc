---
layout: post
title: Month 2 Milestone Progress Report
category: reports
image-folder: 2022-02-16-ACTM-UMD-progress-report2-media
---
{% include base.html %}
<div id="adobe-dc-view"></div>
<script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
<script type="text/javascript">
  document.addEventListener("adobe_dc_view_sdk.ready", function(){
    var adobeDCView = new AdobeDC.View({clientId: "fb1b04b20faa4b3c81d632bd8a00270e", divId: "adobe-dc-view"});
    adobeDCView.previewFile({
      content:{location: {url: "{{base}}/images/{{page.image-folder}}/ACTM_DARPA_Progress_Report_2__Feb__2022_.pdf"}},
      metaData:{ fileName: "ACTM_DARPA_Progress_Report_2__Feb__2022_.pdf" }
    }, {embedMode: "IN_LINE"});
  });
</script>
