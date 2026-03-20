---
layout: index
title: ホーム
permalink: /
subtitle: 東京都立大学　理学部　生命科学科<br>東京都立大学大学院　理学研究科　生命科学専攻

profile:
  <p align: center>
    <img src= /image/prof_pic.jpg width="600">
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>〒192-0397</p>
    <p>東京都八王子市南大沢1-1</p>
    <p>東京都立大学　南大沢キャンパス　9号館514,515号室</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

Recent publications:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div class="slideshow">
  <img class="slide" src="/images/img1.jpg">
  <img class="slide" src="/images/img2.jpg">
  <img class="slide" src="/images/img3.jpg">
</div>

<script>
let slideIndex = 0;
showSlides();

function showSlides() {
  let slides = document.getElementsByClassName("slide");
  for (let i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}
  slides[slideIndex-1].style.display = "block";
  setTimeout(showSlides, 3000); // 3秒ごと
}
</script>

<style>
.slideshow {
  text-align: center;
}
.slide {
  width: 70%;
  display: none;
}
</style>


Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](https://www.reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them.
