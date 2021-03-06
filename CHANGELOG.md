# Changelog

All notable changes to this project will be documented in this file. This project adheres to [Semantic Versioning](http://semver.org/).
In order to read more about upgrading and BC breaks have a look at the [UPGRADE Document](UPGRADE.md).

## 1.1.3 (27. May 2019)

+ [#1](https://github.com/luyadev/luya-mailjet/pull/1) Added deduplicate flag to be able to send a mail more than once to a recipient in the same campaign
+ [#1](https://github.com/luyadev/luya-mailjet/pull/1) Added CustomCampaign and CustomId to provide additional tagging ability
+ [#1](https://github.com/luyadev/luya-mailjet/pull/1) Added setTemplateLanguage to avtivly set the TemplateLanguage-Flag (true to parse variables into template)

## 1.1.2 (6. May 2019)

+ Fixed bug with double replacements.

## 1.1.1 (6. May 2019)

+ Fixed bug with nested elements an `mj-text` also with `mj-text` tags with attributes like `<mj-text color="black">text</mj-text>`.

## 1.1.0 (6. May 2019)

+ Force raw elements to pass the content as CDATA. For example `<mj-text><a href="https://luya.io">Go</a></mj-text>` must be passed as link content instead of a child node of mj-text node.

## 1.0.0 (21. March 2019)

+ First stable release.
