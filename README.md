[release-badge]: https://img.shields.io/github/release-pre/ClearVision/v1.svg?style=flat-square
[release-link]: https://github.com/ozgurozgumuss/beecord/releases
[license-badge]: https://img.shields.io/github/license/ClearVision/v6.svg?style=flat-square
[license-link]: https://github.com/ozgurozgumuss/beecord/blob/master/LICENSE
[discord-badge]: https://img.shields.io/discord/212324635356692500.svg?style=flat-square
[discord-link]: https://discord.gg/uvWDD76
[issues-badge]: https://img.shields.io/github/issues/ClearVision/v6.svg?style=flat-square
[issues-link]: https://github.com/ozgurozgumuss/beecord/issues
[prs-badge]: https://img.shields.io/github/issues-pr/ClearVision/v6.svg?style=flat-square
[prs-link]: https://github.com/ozgurozgumuss/beecord/pulls

<div align="center">

# BEECORD V1

[![GitHub release](https://img.shields.io/github/release/Naereen/StrapDown.js.svg)](https://github.com/ozgurozgumuss/beecord/releases/)
[![Generic badge](https://img.shields.io/badge/discord-online-green.svg)](https://discord.gg/uvWDD76)
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/ozgurozgumuss/beecord/blob/master/LICENSE)


![v6 Sapphire](https://github.com/ozgurozgumuss/beecord/raw/master/screenshots/6-stable.4.7.9.png)

</div>

## Installing
Download the theme file and move it into your [BetterDiscord](https://betterdiscord.net) themes folder:

>[Visit for download](https://ozgurozgumuss.github.io/beecord/)

## Building from source
In order build the theme from source you will need [Sass](https://sass-lang.com) & [PostCSS Autoprefixer](https://github.com/postcss/autoprefixer).  
With [npm](https://npmjs.org/get-npm) installed you can simply run `npm install` to install all missing dependencies and compile the theme into the `/public` folder via `npm run build`.

**Dependencies:**
- [node-sass](https://github.com/sass/node-sass)
- [PostCSS Autoprefixer](https://github.com/postcss/autoprefixer)
- [PostCSS CLI](https://github.com/postcss/postcss-cli)
- *[DiscordSelectors](https://github.com/zerthox/discordselectors) (included in the `/lib` folder)*
- *[rimraf](https://github.com/isaacs/rimraf) (for cleanup)*

## Contributing
In order to contribute you need to be able to compile [Sass](https://sass-lang.com).

If you use [Node Sass](https://github.com/sass/node-sass) via CLI, you can run:
```
node-sass main.scss public/main.css --watch
```

If you use [Dart Sass](https://github.com/sass/dart-sass) via CLI, you can run:
```
sass main.scss:public/main.css --watch
```

This will compile the theme into the `/public` folder and watch changes.
