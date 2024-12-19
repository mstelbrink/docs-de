---
layout: home

title: Vite
titleTemplate: Frontend-Tooling der nächsten Generation

hero:
  name: Vite
  text: Frontend-Tooling der nächsten Generation
  tagline: Machen Sie sich bereit für eine Entwicklungsumgebung, die endlich mit Ihnen Schritt halten kann.
  image:
    src: /logo-with-shadow.png
    alt: Vite
  actions:
    - theme: brand
      text: Erste Schritte
      link: /guide/
    - theme: alt
      text: Wieso Vite?
      link: /guide/why
    - theme: alt
      text: Auf GitHub anzeigen
      link: https://github.com/vitejs/vite
    - theme: brand
      text: ⚡ ViteConf 24!
      link: https://viteconf.org/?utm=vite-homepage

features:
  - icon: 💡
    title: Sofortiger Server-Start
    details: Dateien werden bei Bedarf über natives ESM bereitgestellt - kein Bundling erforderlich!
  - icon: ⚡️
    title: Blitzschnelles HMR
    details: Hot Module Replacement (HMR), das unabhängig von der Größe der Anwendung schnell bleibt.
  - icon: 🛠️
    title: Reich an Funktionen
    details: Sofort verfügbare Unterstützung für TypeScript, JSX, CSS und mehr.
  - icon: 📦
    title: Optimierter Build-Prozess
    details: Vorkonfigurierter Rollup-Build mit Unterstützung für Mehrseiten- und Bibliotheksmodus.
  - icon: 🔩
    title: Universelle Plugin-Schnittstelle
    details: Rollup-Superset-Plugin-Schnittstelle, die von dev und build gemeinsam genutzt wird.
  - icon: 🔑
    title: Vollständig typisierte APIs
    details: Flexible programmatische APIs mit vollständiger TypeScript-Typisierung.
---

<script setup>
import { onMounted } from 'vue'

onMounted(() => {
  const urlParams = new URLSearchParams(window.location.search)
  if (urlParams.get('uwu') != null) {
    const img = document.querySelector('.VPHero .VPImage.image-src')
    img.src = '/logo-uwu.png'
    img.alt = 'Vite Kawaii Logo by @icarusgkx'
  }
})
</script>
