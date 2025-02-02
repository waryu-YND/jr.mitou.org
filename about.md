---
layout: post
title: 未踏ジュニアとは
description: 本ページでは初めての方を対象としたコンテンツをまとめています。
---

<p style='margin: 50px auto;'><b>未踏ジュニアへようこそ!</b> 本ページでは初めての方を対象としたコンテンツをまとめています <i class="fas fa-tv green" aria-hidden="true"></i> ✨</p>

<div class="youtube" itemprop="video" itemscope itemtype="http://schema.org/VideoObject">
  <meta itemprop="isFamilyFriendly"     content="True">
  <meta itemprop="requiresSubscription" content="False">
  <meta itemprop="width"                content="1280">
  <meta itemprop="height"               content="720">
  <meta itemprop="thumbnailUrl"         content="https://i.gyazo.com/c9279aac3f89da401e0d3d14f570fa37.jpg">
  <meta itemprop="uploadDate"           content="2022-10-05">
  <meta itemprop="contentUrl"           content="https://youtube.googleapis.com/v/Eu42E-FXBME">
  <meta itemprop="embedUrl"             content="https://www.youtube.com/embed/Eu42E-FXBME?rel=0">
  <meta itemprop="name"                 content="未踏ジュニアとは？">
  <meta itemprop="description"          content="未踏ジュニアとは何か、IPA が実施する未踏事業とは何が違うのか、どういう関係なのか？といったことを３分で説明する動画です。「未踏」について知るキッカケになれば嬉しいです。">
  <iframe width="100%" src="https://www.youtube.com/embed/Eu42E-FXBME?list=PLNObH2jlC6lc3c-gRpILyQrMhlqBIRjKr" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<a href="https://www.youtube.com/playlist?list=PLNObH2jlC6lc3c-gRpILyQrMhlqBIRjKr" class="button">YouTubeで視聴する</a>

<br>

