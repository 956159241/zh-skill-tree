## 项目创建
git clone https://github.com/956159241/zh-skill-tree.git
git submodule add https://github.com/956159241/graphical-front-end.git graphical-front-end


<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Markmap</title>
    <style>
      svg.markmap {
        width: 100%;
        height: 100vh;
      }
    </style>
    <script src="https://cdn.jsdelivr.net/npm/markmap-autoloader@0.14.4-alpha.1"></script>
  </head>
  <body>
    <div class="markmap">
      <script type="text/template">
        ---
        markmap:
          maxWidth: 300
          colorFreezeLevel: 2
        ---

        # markmap

        ## Links

        - <https://markmap.js.org/>
        - [GitHub](https://github.com/markmap/markmap)

        ## Related

        - [coc-markmap](https://github.com/markmap/coc-markmap)
        - [gatsby-remark-markmap](https://github.com/markmap/gatsby-remark-markmap)

        ## Features

        - links
        - **inline** ~~text~~ *styles*
        - multiline
          text
        - `inline code`
        -
            ```js
            console.log('code block');
            ```
        - Katex - $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$
        - This is a very very very very very very very very very very very very very very very long line.
      </script>
    </div>
  </body>
</html>
