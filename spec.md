# IPFS application Repository

(https://github.com/sddipinai/ipfs/spec.md)

> Specification

This is the spec document for the IPFS dental application.

The spec has a directory `spec` which contains:

1. [database spec] (https://github.com/sddipinai/spec/database/spec_db.md) for the layout of the ipfs dental db metadata.
2. [file layout] (https//github.com/sddipinai/spec/files/file_layout.md)([work in progress]).A link to a linter you can use to keep your README maintained ([work in progress]).
3. [IPFS api] (https://github.com/sddipinai/ipfs/spec/api/spec_api.md) The api spec gives you a guide on how to use he api to generate dental cheatsheet in your application.
4. [A badge](#badge) to point to this spec.

IPFS is designed for open source libraries. Although it’s [historically](#background) made for Node and npm projects, it also applies to libraries in other languages and package managers.


## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
	- [APIs](#apis)
- [Badge](#badge)
- [Example IPFS Cheatsheet](#sample-cheatsheets)
- [Related Efforts](#related-efforts)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [License](#license)

## Background

IPFS started with an inspiration resulting from a need.
I had a toothache, discovered I had two wisdom teeth that needed to be pulled and needed to get a dentist to do it.  In the processs of obtaining help to this problem, I was presented with one dilemma, how to get a dentist to not hustle me into taking the same xrays and different procedures, eating my insurance dollars.  The solution, I thought was have the exploratory checkups documented in a way that I could submit any xrays or work previously done and have one record that we can all globally speak on.  My dental record of truth!  My data that would not be exploited.

The goals for this repository are:

1. A well defined **specification**. This can be found in the [Spec document](spec.md). It is a constant work in progress; please open issues to discuss changes.
2. **Sample dental cheatsheets**. Sample IPFS Dental Cheatsheets in the `sample-cheatsheetss` folder.
4. The **apis** that can be used to quickly scaffold out new IPFs dental cheatsheets. See [sample-cheatsheets directory ](https://github.com/sddipinai/ipfs/sample-cheatsheets).
5. A **compliant badge** for users. See [the badge](#badge).

## Install

This project uses [node](http://nodejs.org) and [npm](https://npmjs.com). Go check them out if you don't have them locally installed.

```sh
$ git clone https://github.com/sddipinai/ipfs 
$ cd ipfs
$ npm install 
```

## Usage

This is only a documentation package. You can print out [spec.md](spec.md) to your console:

GOTO localhost:3000\spec.md
To view the spec

### apis

To use the api, look at [generator-standard-readme](https://github.com/dipina/spec/api/spec_api.md). 

## Badge

If your cheatsheet is compliant with the `sample-cheatsheets` provided and you're on GitHub, it would be great if you could add the badge. This allows people to link back to this Spec, and helps adoption of the README. The badge is **not required**.

[![README](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/sddipinai/README)

To add in Markdown format, use this code:

```
[![README compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/sddipinai/README)
```

## Example ipfs dental cheatsheets

To see how the specification has been applied, see the [sample-cheatsheets](sample-cheatsheets/).

## Related Efforts



## Maintainers

[@sddipinai](https://github.com/sddipinai.

## Contributing

Feel free to dive in! [Open an issue](https://github.com/sddipinai/ipfs/issues/new) or submit PRs.

IPFS dental cheatsheet follows the [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) Code of Conduct.

### Contributors

This project exists thanks to all the people who contribute. 
<a href="graphs/contributors"><img src="https://github.com/sddipinai/ipfs/commits?author=sddipinai" /></a>


## License

[MIT](LICENSE) © Ileana DiPina
