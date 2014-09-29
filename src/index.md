---
header-includes: |
    <script src="js/gooan.js" type="text/javascript"></script>
    <script src="js/scale.fix.js" type="text/javascript"></script>
    <script src="js/jquery.min.js" type="text/javascript"></script>
    <script src="js/downloadepub.js" type="text/javascript"></script>
    <script src="js/gotorepo.js" type="text/javascript"></script>
    <script src="js/loader.js" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
    //<![CDATA[
    MathJax.Hub.Config({
        jax: [
            "input/TeX",
            "output/SVG",
        ],
        extensions: [
            "tex2jax.js",
            "MathEvents.js",
        ],
        TeX: {
            extensions: [
                "AMSmath.js",
                "AMSsymbols.js",
            ]
        },
        MathMenu: {
            showRenderer: false
        },
        menuSettings: {
            zoom: "Click"
        },
        messageStyle: "none",
    });
    //]]>
    </script>
    <script src="MathJax/MathJax.js" type="text/javascript"></script>
css: stylesheets/styles.css
title: Nameless
...

<div class="wrapper">
<header>

# Nameless

Put some very short discription here.

- <a class="buttons download" onclick="DownloadEpub();">Download ebook</a>
- <a class="buttons github" onclick="GotoRepo();">View On GitHub</a>
- <a class="buttons menu" href="#welcome.html">Contents</a>

</header>

<section>
<div id="content"></div>
</section>

<footer>
Hosted on [GitHub Pages](http://pages.github.com) using the Dinky theme
</footer>
</div>

<!--[if !IE]><script>fixScale(document);</script><![endif]-->

