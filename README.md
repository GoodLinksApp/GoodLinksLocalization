# GoodLinks Localizations

This is the community language repository for [GoodLinks](https://goodlinks.app).

## Localization

Folders are named in the format "[[language code]](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)" or "[[language code]](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)-[[country/region code]](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)", for example, "de", "zh-Hans".

Strings are denoted as `"key" = "value";`, where the keys remain the same across all languages, and the values are localized. There must be a `;` at the end of each line.

Where you see a `%@` or `%ld` token, this denotes a value that is replaced at runtime. The corresponding localized value must keep the token in the right place to provide the same meaning as the English value.

## Contributing

Localizations can be contributed either by submitting a pull request (preferred), by submitting an issue report, or by contacting me directly via email.