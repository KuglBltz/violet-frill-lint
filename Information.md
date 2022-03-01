# This is Information to help you when making an HTML Page

- In order for stuff to show when you share a page or just have it in a tab, you need to have `this` in the <head></head> part of the HTML section

```fs
<title>Kugel's Realm</title>
    <!-- The Favicon of the Site -->
    <link rel="icon" href="https://cdn.glitch.global/c2c85d3a-6365-4497-bf85-2622f8d3112e/Favicon.png?v=1646154464584" />

    <!-- Meta tags for SEO and social sharing -->
    <link rel="canonical" href="https://glitch-hello-website.glitch.me/" />
    <meta name="description" content="Its my website, DUH." />
    <meta name="robots" content="index,follow" />
    <meta property="og:title" content="KugelBlitz's References." />
    <meta property="og:type" content="article" />
    <meta property="og:url" content="https://glitch-hello-website.glitch.me/" />
    <meta property="og:description" content="Its my website, DUH." />
    <meta
      property="og:image"
      content="https://cdn.glitch.com/605e2a51-d45f-4d87-a285-9410ad350515%2Fhello-website-social.png?v=1616712748147"
    />
    <meta name="twitter:card" content="summary" />

    <!-- Import the webpage's stylesheet -->
    <link rel="stylesheet" href="/style.css" />

    <!-- Import the webpage's javascript file -->
    <script src="/script.js" defer></script>
```

- Making `hyperlink` buttons is hard, this code should help out with that

```fs
<a class="btn--remix" target="_top" href="https://www.google.com">Dont click this button!</a>
```
- Although this is just a hyperlink you can make actual buttons with 
```fs
<button href="https://www.google.com">wow</button>
```