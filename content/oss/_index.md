---
title: OSS貢献
type: landing

design:
  # Default section spacing
  spacing: "3rem"

# View.
view: citation

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''

sections:
  - block: collection
    content:
      title: 審査有り国際会議発表
      text: ""
      filters:
        folders:
          - oss
        tag: "speech"
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    content:
      title: その他（Misc.）
      text: |-
        - 佐藤竜也, 池川航史, 長谷川学.
        Hyperledger概要と技術課題.
        Theory Meets Blockchain Engineering (TMBE). 2024年01月27日. Solidity House at 佐賀県, 日本.
        - 池川航史.
        ブロックチェーンを用いた自己主権型デジタルID管理.
        Hyperledger Tokyo - エンタープライズブロックチェーンワークショップ. 2023年10月17日. オンライン開催.
        - 池川航史.
        ブロックチェーンを用いた自己主権型デジタルID管理.
        WebX – Hyperledger Foundation Workshop. 2023年7月26日. 東京国際フォーラム at 東京都, 日本.
        - 池川航史.
        Hyperledger Fabric Private Chaincodeについて.
        Hyperledger Tokyo Meetup. 2021年10月07日. オンライン開催.
  - block: collection
    content:
      title: 翻訳活動
      text: ""
      filters:
        folders:
          - oss
        tag: "translation"
        exclude_featured: false
    design:
      view: citation
---