# Kinde Translations

This repo contains all the translation files for Kinde public facing screens e.g auth flows

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com) [![Kinde Docs](https://img.shields.io/badge/Kinde-Docs-eee?style=flat-square)](https://kinde.com/docs/) [![Kinde Community](https://img.shields.io/badge/Kinde-Community-eee?style=flat-square)](https://thekindecommunity.slack.com)

## Contributing new languages

We love contributions, if you're keen to get your language supported by Kinde, here are the steps to do so:

1. Fork this repo.

2. Please create a new directory named the languages code ( codes can be found in the table below).

For example, if you were adding Amharic you would do so in a new directory called `am`.

3. Copy our base `auth.json` from `en` into your new directory and update translations for all relevant values.

Where you see ${some_text} this is variable text our system automatically generates, you do not need to translate it, but need to include the variable in the correct order in your translation.

4. Run `npm run validate` which will check all files against our json schema to make sure all keys are accounted for.

5. Make a PR from your fork back to this repo.

6. When in doubt, please refer to Kinde’s [contributing guidelines](https://github.com/kinde-oss/.github/blob/489e2ca9c3307c2b2e098a885e22f2239116394a/CONTRIBUTING.md).

## Language codes

| Language tag (BCP 47) | English name           |
| --------------------- | ---------------------- |
| af                    | Afrikaans              |
| am                    | Amharic                |
| ar                    | Arabic                 |
| ar-001                | Modern Standard Arabic |
| az                    | Azerbaijani            |
| bg                    | Bulgarian              |
| bn                    | Bangla                 |
| bs                    | Bosnian                |
| ca                    | Catalan                |
| cs                    | Czech                  |
| cy                    | Welsh                  |
| da                    | Danish                 |
| de                    | German                 |
| el                    | Greek                  |
| en                    | English                |
| en-AU                 | Australian English     |
| en-GB                 | British English        |
| en-US                 | American English       |
| es                    | Spanish                |
| es-419                | Latin American Spanish |
| es-ES                 | European Spanish       |
| et                    | Estonian               |
| eu-ES                 | Basque                 |
| fa                    | Persian                |
| fi                    | Finnish                |
| fil                   | Filipino               |
| fr                    | French                 |
| fr-CA                 | Canadian French        |
| gl-ES                 | Galician               |
| gu                    | Gujarati               |
| ht                    | Haitian Creole         |
| he                    | Hebrew                 |
| hi                    | Hindi                  |
| hr                    | Croatian               |
| hu                    | Hungarian              |
| hy                    | Armenian               |
| id                    | Indonesian             |
| is                    | Icelandic              |
| it                    | Italian                |
| ja                    | Japanese               |
| ka                    | Georgian               |
| kk                    | Kazakh                 |
| km                    | Khmer                  |
| kn                    | Kannada                |
| ko                    | Korean                 |
| ky                    | Kyrgyz                 |
| lo                    | Lao                    |
| lt                    | Lithuanian             |
| lv                    | Latvian                |
| mk                    | Macedonian             |
| ml                    | Malayalam              |
| mn                    | Mongolian              |
| mr                    | Marathi                |
| ms                    | Malay                  |
| my                    | Burmese                |
| ne                    | Nepali                 |
| nl                    | Dutch                  |
| nn                    | Norwegian Nynorsk      |
| no                    | Norwegian Bokmål       |
| pa                    | Punjabi                |
| pl                    | Polish                 |
| pt                    | Portuguese             |
| pt-BR                 | Brazilian Portuguese   |
| pt-PT                 | European Portuguese    |
| ro                    | Romanian               |
| ru                    | Russian                |
| si                    | Sinhala                |
| sk                    | Slovak                 |
| sl                    | Slovenian              |
| sq                    | Albanian               |
| sr                    | Serbian                |
| sv                    | Swedish                |
| sw                    | Swahili                |
| ta                    | Tamil                  |
| te                    | Telugu                 |
| th                    | Thai                   |
| tr                    | Turkish                |
| uk                    | Ukrainian              |
| ur                    | Urdu                   |
| uz                    | Uzbek                  |
| vi                    | Vietnamese             |
| zh                    | Chinese                |
| zh-Hans               | Simplified Chinese     |
| zh-Hant               | Traditional Chinese    |
| zu                    | Zulu                   |

## Publishing

The core team handles publishing.

## License

By contributing to Kinde, you agree that your contributions will be licensed under its MIT License.
