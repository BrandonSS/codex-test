<template>
  <header class="site-header" :class="{ 'is-scrolled': isScrolled }">
    <a class="brand" href="#top" aria-label="返回首页" @click="scrollToSection">
      <span class="brand-mark">湖</span>
      <span>
        <strong>鱼形湖露营基地</strong>
      </span>
    </a>
    <nav class="nav" aria-label="页面导航">
      <a href="#experience" @click="scrollToSection">基地体验</a>
      <a href="#weekend" @click="scrollToSection">两天行程</a>
      <a href="#facilities" @click="scrollToSection">设施服务</a>
      <a href="#gallery" @click="scrollToSection">实景影像</a>
    </nav>
    <a class="header-cta" href="#contact" @click="scrollToSection">咨询周末档期</a>
  </header>

  <main id="top">
    <section class="hero" aria-label="鱼形湖畔露营基地首屏">
      <img class="hero-image" src="../素材/12-鱼型湖岛桥航拍.jpg" alt="鱼形湖泊、树林和湖岛入口的航拍景观">
      <div class="hero-overlay"></div>
      <div class="hero-content">
        <p class="eyebrow">周末两天 · 亲子家庭 · 情侣度假</p>
        <h1>鱼形湖畔的周末两天露营假期</h1>
        <p class="hero-copy">沿湖抵达，被草坪、树林和水面包围。孩子可以在沙坑和游乐区尽情玩，情侣可以去花海和滨湖咖啡吧放慢脚步，傍晚再登上山顶帐篷平台，看草坪与湖泊在脚下展开。</p>
        <div class="hero-actions">
          <a class="button primary" href="#contact" @click="scrollToSection">咨询周末档期</a>
          <a class="button secondary" href="#experience" @click="scrollToSection">查看基地亮点</a>
        </div>
      </div>
      <div class="hero-strip" aria-label="核心亮点">
        <span>鱼形湖泊实景</span>
        <span>湖畔大草坪</span>
        <span>山顶帐篷视野</span>
        <span>亲子与情侣友好</span>
      </div>
    </section>

    <section class="intro-panel" id="experience">
      <div class="intro-copy">
        <p class="eyebrow">基地体验</p>
        <h2>把一个周末，安排在湖、草地和山风之间</h2>
        <p>基地沿鱼形湖泊一侧展开，湖畔草坪适合搭建帐篷、野餐和轻运动；草坪旁的树林提供自然遮阴；儿童游乐设施、沙坑、花海坡地、主题餐厅和滨湖咖啡吧，让家庭与情侣都能找到自己的节奏。</p>
      </div>
      <div class="intro-facts" aria-label="基地体验概览">
        <article>
          <div>
            <strong>01</strong>
            <h3>湖畔草坪</h3>
            <p>帐篷、野餐、飞盘、亲子活动，一到营地就进入周末状态。</p>
          </div>
          <img src="../素材/07-湖岸草坪与游船-.png" alt="湖岸草坪、湖面和游船区域">
        </article>
        <article>
          <div>
            <strong>02</strong>
            <h3>林间休憩</h3>
            <p>树荫、湖风和慢步道，让大人小孩都有轻松的停留空间。</p>
          </div>
          <img src="../素材/09-帐篷与集装箱营房通道-草坪渲染.png" alt="林间营房通道、帐篷和休憩空间">
        </article>
        <article>
          <div>
            <strong>03</strong>
            <h3>山顶眺望</h3>
            <p>半顶帐篷平台拥有开阔视野，适合日落、清晨和合影。</p>
          </div>
          <img src="../素材/05-山顶营地区域施工与帐篷-草坪渲染.png" alt="山顶帐篷区域与开阔草坪视野">
        </article>
      </div>
    </section>

    <section class="scene-grid" aria-label="核心场景">
      <article class="scene-card large">
        <img src="../素材/14-营地草坪全景航拍-草坪渲染.png" alt="湖岛营地草坪、树林和湖泊的全景航拍效果">
        <div>
          <p class="eyebrow">湖畔草坪</p>
          <h2>湖畔大草坪，是周末的主会场</h2>
          <p>开阔草坪连接湖岸与树林，适合帐篷露营、亲子游戏、草坪餐会和傍晚聚会。孩子有地方奔跑，大人也能在湖风里放松下来。</p>
        </div>
      </article>
      <article class="scene-card">
        <img src="../素材/03-湖岸树林水景.jpg" alt="湖岸边树林、水面和草坡景观">
        <div>
          <h3>草坪旁的树林</h3>
          <p>自然树荫围合出安静边界，适合散步、乘凉和拍照。</p>
        </div>
      </article>
      <article class="scene-card">
        <img src="../assets/kids-sandpit.png" alt="湖畔露营基地内的儿童沙坑和木质游乐设施">
        <div>
          <h3>儿童游乐与沙坑</h3>
          <p>木质游乐设施和沙坑让孩子玩得投入，家长也能从容陪伴。</p>
        </div>
      </article>
    </section>

    <section class="weekend" id="weekend">
      <div class="section-heading centered">
        <p class="eyebrow">两天周末</p>
        <h2>两天一夜，不赶路，只换一种生活节奏</h2>
        <p>距离益阳市区约 30 分钟车程，周五下班后或周末上午都能轻松抵达，把更多时间留给草地、湖风和家人。</p>
      </div>
      <div class="timeline">
        <article>
          <span>第一天</span>
          <h3>抵达湖畔，把下午交给草地</h3>
          <ol>
            <li><strong>14:00</strong> 从益阳市区轻松出发，抵达基地后搭建帐篷或进入营地区域。</li>
            <li><strong>15:30</strong> 草坪轻运动、树林散步、儿童区玩沙和游乐。</li>
            <li><strong>17:30</strong> 开启湖畔自助烧烤，也可前往滨湖咖啡吧或主题餐厅，享受湖边傍晚。</li>
            <li><strong>20:00</strong> 山顶帐篷平台观景，和家人或伴侣看夜色落下。</li>
          </ol>
        </article>
        <article>
          <span>第二天</span>
          <h3>晨光、花海和轻松返程</h3>
          <ol>
            <li><strong>07:30</strong> 山顶或湖边看清晨风景，拍一组自然合影。</li>
            <li><strong>09:00</strong> 早餐后去花海坡地打卡，记录周末好天气。</li>
            <li><strong>10:30</strong> 继续草坪活动、咖啡休息或湖边漫步。</li>
            <li><strong>12:00</strong> 整理装备，乘摆渡车轻松接驳至各区域。</li>
          </ol>
        </article>
      </div>
    </section>

    <section class="feature-split">
      <div class="feature-copy">
        <p class="eyebrow">山顶视野</p>
        <h2>山顶半顶帐篷平台，俯瞰草坪与湖泊</h2>
        <p>山顶平台是基地最有记忆点的地方。半顶帐篷带来遮蔽和仪式感，向外则是湖面、草坪和树林铺开的视野，适合情侣日落、家庭合影，也适合清晨安静地喝一杯咖啡。</p>
        <div class="feature-tags">
          <span>开阔湖景</span>
          <span>日落拍照</span>
          <span>山顶帐篷体验</span>
        </div>
      </div>
      <figure>
        <img src="../素材/06-湖景玻璃观景房.jpg" alt="湖景玻璃观景空间与周边树林湖泊">
      </figure>
    </section>

    <section class="facilities" id="facilities">
      <div class="section-heading">
        <p class="eyebrow">设施服务</p>
        <h2>从玩到吃，再到接驳，都为周末停留准备好</h2>
        <p>基地不只适合搭帐篷，也适合把一天完整地留在这里：小朋友有游乐设施，情侣有咖啡和花海，家庭聚会也能安排在主题餐厅。</p>
      </div>
      <div class="facility-grid">
        <article>
          <span class="facility-icon">餐</span>
          <h3>特色主题餐厅</h3>
          <p>承接周末正餐、家庭聚会和朋友小聚，让露营不止有户外，也有舒服的用餐体验。</p>
        </article>
        <article>
          <span class="facility-icon">咖</span>
          <h3>滨湖咖啡吧</h3>
          <p>湖边下午茶、情侣约会和轻松休息点，适合在行程中留一段慢时间。</p>
        </article>
        <article>
          <span class="facility-icon">车</span>
          <h3>电动摆渡车</h3>
          <p>基地内交通更方便，草坪、餐饮、观景区之间接驳更轻松。</p>
        </article>
        <article>
          <span class="facility-icon">花</span>
          <h3>花海坡地</h3>
          <p>山坡花海适合家庭合影、情侣打卡和朋友圈出片，是行程里的轻松亮点。</p>
        </article>
      </div>
    </section>

    <section class="photo-feature">
      <figure>
        <img src="../assets/flower-hillside.png" alt="湖畔山坡花海和远处湖泊风景">
      </figure>
      <div>
        <p class="eyebrow">拍照打卡</p>
        <h2>花海、湖岸、草坪，都能拍出周末的松弛感</h2>
        <p>不需要刻意摆拍，走上花海坡地，身后是湖面和树林；回到草坪，孩子奔跑、帐篷展开、咖啡在手，都是自然的出片场景。</p>
      </div>
    </section>

    <section class="gallery" id="gallery">
      <div class="section-heading centered">
        <p class="eyebrow">实景影像</p>
        <h2>用实景影像，看见基地的尺度和氛围</h2>
      </div>
      <div class="gallery-grid">
        <figure class="gallery-main">
          <img src="../素材/16-湖岛草坪环湖航拍-草坪渲染.png" alt="环湖草坪和树林营地航拍效果">
        </figure>
        <figure>
          <img src="../素材/01-湖畔大草坪近景.jpg" alt="湖畔大草坪近景">
        </figure>
        <figure>
          <img src="../素材/13-湖岛入口与水岸航拍.jpg" alt="湖岛入口与水岸航拍">
        </figure>
        <figure>
          <img src="../素材/15-林间道路与营房航拍.jpg" alt="林间道路、营房和周边树林航拍">
        </figure>
      </div>
      <div class="video-row" aria-label="基地视频片段">
        <video src="../素材/08c50d0d5ca9e16723e152a6b2f2c3c6.mp4" poster="../素材/01-湖畔大草坪近景.jpg" controls muted preload="metadata" playsinline></video>
        <video src="../素材/20bc5bf4e9ca8eddaea94136c0202386.mp4" poster="../素材/03-湖岸树林水景.jpg" controls muted preload="metadata" playsinline></video>
      </div>
    </section>

    <section class="contact" id="contact">
      <div>
        <p class="eyebrow">周末咨询</p>
        <h2>把这个周末，留给湖边的草地和山顶的风</h2>
        <p>页面为宣传样稿，具体档期、餐饮安排、活动内容和接驳服务可按基地实际运营信息替换。当前先保留轻量咨询入口，不展示未确认的商业信息。</p>
      </div>
      <a class="button primary" href="#top" @click="scrollToSection">返回顶部查看基地</a>
    </section>
  </main>

  <footer class="site-footer">
    <p>鱼形湖露营基地 · 周末两天露营假期宣传页</p>
    <a href="#top" @click="scrollToSection">回到顶部</a>
  </footer>
</template>

<script setup>
import { onMounted, onUnmounted, ref } from "vue";

const isScrolled = ref(false);

const updateHeader = () => {
  isScrolled.value = window.scrollY > 18;
};

const scrollToSection = (event) => {
  const href = event.currentTarget.getAttribute("href");
  const target = href ? document.querySelector(href) : null;

  if (!target) {
    return;
  }

  event.preventDefault();
  target.scrollIntoView({ behavior: "smooth", block: "start" });
};

const pauseOtherVideos = (event) => {
  document.querySelectorAll("video").forEach((video) => {
    if (video !== event.currentTarget) {
      video.pause();
    }
  });
};

onMounted(() => {
  updateHeader();
  window.addEventListener("scroll", updateHeader, { passive: true });
  document.querySelectorAll("video").forEach((video) => {
    video.addEventListener("play", pauseOtherVideos);
  });
});

onUnmounted(() => {
  window.removeEventListener("scroll", updateHeader);
  document.querySelectorAll("video").forEach((video) => {
    video.removeEventListener("play", pauseOtherVideos);
  });
});
</script>
