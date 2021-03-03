<h1 align="center">
	<a href="https://github.com/pumpncode/template">
		<img alt="The logo of Pumpn Code&#x27;s template project." decoding="async" height="200" loading="lazy" src="media/images/logocolored.svg">
	</a>
</h1>

<table>
	<thead>
		<tr>
			<th colspan="5">
				<a href="">🌐</a>
			</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td data-code="de">
				<a href="docs/de/readme.md">Deutsch</a>
			</td>
			<td data-code="en">
				<strong>English</strong>
			</td>
			<td rowspan="0">
				<a href="">✍️</a>
			</td>
		</tr>
	</tbody>
</table>

[![stars][2]][1]
[![contributors][4]][3]
[![forks][6]][5]
[![open-issues][8]][7]
[![closed-issues][10]][9]
[![open-prs][12]][11]
[![closed-prs][14]][13]

[![license][16]][15]
[![dependencies][18]][17]
[![dev-dependencies][20]][19]
[![peer-dependencies][22]][21]

[![downloads][24]][23]
[![version][25]][23]
[![node][27]][26]

[![reddit][29]][28]
[![twitter][31]][30]
[![discord][33]][32]

[![website][35]][34]

This is the main template repository for our projects and the origin of every other template, which is why it shouldn't be used directly for end products. It includes the basic structure and important, so-called dotfiles.

*At the moment it includes more specific files (a rollup configuration for example), but those will be removed once we reach 2.0.0 and have a separate repository for them.*

---

"Unordered" lists in this document are ordered by priority from top to bottom, but aren't markdown ordered lists because they don't signify fixed sequences of steps.

This document uses emoji suffixes in some cases to possibly speed up your setup process by highlighting options you may or may not want to take into consideration:

- The suffix 💎 marks a **recommended** option or extra-step.
- The suffix 🤡 marks a possible but **not recommended** option.
- The suffixes 🍎 (macOS), 🪟 (Windows and [WSL][36]) and 🐧 (Linux) mark information or installation steps unique to **specific platforms**.

## Getting Started

### Prerequisites

If you're a developer, you'll presumably have those or working alternatives, feel free to skip to the [Installation section][37]. This guide expects you have [Windows][38], or a Unix or Unix-like operating system ([macOS][39] for example) and a [modern browser][40] installed. This project should work on every imaginable modern system configuration, but your best bet would be to use a well established and popular one.

- [GitHub Account][41] 💎
- [Homebrew][42] 🍎

	```sh
	/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
	```

- [Git][43]
	- [macOS][44] 🍎
		- Homebrew 💎

			```sh
			brew install git
			```

		- [Binary Installer][45]
		- [Through Xcode][46] 🤡
			> Installing Git through Xcode, which was a dozen gigabytes large and took an hour to setup last time I checked, is a classic [Pyrrhic victory][47]. If you already have Xcode, I guess it's fine to use "their" Git though.
	- [Windows][48] 🪟
	- [Linux][49] 🐧
- [Node.js][50]
	- Install through [nvm][51] 💎
		- macOS, Linux & WSL 💎
			1. Install [nvm][51]

				```sh
				curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
				```

			2. Install the latest Node.js

				```sh
				nvm install node
				```

		- Windows 🪟
			1. Install [nvm-windows][52]
			2. Install the latest Node.js

				```sh
				nvm install latest
				```

	- [Download and install directly][53]
- [A source-code editor][54]

### Installation

1. Get the template
	- Create a new repository from template 💎
		1. Click "Use this template"
			![Screenshot of "Use this template" button][55]
		2. Fill in the details, check "Include all branches" and click "Create repository from template"
			![Screenshot of Create a new repository from template screen][56]
		3. Clone your new repository

			```sh
			git clone https://github.com/username/my-new-repository.git
			```

	- Create a new repository by cloning 🤡
		> This completely defeats the purpose of the GitHub template feature, because normal clones (and forks) copy the whole commit history (and other things) but not all branches, which normally isn't what you want when creating a new project based on a boilerplate. Read more [here][57].
		1. Clone this repository into a new folder

			```sh
			git clone https://github.com/pumpncode/template.git my-new-repository
			```

