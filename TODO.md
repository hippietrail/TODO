# TODO
## A kind of global TODO

1. ### ICU
    - How to find out which calendars/chronologies are applicable for a given language/locale?
    - How to find out which numbering systems are applicable for a given language?
    - How to format numers in a universal way that works for Latin and Thai, which use sequential codepoints but also Chinese and Japanese, which don't?
    - Which syntax to use for the locale string?  
        - Old (LDML 1.7 or older) : `th_TH@calendar=gregorian;numbers=thai`
        - New : `th_TH_u_ca_gregory_nu_thai`
        - Does `java.util.Locale` only support old but without Chinese and Japanese numbers?
        - Is `android.icu` supposed to support the > 1.7 LDML syntax?
        - How to check which LDML version an Android device or Android release uses?

2. ### [overlaid images](https://github.com/hippietrail/overlaid-images)
    - How to add an alpha channel to the top image?
