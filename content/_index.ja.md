---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: collection
    content:
      title: ❐ 最近の論文 ❐
      text: ""
      count: 3
      filters:
        folders:
          - ref-list
        exclude_featured: false
      archive:
        enable: false
    design:
      view: citation
      spacing:
        padding: 

  - block: markdown
    content:
      title: '❐ 研究のハイライト ❐'
      subtitle: ''
      text: |-
        ### <center>モバイルアプリ駆動による地方型観光エコシステムの構築</center>

        <p style="font-size:90%; text-align:justify">私の研究は，地方着地型観光のエコシステムを強化し，個人と地域社会の持続可能性に貢献することを目的としています．</p>

        <p style="font-size:90%; text-align:justify"><span style="font-weight: bold;">観光事業者の視点：</span>ウォーキング・ツーリズムは，地域のビジネスにとって魅力的な選択肢となっています．これは，既存の地域資源とストーリーを組み合わせることで新たな価値を付加できる"あらゆる地域に開かれたスタイル"です．ウォーキング・ツーリズムのデジタル化は，地域主導の取り組みを加速し，都市規模の貴重な分析を提供することができます．</p>

        <p style="font-size:90%; text-align:justify"><span style="font-weight: bold;">観光者の視点から：</span>ウォーキング・ツーリズムは，個人の健康と文化的体験を大幅に向上させます．まず歩くことは，筋力を強化し，ストレスや不安を軽減する低負荷の運動として健康増進に寄与します．そして，観光客が周囲と深く関わり，地域住民との交流を育み，隠れた地域ストーリーを発見することを可能にします．</p>

        <p style="font-size:90%; text-align:justify; color:gray;">"There is nothing special to visit in my hometown..."</p>
        
        <p style="font-size:90%; text-align:justify; color:gray;">"Actually, the real voyage of discovery consists not in seeking new landscapes, but in having new 'digital' eyes."</p>

        ---

        #### ◉ 歩行推薦ルートの開発に資する人流ヒートマップ生成とスコアリング法の研究 (2021–)

        <img width="100%" src="home/graphical-abstract-topic1.png">

        <p style="font-size:90%; text-align:justify">歩行推薦ルートを構成するスポットと歩行経路の両方を考慮したコスト効率の高いデジタルフィードバックシステムを確立することは，持続可能な地域観光を促進する上での課題です．本研究では，スマートフォンやその他のデバイスに標準装備されているモバイルセンサーデータの自動収集と分析に基づき，観光資源への観光客のアクセス（注目）をマッピングすることで，既存の推薦ルートの評価と改善に貢献するフィードバックシステムについて議論します．</p>

        <p style="font-size:70%; text-align:left; font-weight: bold;">references:</p>
        <p style="font-size:70%; text-align:left;">[1] Sasaki et al. (2020). Articulated Trajectory Mapping for Reviewing Walking Tours. ISPRS Int. J. Geo-Inf. 9(10):610. <a href="https://doi.org/10.3390/ijgi9100610">https://doi.org/10.3390/ijgi9100610</a></p>
        <p style="font-size:70%; text-align:left;">[2] Sasaki et al. (2023). Mobile Collaborative Heatmapping to Infer Self-Guided Walking Tourists’ Preferences for Geomedia.. ISPRS Int. J. Geo-Inf. 12(7):283. <a href="https://doi.org/10.3390/ijgi12070283">https://doi.org/10.3390/ijgi12070283</a></p>

        ---

        #### ◉ まち規模な位置情報サービスのためのジオフェンシング自動設計手法の研究 (2023–)

        <img width="100%" src="home/graphical-abstract-topic2.png">

        <p style="font-size:90%; text-align:justify">プロアクティブな位置情報サービスの中核技術として知られるのがジオフェンシングです．ジオフェンシングは，仮想的な地理境界（ジオフェンス）へのユーザーの出入りを監視し，クーポンの送信や音声ガイドの再生といったサービスをトリガーします．本研究の目的は，観光における位置情報サービスの設計問題を定式化し，収集したモバイルセンサデータからダイナミックな観光者の歩行パターンを解析して，ジオフェンスパラメータを生成する計算機ソリューションを開発することです．</p>

        <p style="font-size:70%; text-align:left; font-weight: bold;">references:</p>
        <p style="font-size:70%; text-align:left;">[1] Sasaki et al. (2020). Data-Driven Geofencing Design for POI Notifiers Utilizing Genetic Algorithm. ISPRS Int. J. Geo-Inf. 13(6):174. <a href="https://doi.org/10.3390/ijgi13060174">https://doi.org/10.3390/ijgi13060174</a></p>

        ---

        #### ◉ オンサイトラジオ - 階層型ジオフェンシングと大規模言語モデルを用いた生成型オーディオツアーの研究 (2024–)

        <img width="100%" src="home/graphical-abstract-topic3.png">

        <p style="font-size:90%; text-align:justify">POI（Point-of-Interest）ベースのガイドアプリケーションは，地方都市の環境でいくつかの課題に直面しています．特筆すべきスポットが少ないエリアでは提供できるコンテンツが不足し，ユーザーのインタラクションの機会が減少することが避けられないのです．また、一部の観光客が想定ルートから外れてしまうと，コンテンツのストーリーを理解するために最適な流れが崩れてしまうこともあります．私たちの提案は，階層型ジオフェンシングと大規模言語モデルによる会話生成技術を組み合わせたもので，モバイルアプリを通じて，より柔軟で連続的なガイドインタラクションを提供します．再生ボタンを押し，スマートフォンをポケットに入れて歩き始めるだけで，あなたの一歩一歩がバーチャルキャラクターによる魅力的なストーリーテリングに変わります．</p>

        <p style="font-size:70%; text-align:left; font-weight: bold;">references:</p>
        <p style="font-size:70%; text-align:left;"></p>

    design:
      columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
