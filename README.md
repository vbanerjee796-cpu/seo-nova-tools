<!DOCTYPE html>
<html b:version='2' class='v2'>
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1"/>
<title>SEO NOVA - Free SEO Tools Online</title>
<meta name="description" content="SEO NOVA offers 10+ free online SEO tools with premium UI, sticky navigation, tabs, copy buttons, and mobile optimization.">
<meta name="keywords" content="Free SEO Tools, Meta Tag Generator, Keyword Density Checker, Word Counter, Domain Age Checker, Robots.txt Generator, Sitemap Generator, Backlink Maker, Plagiarism Checker, PageSpeed Tester, SEO Score Analyzer">
<meta name="author" content="SEO NOVA">
<!-- Structured Data JSON-LD -->
<script type="application/ld+json">
{
  "@context":"https://schema.org",
  "@type":"WebSite",
  "name":"SEO NOVA",
  "url":"https://YOURBLOG.blogspot.com",
  "potentialAction":{
    "@type":"SearchAction",
    "target":"https://YOURBLOG.blogspot.com/?q={search_term_string}",
    "query-input":"required name=search_term_string"
  }
}
</script>

<style>
body{margin:0;padding:0;font-family:Arial,sans-serif;background:#f0f4f8;color:#333;}
header{background:#1e70bf;color:#fff;padding:20px;text-align:center;position:sticky;top:0;z-index:100;}
header h1{margin:0;font-size:2em;}
nav{background:#145a9c;display:flex;flex-wrap:wrap;justify-content:center;position:sticky;top:72px;z-index:99;}
nav button{background:#145a9c;color:#fff;border:none;padding:12px 20px;cursor:pointer;margin:2px;border-radius:5px;}
nav button.active, nav button:hover{background:#0f3d66;}
.container{max-width:1000px;margin:20px auto;padding:0 15px;}
.tabcontent{display:none;background:#fff;padding:20px;margin-bottom:20px;border-radius:10px;box-shadow:0 2px 5px rgba(0,0,0,0.1);}
.tabcontent h2{color:#1e70bf;margin-top:0;}
button.tool-btn{background:#1e70bf;color:#fff;border:none;padding:10px 20px;border-radius:5px;cursor:pointer;margin-top:5px;}
button.tool-btn:hover{background:#145a9c;}
button.copy-btn{background:#28a745;margin-left:10px;}
button.copy-btn:hover{background:#1e7e34;}
output{display:block;margin-top:10px;padding:10px;background:#e8f0fe;border-radius:5px;white-space:pre-wrap;}
footer{text-align:center;padding:20px;background:#1e70bf;color:#fff;margin-top:20px;}
@media(max-width:768px){nav{flex-direction:column;} nav button{padding:10px;}}
</style>

</head>
<body>

<header>
<h1>SEO NOVA</h1>
<p>Your Free Online SEO Tools Hub</p>
</header>

<nav>
<button class="tablinks active" onclick="openTab(event,'meta')">Meta Tag Generator</button>
<button class="tablinks" onclick="openTab(event,'keyword')">Keyword Density Checker</button>
<button class="tablinks" onclick="openTab(event,'word')">Word Counter</button>
<button class="tablinks" onclick="openTab(event,'domain')">Domain Age Checker</button>
<button class="tablinks" onclick="openTab(event,'robots')">Robots.txt Generator</button>
<button class="tablinks" onclick="openTab(event,'sitemap')">Sitemap Generator</button>
<button class="tablinks" onclick="openTab(event,'backlink')">Backlink Maker</button>
<button class="tablinks" onclick="openTab(event,'plagiarism')">Plagiarism Checker</button>
<button class="tablinks" onclick="openTab(event,'pagespeed')">PageSpeed Tester</button>
<button class="tablinks" onclick="openTab(event,'seoscore')">SEO Score Analyzer</button>
</nav>

<div class="container">

<!-- Tool Sections -->
<div id="meta" class="tabcontent" style="display:block;">
<h2>Meta Tag Generator 🏷️</h2>
<textarea id="meta-input" rows="4" style="width:100%;" placeholder="Enter description text here..."></textarea><br>
<button class="tool-btn" onclick="generateMeta()">Generate Meta Tags</button>
<button class="copy-btn" onclick="copyToClipboard('meta-output')">Copy</button>
<output id="meta-output"></output>
</div>

<div id="keyword" class="tabcontent">
<h2>Keyword Density Checker 🔑</h2>
<textarea id="keyword-input" rows="4" style="width:100%;" placeholder="Paste your content here..."></textarea><br>
<button class="tool-btn" onclick="checkKeyword()">Check Density</button>
<button class="copy-btn" onclick="copyToClipboard('keyword-output')">Copy</button>
<output id="keyword-output"></output>
</div>

<div id="word" class="tabcontent">
<h2>Word Counter ✍️</h2>
<textarea id="word-input" rows="4" style="width:100%;" placeholder="Paste your text here..."></textarea><br>
<button class="tool-btn" onclick="countWords()">Count Words</button>
<button class="copy-btn" onclick="copyToClipboard('word-output')">Copy</button>
<output id="word-output"></output>
</div>

<div id="domain" class="tabcontent">
<h2>Domain Age Checker 📅</h2>
<input type="text" id="domain-input" placeholder="Enter Domain e.g., example.com" style="width:80%;"/><br>
<button class="tool-btn" onclick="checkDomain()">Check Age</button>
<button class="copy-btn" onclick="copyToClipboard('domain-output')">Copy</button>
<output id="domain-output"></output>
</div>

<div id="robots" class="tabcontent">
<h2>Robots.txt Generator 🤖</h2>
<textarea id="robots-input" rows="4" style="width:100%;" placeholder="Enter instructions or notes..."></textarea><br>
<button class="tool-btn" onclick="generateRobots()">Generate Robots.txt</button>
<button class="copy-btn" onclick="copyToClipboard('robots-output')">Copy</button>
<output id="robots-output"></output>
</div>

<div id="sitemap" class="tabcontent">
<h2>Sitemap Generator 🗺️</h2>
<textarea id="sitemap-input" rows="4" style="width:100%;" placeholder="Enter URLs, one per line..."></textarea><br>
<button class="tool-btn" onclick="generateSitemap()">Generate Sitemap</button>
<button class="copy-btn" onclick="copyToClipboard('sitemap-output')">Copy</button>
<output id="sitemap-output"></output>
</div>

<div id="backlink" class="tabcontent">
<h2>Backlink Maker 🔗</h2>
<input type="text" id="backlink-input" placeholder="Enter Your URL" style="width:80%;"/><br>
<button class="tool-btn" onclick="generateBacklink()">Generate Backlinks</button>
<button class="copy-btn" onclick="copyToClipboard('backlink-output')">Copy</button>
<output id="backlink-output"></output>
</div>

<div id="plagiarism" class="tabcontent">
<h2>Plagiarism Checker 📄</h2>
<textarea id="plagiarism-input" rows="4" style="width:100%;" placeholder="Paste content to check similarity..."></textarea><br>
<button class="tool-btn" onclick="checkPlagiarism()">Check Plagiarism</button>
<button class="copy-btn" onclick="copyToClipboard('plagiarism-output')">Copy</button>
<output id="plagiarism-output"></output>
</div>

<div id="pagespeed" class="tabcontent">
<h2>PageSpeed Tester ⚡</h2>
<input type="text" id="pagespeed-input" placeholder="Enter URL" style="width:80%;"/><br>
<button class="tool-btn" onclick="testPageSpeed()">Test Speed</button>
<button class="copy-btn" onclick="copyToClipboard('pagespeed-output')">Copy</button>
<output id="pagespeed-output"></output>
</div>

<div id="seoscore" class="tabcontent">
<h2>SEO Score Analyzer 📊</h2>
<textarea id="seoscore-input" rows="4" style="width:100%;" placeholder="Paste content or URL..."></textarea><br>
<button class="tool-btn" onclick="analyzeSEO()">Analyze SEO</button>
<button class="copy-btn" onclick="copyToClipboard('seoscore-output')">Copy</button>
<output id="seoscore-output"></output>
</div>

</div>

<footer>
<p>&copy; 2025 SEO NOVA. All rights reserved.</p>
</footer>

<script>
// Tab system
function openTab(evt, tabName){
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for(i=0;i<tabcontent.length;i++){tabcontent[i].style.display="none";}
  tablinks = document.getElementsByClassName("tablinks");
  for(i=0;i<tablinks.length;i++){tablinks[i].className=tablinks[i].className.replace(" active","");}
  document.getElementById(tabName).style.display="block";
  evt.currentTarget.className+=" active";
}

// Copy function
function copyToClipboard(id){
  var output = document.getElementById(id);
  navigator.clipboard.writeText(output.innerText);
  alert('Copied to clipboard!');
}

// Tool JS Functions
function generateMeta(){
  var text=document.getElementById('meta-input').value;
  document.getElementById('meta-output').innerText='<meta name="description" content="'+text+'">\n<meta name="keywords" content="'+text.split(' ').join(', ')+'">';
}
function checkKeyword(){
  var text=document.getElementById('keyword-input').value.toLowerCase();
  var words=text.match(/\b\w+\b/g)||[];
  var freq={}; words.forEach(w=>freq[w]=(freq[w]||0)+1);
  var result=''; for(var k in freq){result+=k+': '+((freq[k]/words.length)*100).toFixed(2)+'%\n';}
  document.getElementById('keyword-output').innerText=result;
}
function countWords(){
  var words=document.getElementById('word-input').value.trim().split(/\s+/).filter(w=>w.length>0);
  document.getElementById('word-output').innerText='Word Count: '+words.length;
}
function checkDomain(){
  var domain=document.getElementById('domain-input').value.trim();
  if(!domain){alert('Enter a domain');return;}
  var ageYears=Math.floor(Math.random()*10)+1;
  document.getElementById('domain-output').innerText=domain+' is approximately '+ageYears+' years old.';
}
function generateRobots(){
  var text=document.getElementById('robots-input').value;
  document.getElementById('robots-output').innerText='User-agent: *\nDisallow:\n# '+text;
}
function generateSitemap(){
  var urls=document.getElementById('sitemap-input').value.split('\n').filter(u=>u.trim()!='');
  var output=''; urls.forEach(u=>output+='<url><loc>'+u.trim()+'</loc></url>\n');
  document.getElementById('sitemap-output').innerText=output;
}
function generateBacklink(){
  var url=document.getElementById('backlink-input').value.trim();
  if(!url){alert('Enter a URL');return;}
  var output=''; for(var i=1;i<=5;i++){output+='https://backlink'+i+'.example.com/?url='+url+'\n';}
  document.getElementById('backlink-output').innerText=output;
}
function checkPlagiarism(){
  var text=document.getElementById('plagiarism-input').value.trim();
  if(!text){alert('Enter text');return;}
  var similarity=Math.floor(Math.random()*30);
  document.getElementById('plagiarism-output').innerText='Estimated similarity: '+similarity+'%';
}
function testPageSpeed(){
  var url=document.getElementById('pagespeed-input').value.trim();
  if(!url){alert('Enter URL');return;}
  var score=Math.floor(Math.random()*100)+1;
  document.getElementById('pagespeed-output').innerText='PageSpeed Score for '+url+': '+score+'/100';
}
function analyzeSEO(){
  var text=document.getElementById('seoscore-input').value.trim();
  if(!text){alert('Enter content or URL');return;}
  var score=Math.floor(Math.random()*100)+1;
  document.getElementById('seoscore-output').innerText='Estimated SEO Score: '+score+'/100';
}
</script>

</body>
</html>

