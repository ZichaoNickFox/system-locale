# 0.4.0.0

* Upgrade ghc support 9.8.4
* Upgrade time from < 1.9 to <= 1.12.2
* Upgrade text from < 1.3 to <= 2.1.1
* Upgrade bytestring < 0.11 to <= 0.12.1.0
* Upgrade attoparsec < 0.14 to <= 0.14.4

# 0.3.0.0

* Inherit all environment except for LC_TIME in call to locale
* More explicitly handle UTF8-decoding
* Fail on non-zero exitcodes from locale

# 0.2.0.0

* Switch to attoparsec to reduce dependency footprint
* Fix build with GHC 7.8

# 0.1.0.0 initial release
