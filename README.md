Release notes for Strong's Greek Dictionary in XML with real Greek

By Dr. Ulrik Sandborg-Petersen

* [Personal website](http://ulrikp.org/)
* [Company website, Scripture Systems ApS](http://scripturesys.com/)


# License?

Released under the Creative Commons CC0 waiver.

http://creativecommons.org/publicdomain/zero/1.0/

To the extent possible under law, [Ulrik Sandborg-Petersen](http://ulrikp.org/) has waived all copyright and
related or neighboring rights to *Strong's Dictionary in XML with real
Greek*.


# Release notes

## Version 1.9 (2019-02-05)

* Fix a wrong "derived from": G2552 is derived from G2556 instead of
  G2256.

## Version 1.8 (2018-04-02)

* Much proof-reading of individual entries.
* Some instances of "participle" -> "particle" or "part".
* Many instances of "comparative" -> "compound" or "compounds".
* Remove the <see.../> element, since it is redundant.  The
  information is in the main part of each article.
* Remove the "see" element from the DTD.
* In the DTD, state the fact that the attribute "language" on the element
  "strongsref" is an enumeration consisting of (GREEK|HEBREW).

## Version 1.7 (2017-04-28)

* Release explicitly under the CC0 copyright waiver (Public Domain).


## Version 1.6 (2017-04-28)

* Add link from G5521 to G5514.


## Version 1.55 (2012-07-18)

* Fixed spelling of 'scupltured' --> 'sculptured' in 5480.


## Version 1.5 (2011-09-26)

* Now entries with 'of uncertain affinity' as the derivation have a
  correct split between <strongs_derivation>of uncertain
  affinity;</strongs_derivation> and the real definition.  Before, the
  definition would be included in the derivation as well.

* Fixed derivation of 5043 to be from 5088, not 5098.

* Various other fixes to either spellings or derivations.


## Version 1.4 (2007-09-14)

* Changed the Greek of a 26 entries, to be in conformance with the
  printed edition: 234, 493, 527, 703, 902, 965, 993, 1361, 1420,
  1502, 1503, 1541, 1695, 2216, 2256, 2636, 2810, 3103, 3116, 3138,
  3198, 4609, 4770, 4949, 5253, 5592.

* Moved some words between the various parts (i.e., derivation;
  definition; KJV-definition), to where they belong logically.

* Added some missing derivations.

* Fixed a lot of typos in the text.


## Version 1.3 (2007-05-29)

* Changed the Greek of about half a dozen entries, to be in
  conformance with the printed version.

* Added SBL-style transliterations on the <greek/> element, as the
  attribute "translit".

