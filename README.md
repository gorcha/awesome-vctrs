# Awesome VectoRs

A curated list of amazingly awesome R vector classes, and the packages that provide them.


## Contributing

Please read [CONTRIBUTING](./CONTRIBUTING.md) if you wish to add a new vector class.


## Table of Contents

* [Awesome VectoRs](#awesome-vectors)
  * [Base](#base)
  * [Numbers](#numbers)
  * [Date and time](#date-and-time)
  * [Compound](#compound)
  * [Computing](#computing)
  * [Internal](#internal)
* [Resources](#resources)
  * [Blogs](#blogs)
  * [Books](#books)
  * [Repositories](#repositories)


## Base

*Classes provided by base R.*

* [`character`](https://rdrr.io/r/base/character.html) - Strings: [`"a"`](reprex/character.md)
* [`numeric`](https://rdrr.io/r/base/numeric.html) - Floating-point numbers: [`1.234567`](reprex/numeric.md)
* [`integer`](https://rdrr.io/r/base/integer.html) - 32-bit integers: [`1`](reprex/integer.md)
* [`numeric_version`](https://rdrr.io/r/base/numeric_version.html) - Software versions: [`'1.23.456'`](reprex/numeric_version.md)
* [`POSIXct`](https://rdrr.io/r/base/as.POSIXlt.html) - Calendar time with time zone, stored as days since epoch: [`2020-03-03 09:16:17 CET`](reprex/POSIXct.md)
* [`POSIXlt`](https://rdrr.io/r/base/as.POSIXlt.html) - Calendar time with time zone, stored as record of components: [`2020-03-03 09:16:17 CET`](reprex/POSIXlt.md)


## Numbers

*Classes that wrap numbers.*

* [`units`](https://r-quantities.github.io/units/reference/set_units.html) - Numbers with units: [`1 [m/s]`](reprex/units.md)


## Date and time

*Classes that wrap dates and times.*

* [`aweek`](https://www.repidemicsconsortium.org/aweek) - Weeks that start on any day of the week: [`2020-W10-2`](reprex/aweek.md)
* [`date_xx`](https://s-fleck.github.io/dint/reference/date_y.html) - Years, year-quarter, year-month and year-week: [`2020-Q1`](reprex/date_xx.md)
* [`hms`](https://hms.tidyverse.org/reference/hms.html) - Time of day: [`12:34:56`](reprex/hms.md)
* [`yr`](https://era.joeroe.io/reference/yr.html) - Year-based time scales: [`4.2 ka`](reprex/yr.md)

## Compound

*Classes that wrap complex objects.*

* [`blob`](https://blob.tidyverse.org/reference/blob.html) - Binary Large OBjects: [`blob[42 B]`](reprex/blob.md)
* [`labelled`](https://haven.tidyverse.org/reference/labelled.html) - Labelled vectors: [`<Labelled double> 3` with labels](reprex/labelled.md)
* [`mixed_units`](https://r-quantities.github.io/units/reference/mixed_units.html) - Numbers with different units: [`1 [m], 2 [kg]`](reprex/mixed_units.md)
* [`phone`](https://socialresearchcentre.github.io/dialr/reference/dialr-phone.html) - Phone numbers parsed with Google's [libphonenumber](https://github.com/google/libphonenumber) for formatting and further processing: [`# Parsed phone numbers: 5 total, 4 successfully parsed`](reprex/phone.md)
* [`term`](https://poissonconsulting.github.io/term/) - Labels for values in numeric objects: [`beta[1,2]`](reprex/term.md)

## Computing

*Classes related to computing*

* [`ip_address`](https://davidchall.github.io/ipaddress/reference/ip_address.html) - IP address: [`192.168.0.1`](reprex/ip_address.md)
* [`ip_interface`](https://davidchall.github.io/ipaddress/reference/ip_interface.html) - IP interface: [`192.168.0.1/24`](reprex/ip_interface.md)
* [`ip_network`](https://davidchall.github.io/ipaddress/reference/ip_network.html) - IP network: [`192.168.0.0/24`](reprex/ip_network.md)


## Internal

*Classes implemented by packages for their own use*

* [`tokenlist`](https://tidymodels.github.io/textrecipes/dev/articles/tokenlist.html) - List of tokens: [`[3 tokens]` with number of unique tokens](reprex/tokenlist.md)


# Resources

## Books

* [Advanced R](https://adv-r.hadley.nz/) by Hadley Wickham


## Repositories

* [vctrs](https://vctrs.r-lib.org/): simplifies creating vector classes

## Talks

* [Jesse Sadler, vctrs: Creating custom vector classes with the vctrs package at RStudio::conf2020](https://resources.rstudio.com/rstudio-conf-2020/vctrs-creating-custom-vector-classes-with-the-vctrs-package-jesse-sadler) with the companion tutorial [debvctrs](https://github.com/jessesadler/debvctrs)


## License

![cc license](http://i.creativecommons.org/l/by-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/) license.
