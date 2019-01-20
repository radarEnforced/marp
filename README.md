<div align="center">
  <p>
    <img src="marp.png" alt="Marp" width="500" />
  </p>
  <p>
    <strong>Marp</strong>: Markdown Presentation Ecosystem
  </p>
</div>

> This repository is the entrance of **_next version of Marp_ (Marp Next)**.
>
> Refer to **[yhatt/marp]** when you are looking for pre-released desktop app. However, keep in your mind that _it has no longer been developed_.

---

**Marp** is the ecosystem to write your presentation with plain Markdown.

## Marp family

|                                    Name | Description                                                                                                                         | Release                                                                                                           |
| --------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------- |
|                 [@marp-team/marp][marp] | 🚪 The entrance repository of Marp family. In future we would host website.                                                         |                                                                                                                   |
|       <nobr>**[Marpit][marpit]**</nobr> | The skinny framework for creating slide deck from Markdown. ([marpit.marp.app])                                                     | [![@marp-team/marpit](https://img.shields.io/npm/v/@marp-team/marpit.svg?style=flat-square)][marpit-npm]          |
| <nobr>**[Marp Core][marp-core]**</nobr> | The core of Marp converter based on [Marpit][marpit]. It has the practical Markdown syntax, advanced features, and official themes. | [![@marp-team/marp-core](https://img.shields.io/npm/v/@marp-team/marp-core.svg?style=flat-square)][marp-core-npm] |
|   <nobr>**[Marp CLI][marp-cli]**</nobr> | A CLI interface for [Marp Core][marp-core] and any Marpit based framework. It can convert Markdown to static HTML / CSS and PDF.    | [![@marp-team/marp-cli](https://img.shields.io/npm/v/@marp-team/marp-cli.svg?style=flat-square)][marp-cli-npm]    |
|   <nobr>**[Marp Web][marp-web]**</nobr> | The main interface of Marp. It can work on the both of online / offline by using [PWA].                                             | [web.marp.app][marp-web-site]<br>(tech demo)                                                                      |
|             <nobr>_Marp Desktop_</nobr> | The desktop client of [Marp Web][marp-web-site] wrapped in [Electron]. It would replace [yhatt/marp], and support local files.      | _(PLANNED)_                                                                                                       |

[yhatt/marp]: https://github.com/yhatt/marp
[marp]: https://github.com/marp-team/marp
[marpit]: https://github.com/marp-team/marpit
[marp-core]: https://github.com/marp-team/marp-core
[marp-cli]: https://github.com/marp-team/marp-cli
[marp-web]: https://github.com/marp-team/marp-web
[pwa]: https://en.wikipedia.org/wiki/Progressive_Web_Apps
[electron]: https://electronjs.org/
[marpit.marp.app]: https://marpit.marp.app/
[marpit-npm]: https://www.npmjs.com/package/@marp-team/marpit
[marp-core-npm]: https://www.npmjs.com/package/@marp-team/marp-core
[marp-cli-npm]: https://www.npmjs.com/package/@marp-team/marp-cli
[marp-web-site]: https://web.marp.app/

## Examples

### Starter

- **[Marp CLI example](https://yhatt-marp-cli-example.netlify.com/)** by [@yhatt](https://github.com/yhatt) - A good starter to write and host Marp slide with [GitPitch](https://gitpitch.com/) style powered by [Netlify](https://www.netlify.com/). (https://github.com/yhatt/marp-cli-example)

### Community

<!-- - **[Slide title](https://example.com/)** by [@username](https://github.com/username) -->

Let us know if you have created an awesome slide deck with Marp ecosystem! [Edit README.md and send pull request.](https://github.com/marp-team/marp/blob/master/README.md)

<!-- NOTE: The slide deck created by yhatt/marp  desktop app cannot add to examples. -->

## Contributing

Marp and sub-projects are following the [contributing guideline of marp-team][contributing] hosted in this repo. Please read this before starting work in our projects.

[contributing]: .github/CONTRIBUTING.md

## Author

Managed by [@marp-team](https://github.com/marp-team).

- <img src="https://github.com/yhatt.png" width="16" height="16"/> Yuki Hattori ([@yhatt](https://github.com/yhatt))

## License

[MIT License](LICENSE)
