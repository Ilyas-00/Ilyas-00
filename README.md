<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<!--START_SECTION:waka-->
name: Waka Readme

on:
  # for manual workflow trigger
  workflow_dispatch:
  schedule:
    # runs at 12 AM UTC (5:30 AM IST)
    - cron: "0 0 * * *"

jobs:
  update-readme:
    name: WakaReadme DevMetrics
    runs-on: ubuntu-latest
    steps:
        # this action name
      - uses: athul/waka-readme@master # do NOT replace with anything else
        with:
          GH_TOKEN: ${{ secrets.GH_TOKEN }} # optional if on profile readme
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }} # required
          ### meta
          API_BASE_URL: https://wakatime.com/api # optional
          REPOSITORY: Ilyas-00/WAKATIME_API_KEY # optional
          ### content
          SHOW_TITLE: true # optional
          SECTION_NAME: waka # optional
          BLOCKS: -> # optional
          CODE_LANG: rust # optional
          TIME_RANGE: all_time # optional
          LANG_COUNT: 10 # optional
          SHOW_TIME: true # optional
          SHOW_TOTAL: true # optional
          SHOW_MASKED_TIME: false # optional
          STOP_AT_OTHER: true # optional
          IGNORED_LANGUAGES: YAML JSON TOML # optional
          ### commit
          COMMIT_MESSAGE: Updated waka-readme graph with new metrics # optional
          TARGET_BRANCH: master # optional
          TARGET_PATH: README.md # optional
          COMMITTER_NAME: GitHubActionBot # optional
          COMMITTER_EMAIL: action-bot@github.com # optional
          AUTHOR_NAME: YOUR_NAME # optional
          AUTHOR_EMAIL: YOUR@EMAIL.com # optional
          # you can populate email-id with secretes instead
<!--END_SECTION:waka-->




<h3 align="center">{ Languages and Tools }</h3>
<br></br>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=c,py,ts,go,rust,docker" />
  </a>
</p>
<br></br> 
<h3 align="center"">{ Connect with me }</h3>
<p align="center">
<a href="https://codepen.io/il_yasss" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codepen.svg" alt="il_yasss" height="30" width="40" /></a>
<a href="https://dev.to/ilyas00" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/devto.svg" alt="ilyas00" height="30" width="40" /></a>
<a href="https://linkedin.com/in/ilyas-akioui" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="ilyas-akioui" height="30" width="40" /></a>
<a href="https://kaggle.com/ilyasakioui" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" alt="ilyasakioui" height="30" width="40" /></a>
<a href="https://instagram.com/ilyasss_91" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="ilyasss_91" height="30" width="40" /></a>
<a href="https://www.leetcode.com/elmarocchi" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="elmarocchi" height="30" width="40" /></a>
<a href="https://discord.gg/elmarocchi" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="elmarocchi" height="30" width="40" /></a>
</p>
<br></br> 
<!--
<p align="center">
  <a href="https://github.com/Ilyas-00">
    <img align="center" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Ilyas-00&hide_border=true&title_color=94b4a4&icon_color=FFFFFF&text_color=FFFFFF&bg_color=000000" alt="hhhhhhhhh"/>
</a>
  <br></br> 
    <img align="center" src="https://github-readme-stats.vercel.app/api?username=Ilyas-00&show_icons=true&hide_border=true&title_color=94b4a4&amp&icon_color=FFFFFF&amp&text_color=FFFFFF&amp&bg_color=000000&count_private=true&include_all_commits=true"/>
    <img align="center" height="195px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ilyas-00&text_color=FFFFFF&bg_color=000000&title_color=94b4a4&langs_count=15&layout=compact&hide_border=true" />
  <br></br>-->


</p>
<p align='center'>
<img src="https://komarev.com/ghpvc/?username=Ilyas-00">&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://img.shields.io/github/followers/Ilyas-00?style=social">&nbsp;&nbsp;&nbsp;&nbsp;
<!-- <img src="https://visitor-badge.glitch.me/badge?page_id=chinmay29hub.visitor-badge"> -->
</p>
<!--horizontal divider(gradiant)-->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"> 
