---
#cover: cover.jpg
layout: default
image-folder: actm_leadership_slide
---
{% include base.html %}

# Hybridizing Knowledge-based and Machine Learning Models for Climate Prediction

<div id="adobe-dc-view" style="width: 800px;"></div>
<script src="https://documentcloud.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){
		var adobeDCView = new AdobeDC.View({clientId: "fb1b04b20faa4b3c81d632bd8a00270e", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "{{base}}/images/{{page.image-folder}}/actm_leadership_slide.pdf"}},
			metaData:{fileName: "actm_leadership_slide.pdf"}
		}, {embedMode: "IN_LINE"});
	});
</script>
