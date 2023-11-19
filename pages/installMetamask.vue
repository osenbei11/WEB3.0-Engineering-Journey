<script setup lang="ts">
const nextPage = (): void => {
    // navigateTo("/installMetamask")
}

const goToMetamask = (): void  => {
    const url: string = 'https://metamask.io/';
    window.open(url, '_blank');
}
</script>
<template>
    <div>WEB3.0 Engineering Journey</div>
    <div>Install MetaMask</div>
    <CompoInstallMetamask @click="goToMetamask" />

    <button @click="nextPage" class="relative inline-block px-4 py-1.5 font-medium group">
        <span class="absolute inset-0 w-full h-full bg-white border-2 border-black group-hover:bg-black"></span>
        <span class="relative text-black group-hover:text-white">Next</span>
    </button>
</template>