<div id="header" align="center">
  <img src=https://media.giphy.com/media/SUcApSWjPwQMARvcM8/giphy.gif width="200"/>
</div>

# Front-end Developer 👩‍💻

Front-end developer. Python & AI enthusiast. I build interfaces and love the logic behind the data. Started with JS and CSS, and I'm always chasing the next interesting problem. Let's build something together.

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/materialui/materialui-original.svg" title="Material UI" alt="Material UI" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/redux/redux-original.svg" title="Redux" alt="Redux " width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/stackoverflow/stackoverflow-original-wordmark.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/bootstrap/bootstrap-original-wordmark.svg" title="bootstrap" **alt="bootstrap" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/microsoftsqlserver/microsoftsqlserver-original-wordmark.svg" title="microsoftsqlserver" **alt="next.js" width="40" height="40"/>  
  <img src="https://github.com/devicons/devicon/blob/master/icons/tailwindcss/tailwindcss-original-wordmark.svg" title="tailwind" **alt="tailwind" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/sass/sass-original.svg" title="sass" **alt="sass" width="40" height="40"/>  
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="python" **alt="python" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original-wordmark.svg" title="docker" **alt="docker" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/postman/postman-original-wordmark.svg" title="postman" **alt="postman" width="40" height="40"/>
  
</div>

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa
