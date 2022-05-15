[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=SB-SLIM)](https://github.com/anuraghazra/github-readme-stats)

<!--START_SECTION:waka-->
name: Waka Readme

on:
  workflow_dispatch:
  schedule:
    # Runs at every 12AM UTC
    - cron: "0 0 * * *"

jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          SHOW_TITLE: true
          BLOCKS: ⣀⣄⣤⣦⣶⣷⣿
<!--END_SECTION:waka-->
