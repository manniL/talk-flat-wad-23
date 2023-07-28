---
theme: ./theme
title: "From clicks to cribs - How to find your dream home with web scraping"
website: https://lichter.io
handle: TheAlexLichter
favicon: https://raw.githubusercontent.com/manniL/static/main/logo-lightbulb-white-red.svg
highlighter: shiki
lineNumbers: true
transition: fade
---
---

<img class="h-105 mx-auto" src="https://images.unsplash.com/photo-1600725935160-f67ee4f6084a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1920&q=80" alt="Moving boxes">

<!--

Who of you ever moved into a different flat or house? 
* Envy the rest of you -> avoid lots of hassle
* But also not envy you -> new home => more fulfillment, joy, ...

* In a bigger city, e.g. Berlin or Amsterdam, this can be a real challenge
-->

---

<img class="h-100 mx-auto" src="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2370&q=80
" alt="Modern house from outside">

---

<img class="mx-auto" src="https://i.imgur.com/vfNNnjm.png" alt="Rental offer for a tent on a balcony in Berlin">

<!--

* Searching a flat is cumbersome, takes lots of time and also nerves :D
* So... guess what I was up to the last half year :D
-->

---

<div class="h-100">
<img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExcXQ0MzZjaDZyMWh2ZDA3Mm5idThmNTF6OHp6NmMzODN1cDRna3oyYyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/LP8dSox43RFPmhvZTZ/giphy.gif" width="480" height="270" class="mx-auto" />
<img v-click src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExNXlzYWhzdWI0ajJjbXZ5eTc1eWsycm16anEzaTRpdXFib21qeWp1cyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/W4VzWcWKlT0xfPF964/giphy.gif" width="480" height="351" class="mx-auto" />
</div>

---
layout: intro
---

# From <span class="text-orange-400">clicks</span> to <span class="text-orange-400">cribs</span>

## How to find your dream home with <span class="text-orange-400">web scraping</span>

### WeAreDeveloper World Congress 2023

<style>
  h1 {
    @apply !text-5xl;
  }

  h2 {
    @apply !text-3xl !mt-16 !mb-32;
  }

  h3 {
    @apply !text-base;
  }
</style>

---
layout: two-cols
heading: About me
---

<template v-slot:default>
<div class="flex flex-col justify-center items-center h-full">
<img
  class="w-75 rounded-full"
  src="https://lichter.io/img/me@2x.webp"
  />
  <h2 class="mt-4">Alexander Lichter</h2>
</div>
</template>

<template v-slot:right>
<VClicks class="space-y-2 mt-10 text-xl h-full">

