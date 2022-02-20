## Introduction

This repository contains personal adblock lists that I use in uBlock Origin.

If you're interested in using them, you can click on the following links and import them in uBO.

- Search Engine Cleaner [![uBO - add this filter](https://img.shields.io/static/v1?label=uBO&message=add%20this%20filter&color=de3f32&style=flat&logo=uBlock%20Origin)](https%3A%2F%2Fsubscribe.adblockplus.org%2F%3Flocation%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fayushnix%2Fadblock%2Fmaster%2Ffilters%2Fsearch.txt%26title%3DAyushNix+Search+Cleaner+List)

- Annoyances [![uBO - add this filter](https://img.shields.io/static/v1?label=uBO&message=add%20this%20filter&color=de3f32&style=flat&logo=uBlock%20Origin)](https%3A%2F%2Fsubscribe.adblockplus.org%2F%3Flocation%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fayushnix%2Fadblock%2Fmaster%2Ffilters%2Fannoyances.txt%26title%3DAyushNix+Annoyances+List)

- YouTube Cleaner [![uBO - add this filter](https://img.shields.io/static/v1?label=uBO&message=add%20this%20filter&color=de3f32&style=flat&logo=uBlock%20Origin)](https%3A%2F%2Fsubscribe.adblockplus.org%2F%3Flocation%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fayushnix%2Fadblock%2Fmaster%2Ffilters%2Fyoutube.txt%26title%3DAyushNix+YouTube+Cleaner+List)

- YouTube Channel [BlockList](https://raw.githubusercontent.com/ayushnix/adblock/master/filters/blocktube.txt) for [BlockTube](https://addons.mozilla.org/en-US/firefox/addon/blocktube/)

## Scope

### Search Engine Cleaner

The Search Engine Cleaner List is meant to block SEO spam on search engines and other useless
websites that are a waste of network bandwidth and resources. Unlike
[this](https://github.com/quenhus/uBlock-Origin-dev-filter) repository, I don't intend to provide a
segregated and granular list. Why? Because I don't think that bullshit domains blocked by this list
belong anywhere on the Internet. If it should be blocked on Google, it should also be blocked on
other search engines. This might've not been the case if Google was still the definitive source of
information but at this point, no search engine can claim that. Sometimes, I end up using more than
5 or 6 search engines to find worthy search results.

The list of search engines I'm covering in this list are

- Google
- DuckDuckGo
- DuckDuckGo HTML
- DuckDuckGo Lite
- Brave
- Ecosia
- Startpage
- MillionShort
- Yandex
- Bing

I'm open to covering more search engines.

If I block a domain, it'll be blocked from all of these search engines. I'll also be pretty liberal
when it comes to blocking domains. This means that even if bullshit exists on a specific subdomain
or a specific directory of an apex domain, the apex domain will be blocked.

Needless to say, this aggressive approach may end up creating false positives but at this point, I
don't really care. If you are using this repository, feel free to raise an issue to discuss the
removal of a specific website if you believe it is genuine and provides something useful.

A list of URLs which I've added myself and which weren't blocked in the upstream sources during the
time when the commit was made are present in
[this](https://github.com/ayushnix/adblock/tree/master/urls) folder.

### Annoyances List

The Annoyances List is meant to remove spam elements from web pages that either serve as a
distraction or a waste of screen real estate.

### YouTube Cleaner List

The YouTube Cleaner List hides most YouTube elements that are unnecessary and add no value to the
already bloated web page.

In addition, I've also added a channel list that I've blocked using
[BlockTube](https://addons.mozilla.org/en-US/firefox/addon/blocktube/). This list is fairly
aggressive and if I see YouTube faces on thumbnails, bullshit that I don't like such as doom porn,
superstition, extremist politics, misleading clickbait, I'll block that channel.

It's important to note that the last time I did something like this, blocking channels or people or
topics, was on Quora almost a decade ago and now, Quora is one of the domains in urls/misc.txt.
