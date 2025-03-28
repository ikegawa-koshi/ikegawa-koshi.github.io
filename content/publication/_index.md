---
title: 学術文献情報
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
      title: 学術誌論文 (Journal Articles)
      text: ""
      filters:
        folders:
          - publication
        tag: "journal"
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: 国際会議論文 (Conference Papers)
      text: ""
      filters:
        folders:
          - publication
        tag: "proceedings"
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: 国際会議ポスター予稿 (Conference Posters)
      text: ""
      filters:
        folders:
          - publication
        tag: "poster"
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: 日本国内会議論文 (Japanese Conference Papers)
      text: ""
      filters:
        folders:
          - publication
        tag: "japan_proceedings"
        exclude_featured: false
    design:
      view: citation
  # - block: collection
  #   content:
  #     title: その他 (Misc.)
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       tag: "misc"
  #       exclude_featured: false
  #   design:
  #     view: citation
  - block: markdown
    content:
      title: その他 (Misc.)
      text: |-
        - Koshi Ikegawa, Nao Nishijima, Yoji Ozawa, Katsuhiro Fukunaka, Hironori Emaru, Masaru Hisada, Akihito Kaneko, Eiichi Araki, Ai Okada, and Yuichi Shiraishi.
        Secure and Traceable System for Genomic Data Sharing Using Hyperledger Fabric Blockchain.
        2020年日本バイオインフォマティクス学会年会 第9回 生命医薬情報学連合大会 (IIBMP2020), 2020年09月.
        - Minto Funakoshi, Koshi Ikegawa, and Buntarou Shizuki.
        Capacitance- and Phase-Based Detection Technique of Finger Bend and Touched Hand Using Ring-Shaped Device.
        CHI 2019 symposia on Asian CHI Symposium: Emerging HCI Research Collection, May 2019, 7 pages.
        - Takuto Nakamura, Koshi Ikegawa, Shogo Tsuchikiri, Keita Saito, Kazushi Kamezawa, Yuki Hashimoto, and Buntarou Shizuki.
        Touch Interface Design System in Multilayered Urushi Circuit.
        CHI 2019 symposia on Asian CHI Symposium: Emerging HCI Research Collection, May 2019, 7 pages.
        - 舩越南斗, 池川航史, 志築文太郎, 高橋伸.
        位相に基づく指輪型入力デバイスの検討.
        情報処理学会研究報告, Vol.2018-HCI-182, No. 34, 6 pages, 2018年8月, 情報処理学会, 2019年03月.
        - 池川航史, 志築文太郎.
        磁気計測に基づくブロック型タンジブル3Dモデリングシステム.
        第26回インタラクティブシステムとソフトウェアに関するワークショップ論文集 (WISS 2018), 予稿なしデモ・ポスター, 日本ソフトウェア科学会, 2018年09月.
        - Koshi Ikegawa, Shuta Nakamae, and Buntarou Shizuki.
        A Block System with Magnetism-based Structure Recognition
        CHI 2017 symposia on Asian CHI Symposium: Emerging HCI Research Collection, May 2017, 8 pages.
        - 池川航史, 中前秀太, 志築文太郎.
        磁気計測に基づき構造認識を行うブロックシステム.
        インタラクション2017論文集, 情報処理学会, 2017年02月, pp. 707-711.
        - 池川航史, 川上由紀.
        遺伝的アルゴリズムにより設計した周波数選択板によるマイクロストリップアンテナの利得向上効果に関する研究.
        電子情報通信学会 北陸支部 平成26年度学生による研究発表会, 電子情報通信学会, 2015年03月, 1 page.
  - block: collection
    content:
      title: 学位論文（Thesis）
      text: ""
      filters:
        folders:
          - publication
        tag: "thesis"
        exclude_featured: false
    design:
      view: citation
---