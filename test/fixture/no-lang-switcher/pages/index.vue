<template>
  <div>
    <div id="current-page">page: {{ $t('home') }}</div>
    <a id="link-about" :href="localePath('about')">{{ $t('about') }}</a>
    <div id="current-locale">locale: {{ $i18n.locale }}</div>
  </div>
</template>
