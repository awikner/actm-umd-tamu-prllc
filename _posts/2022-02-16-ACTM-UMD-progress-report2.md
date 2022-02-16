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
    var adobeDCView = new AdobeDC.View({clientId: "7720360b9b874923aad9b79d5bc981df", divId: "adobe-dc-view"});
    adobeDCView.previewFile({
      content: { promise: <FILE_PROMISE> }
      metaData: { fileName: "{{base}}/images/{{page.image-folder}}/ACTM_DARPA_Progress_Report_2__Feb__2022_.pdf" }
    }, {});
  });
</script>
