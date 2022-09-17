<template>
    <section id="section-03" class="business-type max-width-1280">
        <div class="section-title">
            <h2>事業内容</h2>
        </div>
        <div class="business-type-container">
            <div class="business-type-text">
                <h3 class="business-type-name color-white">コンサルティング事業</h3>
                <p class="business-type-description color-white">各分野のトップコンサルタントがお客様の悩み発見から解決まで伴走型で承ります。</p>
                <li class="business-type-li color-white">新規事業コンサルティング</li>
                <li class="business-type-li color-white">戦略コンサルティング</li>
                <li class="business-type-li color-white">ブランドコンサルティング</li>
                <li class="business-type-li color-white">マーケティングコンサルティング</li>
                <li class="business-type-li color-white">業務改善コンサルティング</li>
                <li class="business-type-li color-white">ＧＸコンサルティング</li>
            </div>
            <div class="business-type-img">
                <img src="../assets/img/コンサルティング事業.png" alt="コンサル事業">
            </div>
        </div>
        <div class="business-type-container">
            <div class="business-type-text">
                <h3 class="business-type-name color-white">リスクマネジメント事業</h3>
                <p class="business-type-description color-white">昨今、環境問題や自然災害、経済安全保障等、企業を取り巻く環境はより一層厳しくなりました。当社ではそのようなお客様をサポートするために会社全体から部門単位での支援を行っております。</p>
                <li class="business-type-li color-white">全社的リスクマネジメント（ERM）</li>
                <li class="business-type-li color-white">事業継続計画（BCP）</li>
                <li class="business-type-li color-white">サイバーセキュリティ</li>
                <li class="business-type-li color-white">ESG/CSR</li>
                <li class="business-type-li color-white">経済安全保障</li>
            </div>
            <div class="business-type-img">
                <img src="../assets/img/リスクマネジメント事業.png" alt="コンサル事業">
            </div>
        </div>
        <div class="business-type-container">
            <div class="business-type-text">
                <h3 class="business-type-name color-white">教育事業</h3>
                <p class="business-type-description color-white">国際情勢・外交・安全保障の勉強やニュース、セミナー等の情報をWebサイト内にてワンストップで確認できるオンライン学習プラットフォーム「OASIS」を運営しております。</p>
                <li class="business-type-li color-white">国際情勢、外交、安全保障を学ぶオンラインプラットフォーム「OASIS」</li>
            </div>
            <div class="business-type-img">
                <img src="../assets/img/教育事業.png" alt="コンサル事業">
            </div>
        </div>
        <a />
    </section>
</template>
<script>
import a from '../components/imageTextArea.vue';

</script>
<style>
    .business-type-container {
        display: flex;
        align-items: center;
        position: relative;
        justify-content: center;
        margin: 40px 0;
    }
    .business-type-text {
        position: absolute;
        width: 60%;
        padding: 0 2rem;
    }
    .business-type-name {
        font-size: 32px;
        line-height: 32px;
        margin: 1rem 0;
        font-weight: bold;
    }
    .business-type-description {
        line-height: 2;
        margin: .5rem;
    }
    .business-type-li {
        line-height: 2;
    }
    .color-white {
        color: white!important;
    }
    .business-type-img {
        width: 60%;
        display: block;
        margin: 0 auto;
    }
</style>