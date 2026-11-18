---
theme: default
title: 誰在聽？誰在彈？——畫中「聽琴」的兩種傳統
author: "HUMA 1660 策展小組"
fonts:
  sans: 'Noto Sans TC'
  serif: 'Noto Serif TC'
  weights: '400,500,700'
class: text-left
highlighter: shiki
drawings:
  persist: false
transition: fade
mdc: false
---

<style>
/* 黑白灰水墨極簡視覺設定 */
.slidev-layout {
  background-color: #f9f8f6 !important; /* 宣紙米白底色，護眼且襯托古畫 */
  color: #1f1f1f !important;            /* 水墨炭黑文字，確保高對比易讀 */
  font-family: 'Noto Serif TC', serif;
}
h1, h2, h3 {
  color: #111111 !important;
  font-weight: 700 !important;
  letter-spacing: 0.04em;
}
p, li {
  color: #2b2b2b !important;
  line-height: 1.85 !important;
  font-size: 0.95rem;
}
.meta-box {
  border-left: 3px solid #595959;
  padding-left: 12px;
  color: #4a4a4a;
  font-size: 0.85rem;
  line-height: 1.6;
}
.divider-line {
  border-top: 1px solid #d4d4d4;
  margin: 16px 0;
}
/* 強制保留畫作原始比例與色彩，絕不裁切變形 */
.artwork-img {
  max-height: 440px;
  width: auto;
  max-width: 100%;
  object-fit: contain;
  display: block;
  margin: 0 auto;
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.08);
}
</style>

<!-- ==================== 第 1 頁：展覽首頁 ==================== -->
<div class="h-full flex flex-col justify-center px-8">
  <p class="text-sm tracking-widest text-neutral-500 mb-3">HUMA 1660 中國藝術導論 · 線上專題展覽</p>
  <h1 class="text-4xl mb-4 leading-snug">誰在聽？誰在彈？<br/>——畫中「聽琴」的兩種傳統</h1>
  <div class="w-16 h-0.5 bg-neutral-800 my-6"></div>
  <p class="text-base text-neutral-600 mb-8">從廟堂政治修辭到閨閣私密觀看</p>
  
  <div class="text-sm text-neutral-600">
    <p><strong>策展團隊：</strong>組員一姓名、組員二姓名、組員三姓名、組員四姓名</p>
    <p class="text-xs text-neutral-400 mt-2">瀏覽提示：使用鍵盤方向鍵 ← → 或向下滾動切換展廳頁面</p>
  </div>
</div>

---
layout: default
---

<!-- ==================== 第 2 頁：展覽導言 ==================== -->
<div class="px-6 py-4">
  <p class="text-xs tracking-widest text-neutral-500 mb-1">INTRODUCTION</p>
  <h2 class="text-2xl mb-4">展覽導言</h2>
  <div class="divider-line"></div>
  
  <div class="mt-6 space-y-4 text-justify">
    <p>【請在此貼上你們小組撰寫的「展覽導言」，建議字數控制在 400–450 字。】</p>
    <p>【說明本展為何不談古琴形制，而是聚焦「聽琴」場景中的政治權力、性別身份、空間安排與身體姿態對比。】</p>
  </div>
</div>

---
layout: default
---

<!-- ==================== 第 3 頁：第一單元介紹（非必須，若不設單元可整頁刪除） ==================== -->
<div class="h-full flex flex-col justify-center px-10">
  <p class="text-xs tracking-widest text-neutral-500 mb-2">UNIT 01 · 第一單元</p>
  <h2 class="text-3xl mb-6">君臣與廟堂：政治修辭下的琴聲</h2>
  <div class="w-12 h-0.5 bg-neutral-700 mb-6"></div>
  <p class="max-w-2xl text-neutral-700">
    【選填：若設置單元介紹，建議字數為 70–130 字（不計入正文總字數）。簡述本單元如何透過撫琴與聽琴的姿態建構政治秩序。】
  </p>
</div>

---
layout: split-showcase
ratio: equal
---

<!-- ==================== 展品 01（請複製此頁格式擴充至 6 或 8 件） ==================== -->
::left::

<div class="flex flex-col justify-center h-full pr-4">
  <!-- 請將圖片上傳至 public/ 資料夾，並修改下方的檔名 -->
  <img src="/01_huizong_full.jpg" alt="傳 宋徽宗 聽琴圖軸" class="artwork-img" />
  <p class="text-xs text-neutral-500 text-center mt-3">
    圖1：傳 宋徽宗《聽琴圖》軸（全圖）｜圖片來源：北京故宮博物院
  </p>
</div>

::right::

<div class="flex flex-col justify-center h-full pl-4">
  <p class="text-xs tracking-widest text-neutral-500">EXHIBIT 01</p>
  <h3 class="text-xl mb-2">傳 宋徽宗《聽琴圖》軸</h3>
  
  <div class="meta-box mb-4">
    作者：傳 趙佶（宋徽宗，1082–1135）<br/>
    年代：北宋｜媒材：絹本設色<br/>
    尺寸：縱 147.2 厘米，橫 51.3 厘米<br/>
    收藏：北京故宮博物院
  </div>

  <div class="text-sm text-justify space-y-3 overflow-y-auto max-h-80 pr-2">
    <p>【請在此貼上你們撰寫的展品介紹正文，每件建議 400–500 字。】</p>
    <p>【引導觀眾觀察畫面中央撫琴者與兩側聽者的位置、服飾與神態，分析其中的君臣秩序與文人認同。】</p>
  </div>
