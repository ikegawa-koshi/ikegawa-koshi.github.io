---
title: "日本語フリック入力を用いたモバイル端末の把持姿勢識別"
authors:
- 永井美波
- 池川航史
- 志築文太郎
- 高橋伸
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2017-12-01"
# date: "2025-01-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2016-11-01"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "第25回インタラクティブシステムとソフトウェアに関するワークショップ論文集 (WISS 2017)"
publication_short: ""

abstract: "モバイル端末の操作における把持姿勢は，ユーザが置かれている状況によって変化する．把持姿勢
に適したユーザインタフェースを提供するためには，把持姿勢のリアルタイムな識別が必要となる．我々
は，モバイル端末における日本語の入力手法の主流となっている日本語フリック入力時の把持姿勢について
着目した．ユーザがフリック入力をしている際にモバイル端末内蔵のセンサから得られたデータを用いて把
持姿勢の識別を行う．内蔵センサから得られるデータから 83 個の特徴量を抽出し，機械学習の教師データ
とした．把持状態 5 種類とユーザ姿勢 2 種類の組み合わせから 10 種類の把持姿勢を識別し，精度を評価し
た．把持姿勢 10 種類の識別は Random Forest を用いた場合の結果が最も高精度であり，74.3%であった．
また，特徴量の重要度を算出し，フリック入力時に得られる特徴量が上位を占めていることを示した．
"

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- jproc
featured: false

# links:
# - name: "DOI"
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
