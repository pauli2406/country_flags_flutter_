![Logo](./.github/flag.png)

# Country Flags Flutter 
#### (Fork from flag as it was not maintained anymore)
[![Pub Version](https://img.shields.io/pub/v/country_flags_flutter_?style=flat-square)](https://github.com/pauli2406/country_flags_flutter_)
[![Bless](https://img.shields.io/badge/bless-God-brightgreen?style=flat-square)](https://lunagao.github.io/BlessYourCodeTag/)

A flag Flutter package for `Android` / `iOS` / `Web`. Based by https://github.com/dnfield/flutter_svg .

## Screenshot
![Screenshot](https://github.com/pauli2406/country_flags_flutter_/blob/stable/github/image.png)
![Screenshot](https://github.com/pauli2406/country_flags_flutter_/blob/stable/github/image_web.jpg))

## Svg sources
* All flags came from https://github.com/lipis/flag-icons/releases/tag/v4.1.4

Thanks the great project [flag-icons](https://github.com/lipis/flag-icons).

## Flag list

ISO 3166-1-alpha-2 Flags

Note: 

Organisations
* `eu` European Union.

Disputed territories
* `hk` Hong Kong. Special Administrative Region of China.
* `mo` Macau. Special Administrative Region of China.
* `eh` Western Sahara. Claimed by Morocco.
* `tw` Taiwan. Claimed by China.

Undisputed territories which are non-UN state
* `va` Vatican City. Govern by the Holy See.

## How to use

`Flag.fromCode(FlagsCode.COUNTRY_CODE, height: HEIGHT, width: WIDTH),`
`Flag.fromString(COUNTRY_CODE, height: HEIGHT, width: WIDTH),`
`Flags.fromCode([FlagsCode.GB, FlagsCode.US], height: 100, width: 100 * 4 / 3),`

Such as
* `Flag.fromCode(FlagsCode.AD, height: 100, width: null)`
* `Flag.fromString('AD', height: null, width: null)`
* `Flag.fromString('AD', height: 10, width: 100, fit: BoxFit.fill)`