* <mdi-account-check class="text-green-100" /> **Web Development Consultant**
* <mdi-microphone /> Speaker & Instructor
* <logos-nuxt-icon /> Nuxt.js Team
* <mdi-twitter class="text-blue-400" /> @TheAlexLichter
* <mdi-web /> [https://lichter.io](https://lichter.io)
* <mdi-github /> [manniL](https://github.com/manniL)

</VClicks>
</template>

---
layout: intro
---

# How to find a new home?

<VClicks class="list-none!">

* You consult online portals
* Not just one, but many...
* **Lots of**

</VClicks>

---

<div class="ml-16">
  <img class="absolute h-100" src="/sites/01.jpg">
  <img class="absolute ml-8 rotate-10 h-100" v-click src="/sites/02.jpg">
  <img class="absolute ml-12 -rotate-10 h-100" v-click src="/sites/03.jpg">
  <img class="absolute ml-12 rotate-25 h-100" v-click src="/sites/04.jpg">
  <img class="absolute ml-4 -rotate-30 h-100" v-click src="/sites/05.jpg">
</div>

---

<div class="flex justify-around items-center">

<img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExbmtuMnRybzdha2Ruc200NWd0anF2ZndrejljZ2pkd2p0bnd0M2NqYiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/vyVxeMNGUBT7q/giphy.gif" />

<video style="width: 500px; height: 281px;" src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExeTY4OXdkaGk3eWRnYnFmcXJyY3lpbndtaWJiMnpvaHVrcGM3N2o1NiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/tei52cyY5mroA/giphy.mp4" poster="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExeTY4OXdkaGk3eWRnYnFmcXJyY3lpbndtaWJiMnpvaHVrcGM3N2o1NiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/tei52cyY5mroA/giphy_s.gif" autoplay="" loop="" playsinline=""></video>

</div>

<!--

* You want to answer to all ads matching your criteria
* As soon as possible, because speed matters

-->

---
layout: intro
---

# Not feasible!

<VClick>

## Automate it instead?

</VClick>

---

<img class="h-100 mx-auto" src="https://imgs.xkcd.com/comics/is_it_worth_the_time_2x.png" />

---

<div class="w-full h-full flex justify-center items-center">
  <h1 class="text-green-500 font-bold"><heroicons-check class="h-32 w-32" /></h1>
</div>

---
layout: intro
---

# But how?

---
layout: intro
---

# <span class="text-orange-400">Web Scraping</span>!

<VClick>

## Fetching websites and extracting information out of them

</VClick>

---

# Web Scraping

<VClicks>

* is language-independent
* can be (mostly) automated
* helps collecting a big amount of data in short time
* can be done in various ways

</VClicks>

---

# Understanding how a website is built

<VClicks depth="2">

* We have to differ between SPAs and non-SPAs when doing web scraping
* To do that, we can check the browser devtools!
* When navigating around the page...
    * ...either a full HTML document will be loaded
    * ...or JS is loaded + APIs are called

</VClicks>

<img v-click src="/xhr-api.jpg" alt="Devtools showing an API Request">

---

# Scraping SPAs

<VClicks>

* If the site to scrape is an API, you already have to data you need in JSON format (usually)
* You can replicate the API calls that the website is doing and play around with the query params

</VClicks>

<img class="mx-auto h-80" v-click src="/xhr-result.jpg" alt="Result of the search API">

---

# Scraping non-SPAs

<VClicks>

* But what if the target site is no SPA?
* Well, it is a bit more effort but still doable!
* We will have to fetch the HTML document (fetch API) and parse it

</VClicks>

<img class="mt-8" v-click src="/no-spa.jpg" alt="" />

---

# How to parse HTML?

<VClicks>

* Regex!

</VClicks>

---

# How to parse HTML?

* ~~Regex~~ No! (see [this SO post](https://stackoverflow.com/questions/1732348/regex-match-open-tags-except-xhtml-self-contained-tags))

<VClicks>

* Use a HTML/XML parser library
* e.g. BeautifulSoup (Python) or Cheerio (JavaScript)

</VClicks>

---
layout: two-cols
heading: Example
---

<template v-slot:default>
  <img src="/devtools-check-structure-1.jpg">
</template>

<template v-slot:right>

<Code v-click>

```js
document.querySelectorAll('.object')

/*
Array(5) [ 
  div.object.object-status-verhuurd-onder-voorbehoud.object-price-.mb-4, 
  div.object.object-status-verhuurd.object-price-.mb-4,
  div.object.object-status-verhuurd.object-price-.mb-4,
  div.object.object-status-verhuurd.object-price-.mb-4,
  div.object.object-status-verhuurd.object-price-.mb-4
]
*/
```

</Code>

</template>

---

# Take a look at the HTML of a single entry

<Code v-click class="h-90 overflow-scroll w-full" file="single-entry.html">

```html
<div class="object object-status-beschikbaar object-price- mb-4">
    <div class="row">
        <div class="col-12 col-md-5">
            <div class="object-image position-relative mb-3">
                <a href="https://www.example.nl/woningen/overtoom-252-a-amsterdam/" class="position-relative text-decoration-none d-block">
                    <div class="object-image-img">
                    <!-- ... -->
                    </div>
                </a>
                <div class="object-favorite object-favorite-add position-absolute" data-favorite-id="564">
                    <svg class="position-absolute" viewBox="0 -28 512.001 512" xmlns="http://www.w3.org/2000/svg"><!-- ... --></svg>
                </div>
            </div>
        </div>
        <div class="col-12 col-md-7">
            <div class="object-info">
                <div class="object-address mb-3">
                    <div class="object-address-line">
                        <span class="object-street">Overtoom</span>
                        <span class="object-housenumber">252</span>
                        <span class="object-housenumber-addition">a</span>
                    </div>
                    <div class="object-address-line">
                        <span class="object-place">Amsterdam</span>
                    </div>
                </div>
                <div class="object-price mb-3 object-price-status-beschikbaar">
                    <div class="object-price-sale">
                        <span class="object-price-kind-of">
                            Huurprijs
                        </span>
                        <span class="object-price-value">
                            € 1.500
                        </span>
                        <span class="object-price-type">
                            ,- per maand
                        </span>
                    </div>
                </div>
                <div class="object-features mb-3">
                    <div class="object-feature object-feature-woonoppervlakte">
                        <div class="row">
                            <div class="col-5">
                                <div class="object-feature-title text-truncate">
                                    Woonopp.
                                </div>
                            </div>
                            <div class="col-7">
                                <div class="object-feature-info text-truncate">
                                    95 m²
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="object-feature object-feature-aantalkamers">
                        <div class="row">
                            <div class="col-5">
                                <div class="object-feature-title text-truncate">
                                    Aantal kamers
                                </div>
                            </div>
                            <div class="col-7">
                                <div class="object-feature-info text-truncate">
                                    3 kamers
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="object-description mb-3">
                    <p>
                        Algemeen: Een prachtig, ruim en licht 3-kamerappartement van bijna 95 m² (94,7 m²) groot op de eerste verdieping en het uitsluitend gebruiksrecht van de ruime tuin van maar liefst 77 m² en een terras van 13 m². Het
                        appartement verkeert in een uitstekende staat van onderhoud en is op loopafstand…
                    </p>
                </div>
                <div class="object-view mb-3">
                    <a href="https://www.example.nl/woningen/overtoom-252-a-amsterdam-9374326a183ead5fba4d599d5b716c326e6c12/" class="position-relative p-3 text-decoration-none d-table"> Bekijk object </a>
                </div>
            </div>
        </div>
    </div>
</div>
```

</Code>

---

# Identify the important parts

<Code v-click="1" class="h-90 overflow-scroll w-full" file="single-entry.html">

```html{all|all|5,9|5,9,16-18|5,9,16-18,21|5,9,16-18,21,29-31|5,9,16-18,21,29-31,46-48|5,9,16-18,21,29-31,46-48,60-62}
<div class="object object-status-beschikbaar object-price- mb-4">
    <div class="row">
        <div class="col-12 col-md-5">
            <div class="object-image position-relative mb-3">
                <a href="https://www.example.nl/woningen/overtoom-252-a-amsterdam/" class="position-relative text-decoration-none d-block">
                    <div class="object-image-img">
                    <!-- ... -->
                    </div>
                </a>
            </div>
        </div>
        <div class="col-12 col-md-7">
            <div class="object-info">
                <div class="object-address mb-3">
                    <div class="object-address-line">
                        <span class="object-street">Overtoom</span>
                        <span class="object-housenumber">252</span>
                        <span class="object-housenumber-addition">a</span>
                    </div>
                    <div class="object-address-line">
                        <span class="object-place">Amsterdam</span>
                    </div>
                </div>
                <div class="object-price mb-3 object-price-status-beschikbaar">
                    <div class="object-price-sale">
                        <span class="object-price-kind-of">
                            Huurprijs
                        </span>
                        <span class="object-price-value">
                            € 1.500
                        </span>
                        <span class="object-price-type">
                            ,- per maand
                        </span>
                    </div>
                </div>
                <div class="object-features mb-3">
                    <div class="object-feature object-feature-woonoppervlakte">
                        <div class="row">
                            <div class="col-5">
                                <div class="object-feature-title text-truncate">
                                    Woonopp.
                                </div>
                            </div>
                            <div class="col-7">
                                <div class="object-feature-info text-truncate">
                                    95 m²
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="object-feature object-feature-aantalkamers">
                        <div class="row">
                            <div class="col-5">
                                <div class="object-feature-title text-truncate">
                                    Aantal kamers
                                </div>
                            </div>
                            <div class="col-7">
                                <div class="object-feature-info text-truncate">
                                    3 kamers
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="object-description mb-3">
                    <p>
                        Algemeen: Een prachtig, ruim en licht 3-kamerappartement van bijna 95 m² (94,7 m²) groot op de eerste verdieping en het uitsluitend gebruiksrecht van de ruime tuin van maar liefst 77 m² en een terras van 13 m². Het
                        appartement verkeert in een uitstekende staat van onderhoud en is op loopafstand…
                    </p>
                </div>
                <div class="object-view mb-3">
                    <a href="https://www.example.nl/woningen/overtoom-252-a-amsterdam-9374326a183ead5fba4d599d5b716c326e6c12/" class="position-relative p-3 text-decoration-none d-table"> Bekijk object </a>
                </div>
            </div>
        </div>
    </div>
</div>
```

</Code>

---

# Write a test!

```ts
import { load } from "cheerio";

export function parse () { /* TODO */ }

if (import.meta.vitest) {
	const { it, expect } = import.meta.vitest

  it('works', () => {
    const HTML = `HTML_FROM_BEFORE`

    const expected = {
      address: "Overtoom 252 a",
      area: 95,
      link: "https://www.example.nl/woningen/overtoom-252-a-amsterdam-9374326a183ead5fba4d599d5b716c326e6c12/",
      price: 1500,
      region: "Amsterdam",
      rooms: 3,
    }

    expect(parse(load(HTML).root())).toStrictEqual(expected)
  })
}
```

---

# Parse the HTML!

```ts{1|2-6|8-14|15-17|19|all}
function parse (result: Cheerio<any>): Flat | null {
	const status = result.find('.object-status').text().trim()

	if (status && status !== 'nieuw') {
		return null
	}

	const $link = result.find('.object-image > a')

	if (!$link.length) {
		return null
	}

	const link = $link.attr('href') ?? ''
	const street = result.find('.object-street').text().trim()
	const number = result.find('.object-housenumber').text().trim()
	const address = `${street} ${number}`.trim()
  /*  ...  */
	return { link, address, region, price, area, rooms }
}
```

---

# Fetch the results and pass them to parse

```ts
import { $fetch } from "ofetch";
import { DEFAULT_HEADERS } from "../constants.js";
import { load } from "cheerio";
import { Flat } from "../types.js";

export async function scrapeExampleSite (): Promise<Flat[]> {
	const result = await $fetch('https://www.example.nl/huurwoningen/?_prijs_van_huur=1000-9999999&_prijs_tot_huur=1-2000&_per_page=100', {
		headers: DEFAULT_HEADERS
	})
	const $ = load(result)

	return $('.object')
    .toArray()
    .map((result) => parse($(result)))
    .filter((c): c is Flat => Boolean(c))
}
```

---

# Done?

---

# More automation

<VClicks>

* Write a parser for all sites you want to check
* But that's not it!
* Saving the results somewhere
* Scheduling recurring fetches
* Notifying via push when a new flat is up

</VClicks>

---

# Database & Diffing

<VClicks>

* Can be anything you like, from Mongo over MySQL
* I used [LowDB](https://github.com/typicode/lowdb/) for simplicity
* Two options of storing data:
* 1) Crawl all sites and save "the diff" (keep the same, remove old, add new)
* 2) Crawl all sites and add continuously to the database
* I used 1) for simplicity again, but 2) is favorable when data amount increases

</VClicks>

---

# Notifications

<Grid>

<VClicks>

* Multiple options here: Discord/Slack/...
* I chose Telegram because the setup was easy & quick
* With the `telegraf` package, it is hassle free to listen to commands & send messages
* `/start` -> write user in DB for notification, `/stop` to remove
* Commands for "edge cases"

</VClicks>

<div>
  <img v-click class="h-100 mx-auto" src="/telegram.jpg">
</div>
</Grid>

---

# Scheduling

<VClicks>

* To schedule, I used the `node-cron` package to run my scrape job every X minutes
* Which means: Scrape all sites, then alert all users (usually just me)

</VClicks>

<Code v-click>

```ts
export async function initJobs(bot: Telegraf) {
  const check = async () => {
    const db = await createDatabaseHandler()
    const newFlats = await checkAllFlats(db)
    const users = db.getUsers()
    textUsers(bot, newFlats, users)
  }
  check()
  cron.schedule('*/3 * * * *', check)
}
```

</Code>

---

# Edge Cases

<VClicks>

* Most of these sites had no sophisticated protection against scraping
* But what if...?

</VClicks>

<img v-click src="/crawl-protection.png" class="h-80 mx-auto">

---

# Edge Case: Login

<VClicks>

* If possible - create a throwaway account and save the cookie information for login
* Might have to be refreshed (though this could be automated too)

</VClicks>

---

# Edge Case: Captcha

<VClicks>

* Depends on the captcha type
* More sophisticated captchas can be solved with third party services
* Others -> same as "verification layer" 

</VClicks>

<img v-click class="mx-auto h-80" src="/captcha.jpg">

---

# Edge Case: Verification Layer

<VClicks>

* Verification layers are used to check if you use a "real browser"
* As we don't (only a fetch request), we can't see the content we want to scrape
* As these layers need to execute JavaScript, a simple `fetch` call is not enough
* We need to use a headless browser like Puppeteer or Playwright!
* Idea: "Mimic" actual browser behavior
* But even with that, sometimes you need to verify manually

</VClicks>

---

# "Simple captcha" with Puppeteer

<VClicks depth="2">

* If one the site is unsure if you are a bot or not, a captcha will be presented
* This can be solved half-automated (with AI probably fully)
* Process
    * Open site via headless browser (Puppeteer/Playwright)
    * Check if verification is needed
    * If yes, send a screenshot of the site
    * Wait for user input 
    * Click the right image
    * Save the cookies

</VClicks>

---
layout: intro
---

# The Result

---
layout: image
image: ./finally-the-flat.jpg
preload: false
---

<div class="flex justify-between"> 
<Confetti :duration="3000" :particleCount="180" :force="1" />
<Confetti :duration="3500" :particleCount="200" :force="1" />
</div>
---

# Conclusion

<VClicks>

* Web Scraping can help automating things (to some degree)
* This works for flats, but also various other things!
* To get started, `fetch` + cheerio is more than enough
* Finding a flat is not easy, but worth it!

</VClicks>

---

# Thanks a lot to my sponsors!
<img src="https://raw.githubusercontent.com/manniL/static/main/sponsors.svg" class="h-80 mx-auto" alt="My GitHub sponsors">

---
layout: two-cols
heading: Thank you for your attention!
---

<template v-slot:default>
<div class="flex flex-col justify-center items-center h-full">
<img
  class="w-75 rounded-full"
  src="https://lichter.io/img/me@2x.webp"
  />
  <h2 class="mt-4">Alexander Lichter</h2>
</div>
</template>

<template v-slot:right>

* <mdi-account-check class="text-green-100" /> **Web Development Consultant**
* <mdi-microphone /> Speaker & Instructor
* <logos-nuxt-icon /> Nuxt.js Team
* <mdi-twitter class="text-blue-400" /> @TheAlexLichter
* <mdi-web /> [https://lichter.io](https://lichter.io)
* <mdi-github /> [manniL](https://github.com/manniL)

</template>

<style>
  ul {
    @apply space-y-2 mt-10 text-xl h-full;
  }
</style>

---
layout: intro
hideLogoInCorner: true
---

# Slides / Repo

* [https://lichter.link/flat-wad-23/](https://lichter.link/flat-wad-23/)

<img class="w-32 h-32 mt-16 mx-auto" src="https://raw.githubusercontent.com/manniL/static/main/logo-lightbulb-white-red.svg" />

<style>
  ul {
    @apply list-none!;
  }
</style>