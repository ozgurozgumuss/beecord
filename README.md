[release-badge]: https://img.shields.io/github/v/release/ozgurozgumuss/beecord?label=version&logo=beecord&style=for-the-badge
[release-link]: https://github.com/ozgurozgumuss/beecord/releases
[license-badge]: https://img.shields.io/github/license/ozgurozgumuss/beecord?logo=beecord&style=for-the-badge
[license-link]: https://github.com/ozgurozgumuss/beecord/blob/master/LICENSE
[issues-badge]: https://img.shields.io/github/issues/ozgurozgumuss/beecord?color=yellowgreen&logo=beecord&style=for-the-badge
[issues-link]: https://github.com/ozgurozgumuss/beecord/issues
[discord-badge]: https://img.shields.io/discord/712465159553286187?color=informational&logo=beecord&style=for-the-badge
[discord-link]: https://discord.com/invite/uvWDD76
[prs-badge]: https://img.shields.io/github/issues-pr/ozgurozgumuss/beecord?color=yellow&logo=beecord&style=for-the-badge
[prs-link]: https://github.com/ozgurozgumuss/beecord/pulls

<div align="center">



# BEECORD V1

[![Releases][release-badge]][release-link]
[![License][license-badge]][license-link]
[![Issues][issues-badge]][issues-link]
[![Pull Requests][prs-badge]][prs-link]
[![Discord Server][discord-badge]][discord-link]


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
