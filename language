<html>
<head>
<script type="text/javascript"
        src="http://www.google.com/jsapi"></script>
<script type="text/javascript">

 // Initialize version 1.0 of Google AJAX API
 google.load("language", "1");

 function translate(lang) {
   var source = document.getElementById("article").innerHTML;
   var len = content.length;

   // Google Language API accepts 500 characters per request
   var words = 500;

   // This is for English pages, you can change the
   // sourcelang variable for other languages
   var sourcelang = "en";
   document.getElementById("translation").innerHTML = "";

   for(i=0; i<=(len/words); i++) {
     google.language.translate (source.substr(i*words, words),
                 "en", lang, function (result) {
     if (!result.error) {
     document.getElementById("translation").innerHTML
           = document.getElementById("translation").innerHTML
           + result.translation;
    } }); }

  // Hide the text written in the original language
  document.getElementById("article").style.display = 'none';
  return false;
 }

 // Switch to the original language

 function original() {
  document.getElementById("translation").style.display='none';
  document.getElementById("article").style.display = 'block';
  return false;
 }
</script>
</head>
<body>
<a href="#" onclick="original();">Switch to English</a>
<select onchange="translate(this.options[this.selectedIndex].value);">
 <option value="de">deutsch</option> <option value="pt">português</option>
 <option value="fr">français</option> <option value="ja">日本語</option>
 <option value="ar">عَرَبيْ</option> <option value="it">italiano</option>
 <option value="ru">pусский</option> <option value="po">polski</option>
 <option value="zh-CN">中文</option> <option value="es">español</option>
 <option value="ko">한국어</option> <option value="nl">nederlands</option>
 <option value="hi">हिन्दी </option> <option value="el">Ελληνική</option>
 <option value="ro">română</option>
</select>
<div id="translation"></div>
<div id="article">
<h3>Add Google AJAX Language API in your Website</h3>
<p>If you are ready to take the plunge, here’s what you need to do to get this working on your site.</p>
</div>
</body>
</html
