# IPFS application Repository

(https://github.com/sddipinai/ipfs/README.md)

> README

This ipfs application provides a simple IPFS app which allows you to upload image and keep a log of your own dental images.  If keeps log of the physician and the date the image was taken.  It becomes a cheatsheet of the dental work you have had within a given time.  It also allows you to be able to provide this information to your dentist in case you move to another location.  The cost of xrays and redoing xrays would be kept down.

This repository contains:

1. [The specification](spec.md) for how your standard dental cheatsheet should look.
2. A link to a linter you can use to keep your README maintained ([work in progress](https://github.com/sddipinai/ipfs/issues/5)).
3. A link to [a generator](https://github.com/sddipinai/ipfs/dental/generator) you can use to create a dental cheatsheet.
4. [A badge](#badge) to point to this spec.
5. [Examples of ipfs dental cheatsheets](sample-ipfs/).

IPFS is designed for open source libraries. Although it’s [historically](#background) made for Node and npm projects, it also applies to libraries in other languages and package managers.


## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
	- [Generator](#generator)
- [Badge](#badge)
- [Example IPFS Cheatsheet](#sample-ipfs)
- [Related Efforts](#related-efforts)
- [Maintainers](#maintainers)
- [Contributing](#contributing)
- [License](#license)

## Background

IPFS (https://github.com/sddipinai/ipfs) started when I was looking for a dentist to perform a root canal on my molar.  I wanted to get quotes and see what were my options and soon discovered that dental insurance has its limitations and con artists.  Your great insurance can be easily depleted with xrays and just add procedures without you having control.  [IPFS](https://github.com/sddipinai/ipfs) repository, attempts to give you some control over your data and who you can share it with. This specification started as a result of that.  The question is why can't you have a set of xrays with dates and procedures that you have legal right to view and share with whichever dentist you wish.  Wouldn't that cut down the depletion of your charges and cost of procedures and also give you a high confidence of your dental assets and their cost?

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

1. A well defined **specification**. This can be found in the [Dental Spec document](dental_spec.md). It is a constant work in progress; please open issues to discuss changes.
2. **An example DentalCheatsheet** [Dental Cheatsheet] (dental_cheatsheet.md). Please check out the sample-cheatsheet [DentalCheatsheet] (dental_cheatsheet.md), and the other samples provided  in the `sample-cheatsheets` folder.
3. A **linter** that can be used to look at errors in a given Readme. Please refer to the [tracking issue](https://github.com/RichardLitt/standard-readme/issues/5).
4. A **generator** that can be used to quickly scaffold out new READMEs. See [generator-standard-readme](https://github.com/RichardLitt/generator-standard-readme).
5. A **compliant badge** for users. See [the badge](#badge).

## Install

This project uses [node](http://nodejs.org) and [npm](https://npmjs.com). Go check them out if you don't have them locally installed.

```sh
$ npm install --global standard-readme-spec
```

## Usage

This is only a documentation package. You can print out [spec.md](spec.md) to your console:

```sh
$ standard-readme-spec
# Prints out the standard-readme spec
```

### Generator

To use the generator, look at [generator-standard-readme](https://github.com/RichardLitt/generator-standard-readme). There is a global executable to run the generator in that package, aliased as `standard-readme`.

## Badge

If your README is compliant with Standard-Readme and you're on GitHub, it would be great if you could add the badge. This allows people to link back to this Spec, and helps adoption of the README. The badge is **not required**.

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

To add in Markdown format, use this code:

```
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
```

## Example Readmes

To see how the specification has been applied, see the [example-readmes](example-readmes/).

## Related Efforts

- [Art of Readme](https://github.com/noffle/art-of-readme) - 💌 Learn the art of writing quality READMEs.
- [open-source-template](https://github.com/davidbgk/open-source-template/) - A README template to encourage open-source contributions.

## Maintainers

[@RichardLitt](https://github.com/RichardLitt).

## Contributing

Feel free to dive in! [Open an issue](https://github.com/RichardLitt/standard-readme/issues/new) or submit PRs.

Standard Readme follows the [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) Code of Conduct.

### Contributors

This project exists thanks to all the people who contribute. 
<a href="graphs/contributors"><img src="https://opencollective.com/standard-readme/contributors.svg?width=890&button=false" /></a>


## License

[MIT](LICENSE) © Richard Littauer
