<!doctype html>
<html>
	
     <head>
	 <title>MAPA EUROPY</title>
     </head>
     <body>
<div id="openai-chat"></div>
<script src="https://api.openai.com/v1/code/sk-2IHyQonMdUmVTMnniUtBT3BlbkFJb1qOpvKutesTaxSx1N2r/generate?prompt=Hello&model=text-davinci-002"></script>
<script>
  var el = document.getElementById('openai-chat');
  el.innerHTML = JSON.parse(this.responseText).data.response;
</script>
</body>
</html>
