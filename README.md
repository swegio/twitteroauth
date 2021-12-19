<p align="center">
	<img src="https://raw.githubusercontent.com/abraham/twitteroauth-com/main/src/images/twitter-logo-blue.png" itemprop="image" alt="Twitter bird" width="200px">
</p>
<p>
Sweg-<span itemprop="name">TwitterOAuth</span>
</p>

[![Build Status](https://github.com/abraham/twitteroauth/workflows/Test/badge.svg)](https://github.com/abraham/twitteroauth/actions) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/abraham/twitteroauth/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/abraham/twitteroauth/?branch=master) [![Issues Count](https://img.shields.io/github/issues/abraham/twitteroauth.svg)](https://github.com/abraham/twitteroauth/issues) [![Latest Version](https://img.shields.io/packagist/v/abraham/twitteroauth.svg)](https://packagist.org/packages/swegio/twitteroauth) [![Downloads this Month](https://img.shields.io/packagist/dm/abraham/twitteroauth.svg)](https://packagist.org/packages/swegio/twitteroauth)

---

<p itemprop="description">The most popular forked-PHP library for Twitter's OAuth REST API.</p>

## Installation

- Composer

```console
composer require swegio/twitteroauth
```

- npm

```console
npm i sweg-twitteroauth
```

## Quick-Start Guide

1. Install
2. Create a `config.php` page to store the Twitter OAuth credentials
3. Use `require` to import `config.php` (or preferred filename)
4. Use function `shipit()` in`twitteroauth/src/TwitterOAuth.php` to  immediately
base64 encode and upload media from URL (as opposed to temporarily storing media)

See documentation at https://twitteroauth.com.

PHP versions [listed](https://secure.php.net/supported-versions.php) as "active support" or "security fixes only" are supported.
