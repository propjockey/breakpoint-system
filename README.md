[![Jane Ori - PropJockey.io](https://img.shields.io/badge/Jane%20Ori%20%F0%9F%91%BD-%F0%9F%A4%8D%20PropJockey.io-7300E6.svg?labelColor=FB04C2&style=plastic)](http://jane.propjockey.io/)

# breakpoint-system from <img src="https://github.com/user-attachments/assets/87119fb5-c39d-429a-9bfd-424f0e100720" alt="" width="30px"> PropJockey
Highly accessible, responsive CSS designed in pixels and implemented 1:1 with the new Breakpoint Unit for a flawless fluid experience. Custom aliases, breakpoints, and queries with heavily researched defaults. No scripts, no builds, 100% vanilla CSS. Old tech, new ideas - 89% global user reach. Deliver your designs.

Docs+Demos at: https://propjockey.breakpoint-system.com

NPM: https://www.npmjs.com/package/@propjockey/breakpoint-system

GitHub: https://github.com/propjockey/breakpoint-system

Install:
`$ npm install @propjockey/breakpoint-system`
Then import the `/node_modules/@propjockey/breakpoint-system/breakpoint-system.css` file into your project.

OR

Use your favorite NPM CDN and include it on your page for small projects. Like so:
```html
<link rel="stylesheet" type="text/css" href="https://unpkg.com/@propjockey/breakpoint-system@1.1.1/breakpoint-system.css">
```

## 🛸🌏💚 Browser Support (~89% global reach as of April, 2026)

The limiting factor for compatibility is the [CSS round() function](https://caniuse.com/mdn-css_types_round) and [CSS nesting selector](https://caniuse.com/mdn-css_selectors_nesting).

| Browser / Platform | Minimum Version | Date Supported | Global Share |
| :--- | :--- | :--- | :--- |
| **Safari / iOS Safari** | 16.5 | May 2023 | ~17.5% |
| **Firefox** | 128 | July 2024 | ~1.75% |
| **Chrome / Chrome for Android** | 138 | Jun 2025 | ~63.5% |
| **Edge** | 138 | Jun 2025 | ~5.5% |
| **Opera** | 122 | Sep 2025 | ~0.5% |
| **Total Unflagged Support** | | | **~89%** |

---

## ✨👽🎉 The Magic

`@propjockey/breakpoint-system` is the first vanilla CSS library of its kind, with much to offer.

https://propjockey.breakpoint-system.com

### 🛠️ 100% Customizable Querying

Our defaults are excellent, your needs are specific. You are not locked into our breakpoint sizes nor names. You can, optionally, define custom identifiers, aliases, and corresponding breakpoint locations.

### 🔎 Automatic Accessibility Scaling

Ten years ago author Zell Liew wrote about [several problems with responsive design](https://zellwk.com/blog/media-query-units/). Every point has long since been fixed by browsers except, arguably, the most important one:

`px` breakpoints don't respect users who require larger base font sizes and "blows out" the expected boundaries of your design.

Browsers didn't "fix" this because it's a CSS authoring problem - yet `px` is so common, it's [almost](https://propjockey.github.io/css-media-vars/) the only unit you'll ever see in a media query.

`@propjockey/breakpoint-system` fixes this for *everyone*, automatically.

Breakpoints are specified as numeric pixel values for *ease of DX* and automatically integrated into the engine relative to the root `em` determined by the user's system settings for *ease of UX*. 👽🤌💚

Effectively, your mobile-friendly design now shows up instead of your tablet-friendly design to accomodate their larger font size preference, proportionately to the difference. It doesn't blow out your design, it just appears as if they zoomed into your mobile design in their tablet viewport without overflowing their screen.

*This is our default behavior, but it's optional.*

---

### 🌊 Fluid Design and Typography Built-In!

Deliver your designs. Perfect app-ready design and text scaling using our breakpoint units, `var(--bpu-16px)`, without ever trampling nor abusing your `rem` unit, [writing `clamp()`, or reiterating breakpoint boundaries](https://www.npmjs.com/package/fluid-text-plugin) again.

---

### 🛡️ Bulletproof and Future-Ready

Our API uses simple calc() switches, space toggles, CSS Container Style Queries, or `if(style())` conditionals - your choice!

`@propjockey/breakpoint-system` is built with the future in heart, (like [some of our](https://augmented-ui.com/) [other products](https://propjockey.github.io/css-bin-bits/) [and ideas](https://dev.to/janeori/100-css-fetch-and-exfiltrate-512-bits-of-server-generated-data-embedded-in-an-animated-svg-5aad))!

---

Deliver your designs.


## CHANGELOG:

v1.1.1 - April 23rd, 2026:
* Added over 2700 query tests to the website (stress test too) https://propjockey.breakpoint-system.com/tests.html
* Fixed browser support for FF 128 and Safari 16.5 - 18.7 thanks to a generous month of BrowserStack from [@terzic](https://github.com/terzic)
* Corrected Chrome support, CSS abs() is its limiting factor (- 0.81% reach from initial mistake)
* Updated the library's root @supports statements to perfectly align with actual support

v1.1.0 - April 22nd, 2026:
* Made class names prefix--extensible by authors.
* Added query "in" space toggle opt-in expansion.
* Fixes for a currently-undocumented feature set.

v1.0.0 - April 17th, 2026:
* Initial release


---

## Open Contact 👽

Please do reach out if you need help with any of this, have feature requests, or want to share what you've created!

| <small>PropJockey</small> | <small>CodePen</small> | <small>DEV Blog</small> | <small>GitHub</small> |
| :---: | :---: | :---: | :---: |
| [![PropJockey.io](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/external-social/100px/color-responsive/propjockey-lines.svg)](https://propjockey.io) | [![CodePen](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/external-social/100px/color-responsive/codepen.svg)](https://codepen.io/propjockey) | [![DEV Blog](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/external-social/100px/color-responsive/dev.svg)](https://dev.to/janeori) | [![GitHub](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/external-social/100px/color-responsive/github.svg)](https://github.com/propjockey) |

| <small>Mastodon</small> | <small>LinkedIn</small> | <small>X</small> | <small>Bluesky</small> |
| :---: | :---: | :---: | :---: |
| [![Mastodon](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/external-social/100px/color-responsive/mastodon.svg)](https://front-end.social/@JaneOri) | [![LinkedIn](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/external-social/100px/color-responsive/linkedin.svg)](https://www.linkedin.com/in/janeori/) | [![X](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/external-social/100px/color-responsive/x.svg)](https://x.com/jane0ri) | [![Bluesky](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/external-social/100px/color-responsive/bluesky.svg)](https://bsky.app/profile/janeori.propjockey.io) |

### My heart is open to receive abundance in all forms,<br>flowing to me in many expected and unexpected ways.

| PayPal | Ko-fi | Venmo |
| :---: | :---: | :---: |
| [![PayPal](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/QR-Codes/svg/200px/paypal.svg)](https://www.paypal.com/donate/?cmd=_s-xclick&hosted_button_id=9Z925L3SJJ8BS&source=qr&ssrt=1772865628068) | [![Ko-fi](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/QR-Codes/svg/200px/ko-fi.svg)](https://ko-fi.com/janeori) | [![Venmo](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/QR-Codes/svg/200px/venmo.svg)](https://account.venmo.com/u/JaneOri) |

| BTC | XRP | ETH |
| :---: | :---: | :---: |
| [![BTC bc1qe2ss8hvmskcxpmk046msrjpmy9qults2yusgn9](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/QR-Codes/svg/200px/btc.svg)](https://app.ens.domains/janeori.eth) | [![XRP rw2ciyaNshpHe7bCHo4bRWq6pqqynnWKQg : 459777128](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/QR-Codes/svg/200px/xrp.svg)](https://bithomp.com/en/account/X7zmKiqEhMznSXgj9cirEnD5sWo3iZPqbNPChdEKV9sM9WF) | [![ETH 0x674D4191dEBf9793e743D21a4B8c4cf1cC3beF54](https://raw.githubusercontent.com/propjockey/propjockey-brand/main/QR-Codes/svg/200px/eth.svg)](https://app.ens.domains/janeori.eth) |
| bc1qe...usgn9 | rw2ci...nWKQg<br>: 459777128 | 0x674...beF54 |
