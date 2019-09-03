# IPFS application Repository

(https://github.com/sddipinai/ipfs/README.md)

> README

This ipfs application provides a simple IPFS app which allows you to upload image and keep a log of your own dental images.  If keeps log of the physician and the date the image was taken.  It becomes a cheatsheet of the dental work you have had within a given time.  It also allows you to be able to provide this information to your dentist in case you move to another location.  The cost of xrays and redoing xrays would be kept down.

This repository contains:

1. [The specification](spec.md) for how your standard dental cheatsheet should look.
2. A link to a linter you can use to keep your README maintained ([work in progress](https://github.com/sddipinai/ipfs/issues)).
3. A link to [api](https://github.com/sddipinai/ipfs/api/spec_api.md) IPFS dental cheatsheet api of work done.
4. [A badge](#badge) to point to this spec.
5. [Examples of ipfs dental cheatsheets](sample-ipfs/).

IPFS is designed for open source libraries. Although it’s [historically](#background) made for Node and npm projects, it also applies to libraries in other languages and package managers.


## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Badge](#badge)
- [Example IPFS Cheatsheet](#sample-ipfs)
- [Related Efforts](#related-efforts)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [License](#license)

## Background

IPFS (https://github.com/sddipinai/ipfs) started when I was looking for a dentist to perform a root canal on my molar.  I wanted to get quotes and see what were my options and soon discovered that dental insurance has its limitations and con artists.  Your great insurance can be easily depleted with xrays and just add procedures without you having control.  [IPFS](https://github.com/sddipinai/ipfs) repository, attempts to give you some control over your data and who you can share it with. This specification started as a result of that.  The question is why can't you have a set of xrays with dates and procedures that you have legal right to view and share with whichever dentist you wish.  Wouldn't that cut down the depletion of your charges and cost of procedures and also give you a high confidence of your dental assets and their cost?


The goals for this repository are:

1. A well defined **specification**. This can be found in the [Dental Spec document](dental_spec.md). It is a constant work in progress; please open issues to discuss changes.
2. **An example DentalCheatsheet** [Dental Cheatsheet] (dental_cheatsheet.md). Please check out the sample-cheatsheet [DentalCheatsheet] (dental_cheatsheet.md), and the other samples provided  in the `sample-cheatsheets` folder.

3. A **compliant badge** for users. See [the badge](#badge).

## Install

This project uses [node](http://nodejs.org) and [npm](https://npmjs.com). Go check them out if you don't have them locally installed.

```sh
$ git clone https://github.com/sddipinai/ipfs/
$ cd ipfs
$ npm install 
```

## Usage

This is only a documentation package. You can print out [spec.md](spec.md) to your console:

```sh
$ more spec.md
# Prints out the spec.md README file
```

### api

To use the api, look at [spec_api](https://github.com/sddipinai/api/speck_api.md). 

## Badge

If your README is compliant with Standard-Readme and you're on GitHub, it would be great if you could add the badge. This allows people to link back to this Spec, and helps adoption of the README. The badge is **not required**.

[README](https://github.com/sddipinai/ipfs/README.md)

To add in Markdown format, use this code:

```
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
```

## Example Cheatsheets

To see how the specification has been applied, see the [sample-cheatsheets(sample-cheatsheets/).

## Related Efforts


## Maintainers

[@sddipinai](https://github.com/sddipinai).

## Contributing

Feel free to dive in! [Open an issue](https://github.com/sddipinai/ipfs/issues/new) or submit PRs.

IPFS follows the [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) Code of Conduct.

### Contributors

This project exists thanks to all the people who contribute. 
[Contributors] (https://github.com/sddipinai/ipfs/graphs/contributors).


## License

[MIT](LICENSE) © Ileana DiPina