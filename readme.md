# awesome-i18n [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of i18n tools, i18n libraries, localization software, localization programs and translation management systems.


## 📦 Contents

- [👩‍🎓 Acronims and keywords](#acronims-and-keywords)
- [🕵️ SEO i18n](#%EF%B8%8F-seo-i18n)
- [📚 Libraries](#-libraries)
- [👩‍💻  Tools & Services](#-tools-and-services)
- [📅 Dates & Times](#-dates-and-times)
- [📞 Telephone](#telephone)
- [📒 Blog posts & articles](#-blog-posts-articles--others)
- [Translation agencies](#Translation agencies)

## 👩‍🎓 Acronims and keywords

### 🧐 Acronims
* i18n - internationalization
* l10n - localization
* xl8 - group of [translation management systems](#translation-management-system)
* t9n - translation
* g11n - globalization
* m17n - multilingualization
* ICU - International Components for Unicode
* TMS - translation management system
* GMS - globalization translation system (same thing as TMS)

### 🔑 Keywords
* translation key - element in source code which is used by i18n library to replace it with translation message
* translation - translated text or message


## 🕵️ SEO i18n 

* [What is 'hreflang'](https://simplelocalize.io/blog/posts/what-is-hreflang/)


## 📚 Libraries

### JavaScript & Frameworks

* [ECMAScript Internationalization API](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl) documentation what standard `intl` object in JS can do.
* [Globalize](https://github.com/jquery/globalize) library for i18n that leverages the official Unicode CLDR JSON data
* [Intl.js](https://github.com/andyearnshaw/Intl.js) implementation of the ECMAScript Internationalization API
* [Jed](http://slexaxton.github.io/Jed/) Gettext Style i18n
* [FormatJS](https://formatjs.io) internationalize your web apps on the client & server
* [googlei18n/libphonenumber](https://github.com/googlei18n/libphonenumber) Google's common Java, C++ and JavaScript library for parsing, formatting, and validating international phone numbers
* [International Telephone Input](http://jackocnr.com/intl-tel-input.html) plugin for entering and validating international telephone numbers. 
* [lisan.js](http://lisanjs.com) fast and small i18n library
* [Polyglot.js](http://airbnb.io/polyglot.js/) Make your application speak multiple languages
* [i18next](http://i18next.com/) i18next is a full-featured i18n javascript library for translating your web application
- [react-i18next](https://react.i18next.com/) - internationalization framework for React / React Native which is based on i18next
* [c-3po.js](http://c-3po.js.org) library for translations based on ES6 template literals
- [i18n Ally](https://github.com/antfu/i18n-ally) - Extension for VSCode, all in one about i18n.
* [Angular NGX Translate](http://www.ngx-translate.com) Angular translation library
- [npm i18n](https://www.npmjs.com/package/i18n) - Lightweight simple translation module with dynamic json storage.
* [bloodyowl/react-translate](https://github.com/bloodyowl/react-translate) Internationalization for react
* [vue i18n](https://kazupon.github.io/vue-i18n/) Vue I18n is internationalization plugin for Vue.js
- [MDN i18n](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/i18n) - Functions to internationalize your browser extension. You can use these APIs to get localized strings from locale files packaged with your extension.
- [Quasar I18n](https://quasar.dev/options/app-internationalization) - App internationalization (i18n) in Quasar framework.


### Java

* [Thymeleaf](https://www.thymeleaf.org) - modern server-side Java template engine for both web and standalone environments.
* [Spring Messages](https://www.baeldung.com/spring-boot-internationalization) Spring Boot internationalization. LocaleResolver & LocaleChangeInterceptor example usage. 
* [Thymeleaf i18n docs](https://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html#using-texts) using `th:texts` for translations
* [Spring Boot localization](https://www.baeldung.com/spring-boot-internationalization) Baeldun post about using Spring Messages
* [i18n in Spring Boot](https://stackoverflow.com/questions/36531131/i18n-in-spring-boot-thymeleaf) Stackoverflow thread


### Jekyll

* [jekyll-multiple-languages-plugin](https://github.com/kurtsson/jekyll-multiple-languages-plugin) Jekyll Multiple Languages is an internationalization plugin for Jekyll.
* [jekyll-i18n](https://github.com/liamzebedee/jekyll-i18n) Jekyll i18n is a plugin that enables simplistic multi-language site designs using Jekyll. (not maintained)

### Swift (iOS & macOS)

- [SwiftGoogleTranslate](https://github.com/maximbilan/SwiftGoogleTranslate) - A framework to use cloud translation API by Google in Swift.

### Ruby

* [TwitterCLDR](https://github.com/twitter/twitter-cldr-rb) implementation of the ICU that uses the Common Locale Data Repository to format dates, plurals
- [Ruby I18n](https://guides.rubyonrails.org/i18n.html) - Rails internationalization (i18n) API.

### Python

- [Python-i18n](https://pypi.org/project/python-i18n/) - Python internationalization (i18n) package.
- [deep-translator](https://github.com/nidhaloff/deep-translator) - A flexible free and unlimited (depending on the translator used) library written in Python to translate between different languages in a simple way using multiple translators, it can also be used directly in the prompt.

## 👩‍💻 Tools and services

### 🤖 Localization CLI Tools


### ☁️ Translation Management Systems

* [memsource](https://www.memsource.com)
* [localizejs](https://localizejs.com)
- [LocaleApp](https://www.localeapp.com/) - App localization and translation.
* [simplelocalize](https://simplelocalize.io)
- [Crowdin](https://crowdin.com/) - Closed source cloud-based localization service
- [GitLocalize](https://gitlocalize.com/) - Localization platform that syncs with your GitHub repository (sold to alconst)
- [Transifex](https://www.transifex.com/) - Web-based translation platform, globalization management system.
- [Weblate](https://weblate.org/) - Platform for one of the most positive and empowering communities of libre software.
- [Zanata](http://zanata.org/) - Web translation platform for translators and developers to manage localisations.
- [Traduora](https://github.com/traduora/traduora) - A platform for manage translations.

### 🖥 Desktop apps
* [GNU gettext](http://www.gnu.org/software/gettext/) tool for adding native language support to applications
- [RTranslator](https://github.com/niedev/RTranslator) - simultaneous translator app for Android based on Google's API.
- [Crow Translate](https://github.com/crow-translate/crow-translate) - A simple and lightweight desktop translator. Allows to translate and speak text using Google, Yandex and Bing translate API.
- [Copy Translator](https://github.com/CopyTranslator/CopyTranslator) - Cross-platform app that automatically translate texts when copied in the clipboard
- [Electronjs i18n](https://www.electronjs.org/apps/i18n-manager) - Cross-platform i18n manager
- [OmegaT](https://omegat.org/) - Free translation memory application that works on Windows, macOS and Linux
- [Argos Translate](https://github.com/argosopentech/argos-translate) - Open source offline translation app based on OpenNMT
- [LibreTranslate](https://github.com/uav4geo/LibreTranslate) - self-hosted web application to translate texts


## 📅 Dates and Times

* [MomentJS] JavaScript library for handling times and dates. (outdated)
* [Luxon](https://moment.github.io/luxon/) A powerful, modern, and friendly wrapper for Javascript dates and times
* [Daylight saving time and time zone best practices](http://stackoverflow.com/questions/2532729/daylight-saving-time-and-time-zone-best-practices)

## 📞 Telephone

* [E.123: Notation for national and international telephone numbers, e-mail addresses and web addresses](http://www.itu.int/rec/T-REC-E.123/en)
* [ITU-T E.164 Assigned Country Codes](http://www.itu.int/dms_pub/itu-t/opb/sp/T-SP-E.164D-11-2011-PDF-E.pdf)
* [International Telephone Input](http://jackocnr.com/intl-tel-input.html)
* [Random Phone Number Generator](https://fakenumber.org/) Only for a few countries

## 📒 Blog posts, articles & others

* [What is 'hreflang' attribute](https://simplelocalize.io/blog/posts/what-is-hreflang/)
- [Stack Overflow Q&A-1](https://stackoverflow.com/questions/506743/localization-and-internationalization-whats-the-difference) - Localization and internationalization, what's the difference?


## 🦮 Guides
- [Angular and i18n](https://angular.io/guide/i18n) - Angular i18n guide.
- [Message extraction](https://simplelocalize.io/docs/cli/i18n-keys-extraction/) Extracting translation keys from project files. JavaScript, Android, iOS/macOS

## ✍️ Translation agencies

[✌️Add your agency](https://github.com/jpomykala/awesome-i18n/issues/new)

## 🦾 Automated translations

* [Gengo](http://gengo.com) Translation is made by real people but you can make an order using API
* [Google Translate](https://translate.google.com)
* [Microsoft Translator](https://www.microsoft.com/en-GB/translator/)
* [DeepL](https://deepl.com)

## 📘 Documetations

* [The Unicode Consortium](http://unicode.org/)
* [Common Language Data Repository](http://cldr.unicode.org/) The Unicode CLDR provides key building blocks for software to support the world's languages, with the largest and most extensive standard repository of locale data available.
* [ICU: International Components for Unicode](http://site.icu-project.org/) ICU is a mature, widely used set of C/C++ and Java libraries providing Unicode and Globalization support for software applications.
* [Google Developers: Internationalization](https://developers.google.com/international/)
* [W3C Internationalization overview](http://www.w3.org/standards/webdesign/i18n)
* [W3C Internationalization Activity homepage](http://www.w3.org/International/)

## 📢 Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
