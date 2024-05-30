<template>
  <div>
    <div>
      <button class="w-10 h-10 border border-black rounded-full" @click="setLocale('en')">en</button>
      <button class="w-10 h-10 border border-black rounded-full ml-2" @click="setLocale('zh-tw')">tw</button>
      <p>{{ $t('home') }}</p>
      <p>{{ locale }}</p>
      <p>{{ test }}</p>
    </div>
  </div>
</template>

<script setup>
const { locale, setLocale } = useI18n()
</script>

<script>
export default {
  data() { 
    return {
      test:'aaa',
    }
  },
}
</script>