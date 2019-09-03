# IPFS application Repository

(https://github.com/sddipinai/ipfs/spec.md)

> Specification

This is the spec document for the IPFS dental application.

The spec has a directory `spec` which contains:

1. [database spec] (https://github.com/sddipinai/spec/database/spec_db.md) for the layout of the ipfs dental db metadata.
2. [file layout] (https//github.com/sddipinai/spec/files/file_layout.md)([work in progress]).A link to a linter you can use to keep your README maintained ([work in progress]).
3. [IPFS api] (https://github.com/sddipinai/ipfs/spec/api.md) The api spec gives you a guide on how to use he api to generate dental cheatsheet in your application.
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

Standard Readme started with the issue originally posed by [@maxogden](https://github.com/maxogden) over at [feross/standard](https://github.com/feross/standard) in [this issue](https://github.com/feross/standard/issues/141), about whether or not a tool to standardize readmes would be useful. A lot of that discussion ended up in [zcei's standard-readme](https://github.com/zcei/standard-readme/issues/1) repository. While working on maintaining the [IPFS](https://github.com/ipfs) repositories, I needed a way to standardize Readmes across that organization. This specification started as a result of that.

> Your documentation is complete when someone can use your module without ever
having to look at its code. This is very important. This makes it possible for
you to separate your module's documented interface from its internal
implementation (guts). This is good because it means that you are free to
change the module's internals as long as the interface remains the same.

> Remember: the documentation, not the code, defines what a module does.

~ [Ken Williams, Perl Hackers](http://mathforum.org/ken/perl_modules.html#document)

Writing READMEs is way too hard, and keeping them maintained is difficult. By offloading this process - making writing easier, making editing easier, making it clear whether or not an edit is up to spec or not - you can spend less time worry about whether or not your initial documentation is good, and spend more time writing and using code.

As well, standardizing can help elsewhere. By having a standard, users can spend less time searching for the information they want. They can also build tools to gather search terms from descriptions, to automatically run example code, to check licensing, and so on.

The goals for this repository are:

1. A well defined **specification**. This can be found in the [Spec document](spec.md). It is a constant work in progress; please open issues to discuss changes.
2. **Sample cheatsheets**. Sample IPFS Dental Cheatsheets in the `sample-cheatsheetss` folder.
3. A **linter** that can be used to look at errors in a given Readme. Please refer to the [tracking issue](https://github.com/RichardLitt/standard-readme/issues/5).
4. The **apis** that can be used to quickly scaffold out new IPFs dental cheatsheets. See [sample-cheatseets directory ](https://github.com/sddipinai/ipfs/sample-cheatsheets).
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

To use the generator, look at [generator-standard-readme](https://github.com/RichardLitt/generator-standard-readme). There is a global executable to run the generator in that package, aliased as `standard-readme`.

## Badge

If your README is compliant with the `sample-cheatsheets` provided and you're on GitHub, it would be great if you could add the badge. This allows people to link back to this Spec, and helps adoption of the README. The badge is **not required**.

[![README](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/sddipinai/README)

To add in Markdown format, use this code:

```
[![README compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/sddipinai/README)
```

## Example ipfs dental cheatsheets

To see how the specification has been applied, see the [sa,[;e-cheatsheets](sample-cheatsheets/).

## Related Efforts

- [Art of Readme](https://github.com/noffle/art-of-readme) - 💌 Learn the art of writing quality READMEs.
- [open-source-template](https://github.com/davidbgk/open-source-template/) - A README template to encourage open-source contributions.

## Maintainers

[@sddipinai](https://github.com/sddipinai.

## Contributing

Feel free to dive in! [Open an issue](https://github.com/sddipinai/ipfs/issues/new) or submit PRs.

IPFS dental cheatsheet follows the [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) Code of Conduct.

### Contributors

This project exists thanks to all the people who contribute. 
<a href="graphs/contributors"><img src="https://opencollective.com/standard-readme/contributors.svg?width=890&button=false" /></a>


## License

[MIT](LICENSE) © Ileana DiPina
