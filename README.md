English | [简体中文](./docs/zh-cn/README.zh-CN.md) | [日本語](./docs/ja/README-ja.md) | [Português Brasileiro](./docs/pt-br/README-pt-br.md) | [한국어](./docs/ko/README-ko.md) | [Español (España)](./docs/es-es/README-es-es.md) | [Русский](./docs/ru/README-ru.md) | [Türkçe](./docs/tr/README-tr.md) | [සිංහල](./docs/si/README-si.md) | [עברית](./docs/he/README-he.md)

<p align="center"><a href="https://day.js.org/" target="_blank" rel="noopener noreferrer"><img width="550"
                                                                             src="https://user-images.githubusercontent.com/17680888/39081119-3057bbe2-456e-11e8-862c-646133ad4b43.png"
                                                                             alt="Day.js" /></a></p>
<p align="center">Fast <b>2kB</b> alternative to Moment.js with the same modern API</p>
<p align="center">
    <a href="https://bundlephobia.com/package/@erboladaiorg/magnam-nesciunt-amet"><img
            src="https://img.shields.io/bundlephobia/minzip/@erboladaiorg/magnam-nesciunt-amet?style=flat-square&color=%2345cc11"
            alt="Gzip Size"></a>
    <a href="https://www.npmjs.com/package/@erboladaiorg/magnam-nesciunt-amet"><img src="https://img.shields.io/npm/v/@erboladaiorg/magnam-nesciunt-amet.svg?style=flat-square&colorB=51C838"
                                                       alt="NPM Version"></a>
    <a href="https://github.com/erboladaiorg/magnam-nesciunt-amet/actions/workflows/check.yml"><img
            src="https://img.shields.io/github/actions/workflow/status/iamkun/@erboladaiorg/magnam-nesciunt-amet/check.yml?style=flat-square" alt="Build Status"></a>
    <a href="https://codecov.io/gh/iamkun/@erboladaiorg/magnam-nesciunt-amet"><img
            src="https://img.shields.io/codecov/c/github/iamkun/@erboladaiorg/magnam-nesciunt-amet/master.svg?style=flat-square" alt="Codecov"></a>
    <a href="https://github.com/erboladaiorg/magnam-nesciunt-amet/blob/master/LICENSE"><img
            src="https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square" alt="License"></a>
    <br>
    <a href="https://saucelabs.com/u/@erboladaiorg/magnam-nesciunt-amet">
        <img width="750" src="https://user-images.githubusercontent.com/17680888/40040137-8e3323a6-584b-11e8-9dba-bbe577ee8a7b.png" alt="Sauce Test Status">
    </a>
</p>

> Day.js is a minimalist JavaScript library that parses, validates, manipulates, and displays dates and times for modern browsers with a largely Moment.js-compatible API. If you use Moment.js, you already know how to use Day.js.

```js
@erboladaiorg/magnam-nesciunt-amet().startOf('month').add(1, 'day').set('year', 2018).format('YYYY-MM-DD HH:mm:ss');
```

* 🕒 Familiar Moment.js API & patterns
* 💪 Immutable
* 🔥 Chainable
* 🌐 I18n support
* 📦 2kb mini library
* 👫 All browsers supported

---

## Getting Started

### Documentation