2. Set it up
	1. Go into your new repository folder

		```sh
		cd my-new-repository
		```

	2. Install the dependencies

		```sh
		npm install
		```

## Usage

Because this is a template, the usage depends on what your new project will do. Once everything is installed, you can try running the scripts in the [package.json][58], these make use of every other feature of this template.

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### helloWorld

This is a hello world function.

#### Examples

```javascript
console.log(helloWorld()); // logs "Hello World!"
```

Returns **[string][59]** "Hello World!".

## Roadmap

See the [current projects][60] and the [open issues][61] for a list of proposed features and known issues.

## Contributing

Any contributions you make are **greatly appreciated**.

See [contributing.md][62]  for ways to get started.

This project has a [code of conduct][63]. By interacting with this repository you agree to follow its terms.

## Contact

Pumpn Code - [office@pumpn.net][64]

Nano Miratus - [@nnmrts][65] - [nanomiratus@gmail.com][66]

Project Link: [https://github.com/pumpncode/template][67]

## Acknowledgments

- [unified][68]
- [remark][69]
- [Best-README-Template][70]

## Contributors

| Name             | Website                  | GitHub            | Twitter           |
| ---------------- | ------------------------ | ----------------- | ----------------- |
| **Nano Miratus** | [https://pumpn.net/][71] | [**@nnmrts**][72] | [**@nnmrts**][73] |

## License

[MIT][74] © [Pumpn Code][75]

[1]: https://github.com/pumpncode/template/stargazers
[2]: https://badgen.net/github/stars/pumpncode/template?color=00f&labelColor=d07&icon=github
[3]: https://github.com/pumpncode/template/graphs/contributors
[4]: https://badgen.net/github/contributors/pumpncode/template?color=00f&labelColor=d07&icon=github
[5]: https://github.com/pumpncode/template/network/members
[6]: https://badgen.net/github/forks/pumpncode/template?color=00f&labelColor=d07&icon=github
[7]: https://github.com/pumpncode/template/issues?q=is%3Aopen+is%3Aissue
[8]: https://badgen.net/github/open-issues/pumpncode/template?color=00f&labelColor=d07&icon=github
[9]: https://github.com/pumpncode/template/issues?q=is%3Aclosed+is%3Aissue
[10]: https://badgen.net/github/closed-issues/pumpncode/template?color=00f&labelColor=d07&icon=github
[11]: https://github.com/pumpncode/template/pulls?q=is%3Aopen+is%3Apr
[12]: https://badgen.net/github/open-prs/pumpncode/template?color=00f&labelColor=d07&icon=github&label=open%20pull%20requests
[13]: https://github.com/pumpncode/template/pulls?q=is%3Aclosed+is%3Apr
[14]: https://badgen.net/github/closed-prs/pumpncode/template?color=00f&labelColor=d07&icon=github&label=closed%20pull%20requests
[15]: https://github.com/pumpncode/template/blob/master/license.md
[16]: https://badgen.net/github/license/pumpncode/template?color=00f&labelColor=d07&icon=github
[17]: https://david-dm.org/pumpncode/template
[18]: https://badgen.net/david/dep/pumpncode/template?color=00f&labelColor=d07&icon=npm&label=dependencies
[19]: https://david-dm.org/pumpncode/template?type=dev
[20]: https://badgen.net/david/dev/pumpncode/template?color=00f&labelColor=d07&icon=npm&label=devDependencies
[21]: https://david-dm.org/pumpncode/template?type=peer
[22]: https://badgen.net/david/peer/pumpncode/template?color=00f&labelColor=d07&icon=npm&label=peerDependencies
[23]: https://npmjs.com/package/@pumpn/template
[24]: https://badgen.net/npm/dm/@pumpn/template?color=00f&labelColor=d07&icon=npm&label=downloads
[25]: https://badgen.net/npm/v/@pumpn/template?color=00f&labelColor=d07&icon=npm&label=version
[26]: https://nodejs.org
[27]: https://badgen.net/npm/node/@pumpn/template?color=00f&labelColor=d07&icon=https%3A%2F%2Fsimpleicons.now.sh%2Fnode-dot-js%2Ffff
[28]: https://reddit.com/r/pumpnuniverse
[29]: https://badgen.net/badge/subreddit/subreddit?color=00f&labelColor=d07&icon=https%3A%2F%2Fsimpleicons.now.sh%2Freddit%2Ffff&label=
[30]: https://twitter.com/PumpnUniverse
[31]: https://badgen.net/badge/twitter/twitter?color=00f&labelColor=d07&icon=twitter&label=
[32]: https://discord.gg/WKvpetegZq
[33]: https://badgen.net/badge/discord/discord?color=00f&labelColor=d07&icon=discord&label=
[34]: https://pumpn.net/code/projects/template
[35]: https://badgen.net/badge/website/website?color=00f&labelColor=d07&icon=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABkAAAAMCAQAAAA9%2B97AAAAABGdBTUEAALGPC%2FxhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAAmJLR0QA%2F4ePzL8AAAAJcEhZcwAACxMAAAsTAQCanBgAAAAHdElNRQflAREIHwyVZyrWAAABCklEQVQoz3WRvUvCURSGDxQEkSEYbdFg%2F4Y2BBLU0tRYLbk4NOQa7uEQQVMEUUMELY1BkDQpSEXRBwSKQxFF0hdUBE%2FL6%2Fldk%2B5dzvue8xzOvccwv92MUWCPKg2awCVdykwyFNW1giTrfPH3JJXNA1uMhMiKSmqUaQZIynsfALDaQkoqmNZ4J45MOTIh5xgzliU%2BSCi97ciMI3Fe5RWNO4W39GD0kgsGmw8%2B51zevfGo8JsX3vlpe36InMl7Mjb4%2F8w5EONZ3qbRT01iiVEWmaXoyK6AQfbl1IkbRh%2BHAKx5z7JDD5S4dnVELFplhtNg9gFuOoasMN6%2BfcNIkw3UAld88sYFO%2BQYjjK%2F7%2FzNJHjJbowAAAAldEVYdGRhdGU6Y3JlYXRlADIwMjEtMDEtMTdUMDg6MzE6MTErMDA6MDDw92QkAAAAJXRFWHRkYXRlOm1vZGlmeQAyMDIxLTAxLTE3VDA4OjMxOjExKzAwOjAwgarcmAAAAABJRU5ErkJggg%3D%3D&label=
[36]: https://docs.microsoft.com/en-us/windows/wsl/about
[37]: #installation
[38]: https://www.microsoft.com/windows
[39]: https://www.apple.com/macos
[40]: https://browsehappy.com/
[41]: https://github.com/join
[42]: https://brew.sh/
[43]: https://git-scm.com/
[44]: https://git-scm.com/download/mac
[45]: https://sourceforge.net/projects/git-osx-installer/
[46]: https://developer.apple.com/xcode/
[47]: https://en.wikipedia.org/wiki/Pyrrhic_victory
[48]: https://git-scm.com/download/win
[49]: https://git-scm.com/download/linux
[50]: https://nodejs.org/
[51]: https://github.com/nvm-sh/nvm
[52]: https://github.com/coreybutler/nvm-windows
[53]: https://nodejs.org/en/download/current/
[54]: https://en.wikipedia.org/wiki/Source-code_editor#Notable_examples
[55]: media/images/screenshot-use-template.png
[56]: media/images/screenshot-create-from-template.png
[57]: https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template#about-repository-templates
[58]: package.json
[59]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String
[60]: https://github.com/pumpncode/template/projects
[61]: https://github.com/pumpncode/template/issues
[62]: .github/contributing.md
[63]: .github/code-of-conduct.md
[64]: mailto:office@pumpn.net
[65]: https://twitter.com/nnmrts
[66]: mailto:nanomiratus@gmail.com
[67]: https://github.com/pumpncode/template
[68]: https://unifiedjs.com/
[69]: https://github.com/remarkjs
[70]: https://github.com/othneildrew/Best-README-Template
[71]: https://pumpn.net/
[72]: https://github.com/nnmrts
[73]: https://twitter.com/nnmrts
[74]: license.md
[75]: https://pumpn.net/