## 未踏ジュニアとは？ {#mitoujr}
独創的なアイデア、卓越した技術を持つ 17 歳以下の小中高生や[高専生](https://www.mext.go.jp/a_menu/koutou/kousen/index.htm)などを支援するプログラムです。

[IPA 未踏事業](https://www.ipa.go.jp/jinzai/mitou/about.html)という、経産省所管の独立行政法人情報処理推進機構（[IPA](https://www.ipa.go.jp/about/index.html)）が主催する、25 歳以下の若者を支援するプログラムがあります。この未踏事業の修了生を中心に設立・運営されているのが、**未踏ジュニア**です。

{% assign total_applications = 0 %}
{% assign total_creators     = 0 %}
{% for stat in site.data.stats %}
  {% assign total_applications = total_applications | plus: stat.applications %}
  {% assign total_creators     = total_creators     | plus: stat.creators     %}
{% endfor %}

2016年から未踏ジュニアが始まり、これまでに **{{ total_applications }} 件の応募、{{ total_creators }} 名のクリエータを支援・採択**してきました。

<div class="cover-photo">
  <img src="/assets/img/2022_cover.min.webp" data-src="/assets/img/2022_cover.webp"
     title="2022年度の未踏ジュニア集合写真 @ 東京大学" class="top-img lazyload" loading="lazy"
       alt="2022年度の未踏ジュニア集合写真 @ 東京大学">
   
</div>

<div class='flex'>
  <a href='/final'    class='button'>最新の採択例を見る</a>
  <a href='/projects' class='button'>過去の採択例を見る</a>
</div>

<br>

## 採択者への支援 {#supports}

未踏ジュニアに応募し、採択されると、採択者（クリエータ）は以下の支援が得られます。


<h3 id='supports-mentoring'>
  <a href='#supports-mentoring'><i class="fas fa-graduation-cap green"></i></a>
  メンタリングの提供
</h3>

担当の[メンター](/mentors)をはじめ、未踏事業の修了生らを中心とする各界で活躍するエンジニア・専門家の指導が受けられます。

<div class="tips">期間中は、毎週１時間ほど、オンラインでメンターと話せる機会があります。プログラミングの質問やプロジェクトの方針など、なんでも相談できます。</div>
<a href="/mentors" class="button">メンター紹介を見る</a>

<br>


<h3 id='supports-development'>
  <a href='#supports-development'><i class="fas fa-badge-dollar green"></i></a>
  開発資金の援助
</h3>

採択された各グループへ、50 万円を上限として開発資金の援助を行います。

例えばハードウェア開発で機材・資材を使いたい場面や、ソフトウェア開発で有料のAPI・サーバーを使いたい場面などで、50 万円まで使える仕組みになっています。

<img src="/assets/img/spinner.svg" data-src="/assets/img/about_development.webp"
   title="ハードウェア開発を支援している様子 @ CASE Shinjuku" class="top-img lazyload" loading="lazy"
     alt="ハードウェア開発を支援している様子 @ CASE Shinjuku" >

<br>


<h3 id='supports-expenses'>
  <a href='#supports-expenses'><i class="fas fa-gear green"></i></a>
  開発場所の援助
</h3>

必要に応じて、開発場所や工作機材などの援助を行います。

また[成果報告会](/final)などのイベントが現地開催となる場合、イベント参加のための交通費・宿泊費も支給されます。

<img src="/assets/img/spinner.svg" data-src="/assets/img/about_expenses.webp"
   title="ブース出展している様子 @ Maker Faire Tokyo 2023" class="top-img lazyload" loading="lazy"
     alt="ブース出展している様子 @ Maker Faire Tokyo 2023">
 

<br>


<h3 id='supports-awarding'>
  <a href='#supports-awarding'><i class="fas fa-link green"></i></a>
  未踏ジュニアスーパークリエータの認定
</h3>

特に顕著な成果を残したクリエータを、未踏ジュニアスーパークリエータとして認定します。[慶應義塾大学SFC](https://www.sfc.keio.ac.jp/news/012903.html)や[東京都立大学](https://cs.sd.tmu.ac.jp/admission_office.html)、[近畿大学](https://newscast.jp/news/1055602)に推薦枠で出願できます。

<img src="/assets/img/spinner.svg" data-src="/assets/img/about_awarding.webp"
   title="クリエータに修了証書を授与している様子 @ 東京大学" class="top-img lazyload" loading="lazy"
     alt="クリエータに修了証書を授与している様子 @ 東京大学">

<br>


## 応募〜採択の流れ {#guideline}
未踏ジュニアでは応募から採択までの流れや、応募書類（提案書）を書くコツ、採択者の体験談なども公開しています。提案書を良くするコツなども公開しているので、ぜひチェックしてみてください！

<img src="/assets/img/spinner.svg" data-src="/assets/img/illustration/chukan.svg"
   title="応募について身近な人などに相談している様子のイラスト" width="50%" class="post-photo lazyload"
     alt="応募について身近な人などに相談している様子のイラスト">

<div class='flex'>
  <a href="/guideline"       class="button">採択までの流れを見る</a>
  <a href="/download#voice"  class="button">採択者の体験談を見る</a>
</div>

## 運営団体について {#organizer}

未踏ジュニアは、[IPA 未踏事業](https://www.ipa.go.jp/jinzai/mitou/about.html)の修了生などが集まる一般社団法人未踏（[未踏社団](https://www.mitou.org/)）によって運営されています。未踏ジュニアは、未踏社団の取り組んでいる事業の１つです。

<div style='padding-top: 30px; max-width: 400px; margin: auto; display: block;'>
  <a href="https://www.mitou.org/">
    <img src="/assets/img/spinner.svg" data-src="/assets/img/mitou-foundation.png"
       title="一般社団法人未踏のロゴ画像" class="lazyload" loading="lazy" width='100%'
         alt="一般社団法人未踏のロゴ画像">
  </a>
</div>

<div class='flex'>
  <a href="https://www.ipa.go.jp/jinzai/mitou/about.html" class="button">IPA 未踏事業を見る</a>
  <a href="https://www.mitou.org/"  class="button">未踏社団を見る</a>
</div>

<h3 id='interviews'>
  <a href='#interviews'><i class="fa-brands fa-youtube green"></i></a>
  推薦のことば
</h3>

未踏関係者に『**なんで未踏?**』という質問をしてみました。未踏ジュニアについて一歩深く知るキッカケになれば嬉しいです <i class="far fa-laugh-squint" aria-hidden="true" /> <i class="far fa-thumbs-up" aria-hidden="true" />

<div class="youtube" itemprop="video" itemscope itemtype="http://schema.org/VideoObject">
  <meta itemprop="isFamilyFriendly"     content="True">
  <meta itemprop="requiresSubscription" content="False">
  <meta itemprop="width"                content="1280">
  <meta itemprop="height"               content="720">
  <meta itemprop="thumbnailUrl"         content="https://i.gyazo.com/67c56597574a341d2d686a51ad8238ed.jpg">
  <meta itemprop="uploadDate"           content="2019-02-20">
  <meta itemprop="contentUrl"           content="https://youtube.googleapis.com/v/1KNkEAh9AK4">
  <meta itemprop="embedUrl"             content="https://www.youtube.com/embed/1KNkEAh9AK4?rel=0">
  <meta itemprop="name"                 content="未踏ジュニアとは？">
  <meta itemprop="description"          content="未踏関係者に『なんで未踏?』という質問をしてみました。未踏について一歩深く知るキッカケになれば嬉しいです。">
  <iframe width="100%" src="https://www.youtube.com/embed/playlist?list=PLNObH2jlC6leiUTypiJYO2zUcwBg7M0Bg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
</div>

<a href="https://www.youtube.com/playlist?list=PLNObH2jlC6leiUTypiJYO2zUcwBg7M0Bg&disable_polymer=true" class="button">YouTubeで視聴する</a>

<br>

### 他の支援プログラム紹介 {#opportunities}
『未踏ジュニア』は 17 歳以下を対象として支援しておりますが、24 歳以下を対象とした『未踏事業』や、**年齢制限の無い**『未踏アドバンスト』『未踏ターゲット』など、あなたの作りたいもの（[提案書](/download)）を支援してくれるプログラムがあります。コチラもぜひ！

<a href="/opportunities" class="button">他の支援プログラムを見る</a>

<div class="tips">17 歳以下のクリエータが、24 歳以下を対象とした『未踏事業』に採択された例もあります。また未踏事業への応募資料（提案書）を、未踏ジュニアにそのまま再利用することも可能です。</div>

<br>
