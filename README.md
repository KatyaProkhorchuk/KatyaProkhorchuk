### Hi there 👋

<!--
**KatyaProkhorchuk/KatyaProkhorchuk** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=KatyaProkhorchuk)](https://git.io/streak-stats)<br>
- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9![](https://komarev.com/ghpvc/?username=KatyaProkhorchuk)
