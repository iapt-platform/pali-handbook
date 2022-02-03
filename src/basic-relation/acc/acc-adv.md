<script>window.$docsify = {search: 'auto',name: 'mermaid',repo: 'https://github.com/mermaid-js/mermaid',loadSidebar: true,mergeNavbar: true,maxLevel: 4,subMaxLevel: 2,markdown: {renderer: {code: function(code, lang) {if (lang === "mermaid") {return ('<div class="mermaid">' + mermaid.render('mermaid-svg-' + num++, code) + "</div>
");}return this.origin.code.apply(this, arguments);}}},plugins: [function (hook, vm) {hook.beforeEach(function (html) {url = 'https://github.com/mermaid-js/mermaid/blob/develop/docs/' + vm.route.filevar editHtml = '[:memo: Edit this Page](' + url + ')\n'return editHtml + html})}]}var num = 0;const isDarkMode = window.matchMedia("(prefers-color-scheme: dark)").matchesconst conf = { logLevel:4, startOnLoad: false, themeCSS:'.label { font-family: Source Sans Pro,Helvetica Neue,Arial,sans-serif; }' };if(isDarkMode && false) conf.theme = 'dark';mermaid.initialize(conf);</script>

<script>window.onhashchange = function(a) {if(location) {ga('send', 'pageview', location.hash);}} </script>
  <script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script>
  <script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/search.min.js"></script>
  <script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/ga.min.js"></script>

# ADV


* English： Adverbial Relation
* 中文： 副词-動詞 關係
* 巴利语： kiriyāvisesana - kiriyā

某些名词被用为副词或动词修饰语，他们通常是：
- **中**性·**单**数·**宾**格

>sukhaṃ sayati<br>睡得香
><div class="mermaid">
>graph LR
>A(sukkhaṃ<br>快乐)--ADV-->B(sayati<br>睡)
></div>

