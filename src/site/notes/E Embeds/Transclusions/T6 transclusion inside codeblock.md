---
{"dg-publish":true,"permalink":"/e-embeds/transclusions/t6-transclusion-inside-codeblock/","created":"2024-05-07T10:12:25.000-05:00","updated":"2024-05-07T10:12:25.000-05:00"}
---

#known-issue [Issue](https://github.com/oleeskild/obsidian-digital-garden/issues/113)

Transclusions inside code blocks should not show transcluded content, but the literal text inside. Currently it transcludes the content

`
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/005-custom-filters/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">






this plugin has custom filter that turns ❄️ (snow emoji) into 🌞 (THE SUN). When published, this file should have a lot of sun-emojis. 


❄️❄️❄️❄️❄️❄️❄️❄️❄️❄️❄️❄️❄️


</div></div>
`

```

<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/005-custom-filters/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">






this plugin has custom filter that turns ❄️ (snow emoji) into 🌞 (THE SUN). When published, this file should have a lot of sun-emojis. 


❄️❄️❄️❄️❄️❄️❄️❄️❄️❄️❄️❄️❄️


</div></div>

```