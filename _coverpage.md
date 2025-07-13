<img src="https://gh-guides.rweb.site/media/logo.png" alt="GitHub Guides Logo" width="120" height="120" :no-zoom>

# GitHub Guides

> Learn more about GitHub & GitHub pages as a developer.

- Step-by-step tutorials
- Helpful Resources
- Practical tips

### Themes - Choose Your Style

<div class="demo-theme-preview">
  <a data-theme="vue">vue.css</a>
  <a data-theme="buble">buble.css</a>
  <a data-theme="dark">dark.css</a>
  <a data-theme="pure">pure.css</a>
</div>

<style>
  .demo-theme-preview a {
    padding-right: 10px;
  }

  .demo-theme-preview a:hover {
    cursor: pointer;
    text-decoration: underline;
  }
</style>

<script>
  var preview = Docsify.dom.find('.demo-theme-preview');
  var themes = Docsify.dom.findAll('[rel="stylesheet"]');

  preview.onclick = function (e) {
    var title = e.target.getAttribute('data-theme');

    themes.forEach(function (theme) {
      theme.disabled = theme.title !== title;
    });
  };
</script>

[Get Started](#github-guides)
[GitHub](https://github.com/harys722/github-guides/)
