<script setup lang="ts">
const nextPage = (): void => {
    navigateTo("/installMetamask")
}
</script>
<template>
    <div>WEB3.0 Engineering Journey</div>
    <div>WEB3.0 Engineering Journey（WEB3.０エンジニアリングの旅）へようこそ！</div>
    <div>
        このWebサイトは「エンジニアリングの目線からWEB3.0の世界を体験してみる」ことをコンセプトとしています。
        <br>
        当サイトのコンテンツをひととおり体験していただくと、WEB3.0の初歩的な中身を把握することができるはずです。
        <br>
        WEB3.0、ブロックチェーン、NFT・・・言葉としては知っているけど、何だかよく分からない、という方も多いはずです。
        <br>
        そんな方に、是非一度実際に触って体験していただくたい、そんな思いでこのサイトを立ち上げました。
        <br>
        海を見たことがない人には、千回言って聞かせるよりも、まず海に連れていき、入ってもらえば一発です。
        <br>
        当サイトでは、EthereumやPolygonなどのメインネットではなく、テストネットと呼ばれるブロックチェーンのテスト環境を使用するため、
        実際に口座を開いて暗号資産を用意する必要はありません。
        <br>
        それでは、Nextを押してWEB3.0の小旅行へと出発しましょう！
    </div>
    
    <CompoGoBack @click="nextPage"/>
</template>