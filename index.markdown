---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout:
---

<html lang="en">
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- Begin Jekyll SEO tag v2.8.0 -->
  <title>Just Making Kool Renders</title>
  <meta name="generator" content="Jekyll v3.10.0" />
  <meta property="og:title" content="Just Making Kool Renders" />
  <meta property="og:locale" content="en_US" />
  <link rel="canonical" href="http://localhost:4000/" />
  <meta property="og:url" content="http://localhost:4000/" />
  <meta property="og:site_name" content="Just Making Kool Renders" />
  <meta property="og:type" content="website" />
  <meta name="twitter:card" content="summary" />
  <meta property="twitter:title" content="Just Making Kool Renders" />
  <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "WebSite",
      "headline": "Just Making Kool Renders",
      "name": "Just Making Kool Renders",
      "url": "http://localhost:4000/"
    }
  </script>
  <!-- End Jekyll SEO tag -->

  <link rel="stylesheet" href="/main.css">
  <link type="application/atom+xml" rel="alternate" href="http://localhost:4000/feed.xml" title="Just Making Kool Renders" />
</head>

<body>
  <header class="site-header" role="banner">
    <div class="wrapper">
      <a class="site-title" rel="author" href="/">Just Making Kool Renders</a>
      <nav class="site-nav">
        <div style="margin: 15px 0 0 0" class="trigger">
          <a class="page-link" href="/about/">About Us</a>
        </div>
      </nav>
    </div>
  </header>

  <main class="page-content" aria-label="Content">
    <img style="width: 525; height: 400; display: block; margin: auto;" src="game_title_screen.png"/>
    <iframe width="560" height="315" style="display: block; margin: auto;" src="https://youtube.com/embed/OtlVA214Uug" title="YouTube video player"   frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    <div style="display: flex; flex-direction: column; justify-self: center; align-items: center; color: rgb(89, 160, 222); width: 600px">
      <!--Intro-->
      <h1 style="margin: 30px 0 0 0;">What is Belonging?</h1>
      <p style="margin: 20px 0 0 0">
        Everyone has the urge to belong somewhere. Abraham Maslow, an American psychologist, proposed a theory known as Maslow’s Hierarchy of Needs. According to this theory, humans have five levels of needs, and the need for belonging is one of them.
        Our game, Belonging, is a story-driven experience that focuses on this fundamental human need, making it deeply relatable for many. You play as the last survivor of your hometown, following a compelling storyline as you search for a new place to belong. 
      </p>
      <p style="margin: 10px 0 0 0; align-self: flex-start">But even after everything, you’ll find yourself asking:</p> 
      <p style="margin: 10px 0 0 0; font-style: italic; align-self: flex-start;">Do I really belong here?</p>
      <img style="margin: 10px 0 0 0" src="you_dont_belong.png" />
      <h2 style="margin: 30px 0 0 0;">Story</h2>
      <p style="margin: 20px 0 0 0;">
        You will come across a mysterious scythe that leads you to the Darkins—the beings responsible for the tragedy that destroyed your hometown. On your journey for vengeance, you discover a new town that is also under threat from the Darkins. As someone who has already suffered their destruction, you are determined to prevent the same fate from befalling this town. Will you succeed in stopping the Darkins from destroying the new town—and the rest of the world?
      </p>
      <div style="margin: 20px 0 0 0;">
        <img style="width: 60px; height: auto;" src="player.gif">
        <img style="margin: 0 0 0 30px; width: 125px; height: auto; float: right;" src="scythe.png"/>
      </div>
      <h2 style="margin: 30px 0 0 0;">Unique Gameplay</h2>
      <p style="margin: 20px 0 0 0">
        <i>Belonging</i> combines top-down exploration with 2D platformer. You’ll navigate the story through a top-down map, solving puzzles that unlock side-scrolling battle stages. In these 2D platformer sections, you’ll fight the Darkins—creatures bent on annihilating all existence. The blend of top-down gameplay, puzzles, and 2D platformer offers a fresh and engaging experience.
      </p>
      <img style="margin: 20px 0 0 0" src="boss1.png" />
      <img style="margin: 10px 0 0 0" src="boss2.png" />
      <h3 style="margin: 10px 0 0 0">Boss battles against the Darkins</h3>
      <img style="margin: 20px 0 0 0" src="puzzle1.png" />
      <img style="margin: 10px 0 0 0" src="puzzle2.png" />
      <h3 style="margin: 10px 0 0 0">Top-down puzzles</h3>
      <!--Next Steps-->
      <h1 style="margin: 50px 0 0 0;">So... what's next?</h1>
      <p style="margin: 20px 0 0 0">
        Our game is far from finished. There are still many features we’d like to add — including new weapons with special attacks, new mechanics, more bosses, a greater variety of basic enemies, and much more. But before that, there are a few aspects we’d like to refine.
      </p>
      <h2 style="margin: 30px 0 0 0;">Known bugs: </h2>
      <ul style="align-self: flex-start">
        <li style="margin: 20px 0 0 0">
          The animation for player attacks will occasionally cancel during movement, preventing the attack from dealing damage.
        </li>
        <li>
          Occasional mismatch between the final boss' current state and animation (e.g. may attack while walking or after the attack should've taken place)
        </li>
        <li>
          Some flying enemies don't have a (clear?) hitbox and/or may appear to have more health than it should
        </li>
        <li>
          Wall jumping is apparently a thing! (due to logic found in our code)
        </li>
      </ul>
      <h2 style="margin: 30px 0 0 0;">Needed improvements for the game: </h2>
      <ul style="align-self: flex-start">
        <li style="margin: 20px 0 0 0">
          The basic enemies that are scattered across the platformer levels are too easy and bland. We would like to give them unique attacks and an incentive to kill them, such as item drops.
        </li>
        <li>
          As part of our original plan, we want the player to gain access to multiple weapons, each unlocked by defeating a boss. These weapons will not only vary between ranged and melee types, but each will also feature a unique special ability — adding depth and excitement to combat.
        </li>
        <li>
          While our game is supposed to be story-based, many of these story elements aren't present in the current version of the game. To solve this issue, we plan on adding more cutscene events, similar to the opening cutscene at the beginning of the game. Some likely places where these events may take place are before, during, and after boss fights. 
        </li>
      </ul>
    </div>
  </main>

<!--
  <footer class="site-footer h-card">
    <data class="u-url" href="/"></data>
    <div class="wrapper">
      <h2 class="footer-heading">Just Making Kool Renders</h2>
      <div class="footer-col-wrapper">
        <div class="footer-col footer-col-1">
          <ul class="contact-list">
            <li class="p-name">Just Making Kool Renders</li>
          </ul>
        </div>
        <div class="footer-col footer-col-2">
          <ul class="social-media-list"></ul>
        </div>
        <div class="footer-col footer-col-3">
          <p></p>
        </div>
      </div>
    </div>
  </footer>
  -->
</body>
</html>