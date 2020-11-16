<template>
  <div>
    <Header></Header>
    <div class="container mt-3">
      <Card v-for="url in urls" :url="url" :key="url"></Card>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
export default Vue.extend({
  data() {
    return {
      urls: [
        "https://www.dezeen.com/2020/10/26/airbnb-jony-ive-lovefrom/",
        "https://www.amazon.co.jp/%E3%80%8C%E3%83%A6%E3%83%BC%E3%82%B6%E3%83%BC%E3%83%95%E3%83%AC%E3%83%B3%E3%83%89%E3%83%AA%E3%83%BC%E3%80%8D%E5%85%A8%E5%8F%B2-%E4%B8%96%E7%95%8C%E3%81%A8%E4%BA%BA%E9%96%93%E3%82%92%E5%A4%89%E3%81%88%E3%81%A6%E3%81%8D%E3%81%9F%E3%80%8C%E4%BD%BF%E3%81%84%E3%82%84%E3%81%99%E3%81%84%E3%83%A2%E3%83%8E%E3%80%8D%E3%81%AE%E6%B3%95%E5%89%87-%E3%82%AF%E3%83%AA%E3%83%95%E3%83%BB%E3%82%AF%E3%82%A2%E3%83%B3/dp/457531577X",
        "https://zenn.dev/yusugomori/articles/a3d5dc8baf9e386a58e5",
        "https://engineering.mercari.com/en/blog/entry/20201105-python-and-type-hinting-on-the-backend/",
        "https://review.foundx.jp/entry/how-to-spin-your-scientific-research-out-of-a-university-and-into-a-startup",
        "https://dailyportalz.jp/kiji/explanations-of-the_African_proverb",
        "https://slidelive.jp/slide/17587a5b794144c01ca?event_id=17587594e811561d51",
        "https://news.livedoor.com/article/detail/19168642/",
        "https://www.senryaku.metro.tokyo.lg.jp/saiyou/202011_002.html",
        "http://qrais.blog.jp/archives/7743063.html",
        "https://changelog.com/podcast/418",
        "https://www.growthunt.com/",
        "https://coralcap.co/2020/10/app-clips-and-miniapps/",
        "https://www.notion.so/Cocoda-2020-10-a2e7407b192a46eb9b9d3b8f3d102ee6#ee9da00330ba476792b6e4dc71efde37",
        "https://meety.net/articles/t1--c_oh-s2z4",
        "https://www.udemy.com/course/python-algo/?couponCode=80515F7DEDBC4776BF87",
        "https://xtech.nikkei.com/atcl/nxt/column/18/01450/102300001/",
        "https://review.foundx.jp/entry/on-starting-and-scaling-intercom",
        "https://zenn.dev/tetsukick/articles/c297b6ee1e64397432e5",
        "https://dailyportalz.jp/kiji/Tetsu_and_Tomo-quiz",
        "https://review.foundx.jp/entry/work-at-a-startup",
        "https://dailyportalz.jp/kiji/mystery-of-Mc",
        "https://www.mmhmm.app/jp/blog/welcome-memix/",
        "https://about.gitlab.com/handbook/business-ops/tech-stack/",
        "https://zenn.dev/hyuki/books/techask-patterns",
        "https://sauna-ikitai.stores.jp/",
        "https://www.unqork.com/",
        "https://note.com/t_1496/n/na13468468d7d",
        "https://cloud.google.com/blog/ja/products/media-entertainment/helping-media-companies-navigate-the-new-streaming-normal",
        "https://speakerdeck.com/yuzutas0/20190213",
        "https://speakerdeck.com/mnc/improve-product-development?slide=20",
        "https://gist.github.com/voluntas/08671d717290a6f63cddd95052a33a86",
        "https://www.youtube.com/watch?v=HDFdZJD0ZvY",
        "https://www.hanmoto.com/bd/isbn/9784802511773",
        "https://note.com/chijintianxia/n/n11f3e6ec9e22",
        "https://blog.pyq.jp/entry/pyq_development_story_201020",
        "https://www.slideshare.net/i2key/45-developers-summit-2015-devsumi-devsumib",
        "https://www.slideshare.net/recruitcojp/devops-51085988",
        "https://speakerdeck.com/rtechkouhou/enziniadakedeqi-hua-kai-fa-fen-xi-subetewosui-xing-surutimuwoli-tishang-getahua",
        "https://note.com/hrsw0512/n/n65c98588773c",
        "https://craftbeer-tokyo.info/event/takao-202010/",
        "https://zenn.dev/seuyu_bin/articles/709ad8e90be73f9d9a3c",
        "https://coralcap.co/2020/10/3-takeaways-from-netflix-founders-new-book/",
        "https://review.foundx.jp/entry/8d-how-to-build-a-great-series-a-pitch-and-deck",
        "https://www.ted.com/talks/alain_de_botton_a_kinder_gentler_philosophy_of_success?utm_campaign=tedspread&utm_medium=referral&utm_source=tedcomshare",
        "https://review.foundx.jp/entry/doing-old-things-better-vs-doing-brand-new-things",
        "https://www.shoeisha.co.jp/book/detail/9784798169774?fbclid=IwAR2CRv9WDaKZhM7zTTVt1HCGc5eq0bs7RxTZoFAWTV4TGFriqoOZjkmsUUQ",
        "https://www.nikkei.com/article/DGKKZO65142950X11C20A0EA2000/",
        "https://zenn.dev/takahito0508/articles/einstein-ocr-intro",
        "https://strainer.jp/notes/1881",
      ],
    };
  },
});
</script>

<style>
</style>