</div>

---
layout: split-showcase
ratio: equal
---

<!-- ==================== 展品 01 局部特寫（選填：若某件作品需要展示細節放大圖，可使用此頁） ==================== -->
::left::

<div class="flex flex-col justify-center h-full pr-4">
  <img src="/01_huizong_detail.jpg" alt="傳 宋徽宗 聽琴圖軸 局部" class="artwork-img" />
  <p class="text-xs text-neutral-500 text-center mt-3">
    圖1-1：傳 宋徽宗《聽琴圖》軸（<strong>局部</strong>：撫琴者與聽者神態）
  </p>
</div>

::right::

<div class="flex flex-col justify-center h-full pl-4">
  <p class="text-xs tracking-widest text-neutral-500">DETAIL VIEW · 作品細部</p>
  <h3 class="text-xl mb-3">局部觀察：眼神與身體朝向</h3>
  <div class="divider-line"></div>
  <p class="text-sm text-justify mt-4">
    【請在此填寫簡短的細部補充說明（不計入正文總字數），引導觀眾注意局部視覺特徵。注意：裁切圖片必須明確標示為「局部」。】
  </p>
</div>

---
layout: split-showcase
ratio: equal
---

<!-- ==================== 展品 02 ==================== -->
::left::

<div class="flex flex-col justify-center h-full pr-4">
  <img src="/02_chenhongshou_full.jpg" alt="明 陳洪綬 聽琴圖軸" class="artwork-img" />
  <p class="text-xs text-neutral-500 text-center mt-3">
    圖2：明 陳洪綬《聽琴圖》軸（全圖）｜圖片來源：北京故宮博物院
  </p>
</div>

::right::

<div class="flex flex-col justify-center h-full pl-4">
  <p class="text-xs tracking-widest text-neutral-500">EXHIBIT 02</p>
  <h3 class="text-xl mb-2">明 陳洪綬《聽琴圖》軸</h3>
  
  <div class="meta-box mb-4">
    作者：陳洪綬（1598–1652）<br/>
    年代：明代｜媒材：絹本設色<br/>
    尺寸：縱 115.6 厘米，橫 42.3 厘米<br/>
    收藏：北京故宮博物院
  </div>

  <div class="text-sm text-justify space-y-3 overflow-y-auto max-h-80 pr-2">
    <p>【請在此貼上你們撰寫的展品介紹正文，每件建議 400–500 字。】</p>
    <p>【對比撫琴女子與侍女、側耳傾聽男子的空間距離與身體語言，探討畫面如何轉向閨閣情趣與私密聽覺。】</p>
  </div>
</div>

---
layout: default
---

<!-- ==================== 展覽結語 ==================== -->
<div class="px-6 py-4">
  <p class="text-xs tracking-widest text-neutral-500 mb-1">CONCLUSION</p>
  <h2 class="text-2xl mb-4">結語</h2>
  <div class="divider-line"></div>
  
  <div class="mt-6 space-y-4 text-justify">
    <p>【請在此貼上你們小組撰寫的「結語」，建議字數控制在 200–300 字。】</p>
    <p>【總結「聽琴」母題在不同時代的視覺演變，回應展覽開頭提出的核心問題。】</p>
  </div>
</div>

---
layout: default
---

<!-- ==================== 參考文獻與策展團隊分工 ==================== -->
<div class="px-6 py-2">
  <h2 class="text-xl mb-3">參考文獻與圖片來源</h2>
  <ul class="text-xs space-y-1.5 text-neutral-600 mb-6 list-disc pl-5">
    <li>【請列出參考書目、學術文章及各博物館官方藏品頁面網址，格式須與 Word 文檔一致】</li>
    <li>北京故宮博物院數字文物庫：https://digicol.dpm.org.cn/</li>
  </ul>

  <div class="divider-line"></div>

  <h2 class="text-xl mb-3 mt-4">策展團隊與分工</h2>
  <ul class="text-xs space-y-1.5 text-neutral-700 list-disc pl-5">
    <li><strong>組員一姓名：</strong>展覽主題構思、導言與結語撰寫</li>
    <li><strong>組員二姓名：</strong>展品 01–02 文字撰寫與文獻核實</li>
    <li><strong>組員三姓名：</strong>展品 03–04 文字撰寫與圖像細節整理</li>
    <li><strong>組員四姓名：</strong>全稿文字統整、Word 文檔排版與展覽網頁製作</li>
  </ul>
  <p class="text-xs text-neutral-400 mt-4">（註：依作業規定，網頁僅公開組員姓名與分工，學號僅列於提交之 Word 文檔中。）</p>
</div>
