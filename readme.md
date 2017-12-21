| Build Status                             | Latest Release                                      | Version                                            | Last Commit                                                    | Activity                                    |
| :--------------------------------------: | :--------------------------:                        | :----:                                             | :------:                                                       | :------:                                    |
| [![Travis][travis_shield]][travis]       | [![Github Release][release_shield]][github_release] | [![Github Version][version_shield]][github_version] | [![Github Last Commit][last_commit_shield]][github_last_commit] | [![Github commit activity][activity_shield]][github_activity] |


[travis_shield]: https://travis-ci.org/skulumani/business_card.svg?branch=master 
[release_shield]: https://img.shields.io/github/release/skulumani/business_card.svg
[version_shield]: https://badge.fury.io/gh/skulumani%2Fbusiness_card.svg
[last_commit_shield]: https://img.shields.io/github/last-commit/skulumani/business_card.svg
[activity_shield]: https://img.shields.io/github/commit-activity/y/skulumani/business_card.svg

[travis]: https://travis-ci.org/skulumani/business_card
[github_release]: https://github.com/skulumani/business_card/releases/latest
[github_version]: https://github.com/skulumani/business_card/releases/latest
[github_last_commit]: https://github.com/skulumani/business_card/commits/master
[github_activity]: https://github.com/skulumani/business_card/graphs/commit-activity

# Business card in LaTeX

LaTeX source code for a business card.
It is a high quality pdf output suitable for printing from any reputable printing service:

* [vistaprint](http://www.vistaprint.com)
* [moo](http://www.moo.com)

It follows the standard US business card size of 3.5 x 2 inch but is easily modified.
I've complied this from some guides online using standard the standard LaTeX memoir class.

# QR code

[QR Codes](https://en.wikipedia.org/wiki/QR_code) are a useful and efficient way of encoding data into a two dimensional barcode.
The codes are machine readable and are popular in the manufacturing and shipping communities. 
In addition, there is a significant built in error correction and simplicity (there's no need for a power source to transmit the data ).
This allows QR codes to be very robust to poor lighting or even damage.
With the rise of smartphones, QR codes have gained significant popularity in several countries (excluding the US). 

I wanted to include a QR code on my business card to allow an easy way to bridge the gap from paper to digital. 
Luckily, someone has already thought about this and created the [qrcode](https://www.ctan.org/tex-archive/macros/latex/contrib/qrcode?lang=en) package.

# License

The MIT License (MIT)

Copyright (c) 2015 Shankar Kulumani

