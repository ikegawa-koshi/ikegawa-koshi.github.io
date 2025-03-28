---
title: "ブロック構造物に対する磁気計測に基づく構造認識およびその3Dモデリングシステムへの応用"
authors:
- 池川航史
- "[指導教員: 志築文太郎]"
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2019-03-01"
# date: "2025-01-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2019-03-01"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["thesis"]

# Publication name and optional abbreviated publication name.
publication: "筑波大学 システム情報工学研究科 コンピュータサイエンス専攻"
publication_short: ""

abstract: "幼少期の頃、様々な夢を思い描きながらブロック遊びをした経験はあるだろうか。子どもた
ちが作り上げた作品を3D モデルとしてPC に読み込み、大型の3D プリンタを用いて同じ構
造を持つ物体を印刷することで、この夢を少しばかり現実のものとすることができるだろう。
本論文では、その夢を実現する第一歩として、ブロック構造物に対する磁気計測に基づく構
造認識手法を提案する。また、その構造認識手法を応用し、タンジブル3D モデリングシス
テムを作成した。これまでに、本研究の他にも積み木やLEGO のようなブロック型の物体を
3D モデリングに利用するシステムが研究されてきた。これらの多くは電子回路を内蔵したブ
ロックを用いて、ブロック同士が電気信号を送受信することによりブロック構造物の構造を
認識している。またブロック構造物全体を俯瞰できる位置に設置した深度カメラの映像から
構造を認識する手法も存在する。ただし、これらの手法にはブロック自体が複雑になるとい
う問題や、カメラ映像を用いることに伴ってオクルージョンが発生することから構造物全体
を認識できないという問題がある。これらの問題を解決するために、本論文では複数の磁気
センサを格子状に配置したハードウェアを用いたシステムを提案する。提案システムは、磁
石のみを内蔵するという単純な構造を持つブロックからなる構造物の構造認識を磁気計測に
基づいて行い、認識結果を3D モデルとしてディスプレイに描画する。本論文では、提案シス
テムの実装方法を示し、ブロック構造物の高さおよび3 軸磁気センサの使用個数を変化させ
たときの認識精度を評価する実験を行った。16 個の3 軸磁気センサを使用した場合、ブロッ
ク構造物の最大規模が2 × 2 × 2 のときの構造認識精度は80.1% であった。また、ブロック構
造物の最大規模を2 × 2 × 3 としたときの構造認識精度は17.7% であり、高さ方向に規模を大
きくすると認識精度が低下することが分かった。そこで、3 軸磁気センサを64 個使用した場
合の認識精度を評価する実験を行った。結果、ブロック構造物の最大規模を2 × 2 × 3 とした
ときの構造認識精度は77.7% であり、16 個の3 軸磁気センサを使用したときと比較して構造
認識精度は大きく向上することが分かった。"

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- thesis
featured: false

# links:
# - name: "DOI"
#   url: "https://doi.org/10.1145/3173225.3173285"
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
