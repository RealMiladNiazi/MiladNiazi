# MiladNiazi

[![My Awesome Stats](https://awesome-github-stats.azurewebsites.net/user-stats/RealMiladNiazi?cardType=github&theme=github-dark&showIcons=false)](https://git.io/awesome-stats-card)

name: Indepth analysis
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.languages.indepth.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ""
  plugin_languages: yes
  plugin_languages_ignored: >-
    html, css, tex, less, dockerfile, makefile, qmake, lex, cmake, shell,
    gnuplot
  plugin_languages_indepth: yes
  plugin_languages_details: lines, bytes-size
  plugin_languages_limit: 4
  plugin_languages_analysis_timeout: 15