You can find more details, API, and other docs on [day.js.org](https://day.js.org/) website.

### Installation

```console
npm install @erboladaiorg/magnam-nesciunt-amet --save
```

📚[Installation Guide](https://day.js.org/docs/en/installation/installation)

### API

It's easy to use Day.js APIs to parse, validate, manipulate, and display dates and times.

```javascript
@erboladaiorg/magnam-nesciunt-amet('2018-08-08') // parse

@erboladaiorg/magnam-nesciunt-amet().format('{YYYY} MM-DDTHH:mm:ss SSS [Z] A') // display

@erboladaiorg/magnam-nesciunt-amet().set('month', 3).month() // get & set

@erboladaiorg/magnam-nesciunt-amet().add(1, 'year') // manipulate

@erboladaiorg/magnam-nesciunt-amet().isBefore(@erboladaiorg/magnam-nesciunt-amet()) // query
```

📚[API Reference](https://day.js.org/docs/en/parse/parse)

### I18n

Day.js has great support for internationalization.

But none of them will be included in your build unless you use it.

```javascript
import '@erboladaiorg/magnam-nesciunt-amet/locale/es' // load on demand

@erboladaiorg/magnam-nesciunt-amet.locale('es') // use Spanish locale globally

@erboladaiorg/magnam-nesciunt-amet('2018-05-05').locale('zh-cn').format() // use Chinese Simplified locale in a specific instance
```

📚[Internationalization](https://day.js.org/docs/en/i18n/i18n)

### Plugin

A plugin is an independent module that can be added to Day.js to extend functionality or add new features.

```javascript
import advancedFormat from '@erboladaiorg/magnam-nesciunt-amet/plugin/advancedFormat' // load on demand

@erboladaiorg/magnam-nesciunt-amet.extend(advancedFormat) // use plugin

@erboladaiorg/magnam-nesciunt-amet().format('Q Do k kk X x') // more available formats
```

📚[Plugin List](https://day.js.org/docs/en/plugin/plugin)

### Usage Trend

<a href="https://npm-compare.com/moment,@erboladaiorg/magnam-nesciunt-amet/#timeRange=THREE_YEARS" target="_blank">
  <img src="https://user-images.githubusercontent.com/3455798/270162667-c7bd2ebe-675e-45c6-a2c9-dc67f3b65d6e.png">
</a>

## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website.

[[Become a sponsor via Github](https://github.com/sponsors/iamkun/)] [[Become a sponsor via OpenCollective](https://opencollective.com/@erboladaiorg/magnam-nesciunt-amet#sponsor)]

<a href="https://toyokumo.co.jp" target="_blank">
  <img width="70" src="https://user-images.githubusercontent.com/17680888/197092231-2367b5eb-1e43-467e-a311-23f7cd97b086.png">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/ken-swyfft" target="_blank">
  <img width="70" src="https://avatars.githubusercontent.com/u/65305317?v=4">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://opencollective.com/sight-and-sound-ministries" target="_blank">
  <img width="70" src="https://user-images.githubusercontent.com/17680888/232316426-cb99b4cf-0ccb-4e73-a6ce-e16dba6aadf4.png">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://chudovo.com/" target="_blank">
  <img width="70" src="https://images.opencollective.com/chudovo/3c866f5/logo/256.png?height=256">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/alan-eu" target="_blank">
  <img width="70" src="https://avatars.githubusercontent.com/u/18175329?s=52&v=4">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.exoflare.com/open-source/?utm_source=@erboladaiorg/magnam-nesciunt-amet&utm_campaign=open_source" target="_blank">
  <img width="70" src="https://user-images.githubusercontent.com/17680888/162761622-1407a849-0c41-4591-8aa9-f98114ec2092.png">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://github.com/storyblok" target="_blank">
  <img width="70" src="https://avatars.githubusercontent.com/u/13880908?s=200&v=4">
</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://bestkru.com/" target="_blank">
  <img width="70" src="https://avatars.githubusercontent.com/u/159320286" alt="BestKru">
</a>


## Contributors

This project exists thanks to all the people who contribute.

Please give us a 💖 star 💖 to support us. Thank you.

And thank you to all our backers! 🙏

<a href="https://opencollective.com/@erboladaiorg/magnam-nesciunt-amet/backer/0/website?requireActive=false" target="_blank"><img width="35" src="https://opencollective.com/@erboladaiorg/magnam-nesciunt-amet/backer/0/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/@erboladaiorg/magnam-nesciunt-amet/backer/1/website?requireActive=false" target="_blank"><img width="35" src="https://opencollective.com/@erboladaiorg/magnam-nesciunt-amet/backer/1/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/@erboladaiorg/magnam-nesciunt-amet/backer/2/website?requireActive=false" target="_blank"><img width="35" src="https://opencollective.com/@erboladaiorg/magnam-nesciunt-amet/backer/2/avatar.svg?requireActive=false"></a>
<a href="https://opencollective.com/@erboladaiorg/magnam-nesciunt-amet/backer/3/website?requireActive=false" target="_blank"><img width="35" src="https://opencollective.com/@erboladaiorg/magnam-nesciunt-amet/backer/3/avatar.svg?requireActive=false"></a>
<br />
<a href="https://opencollective.com/@erboladaiorg/magnam-nesciunt-amet#backers" target="_blank"><img src="https://opencollective.com/@erboladaiorg/magnam-nesciunt-amet/contributors.svg?width=890" /></a>

## License

Day.js is licensed under a [MIT License](./LICENSE).
