<!-- BADGE LINKS -->
[npm]: https://www.npmjs.com/package/axytube.js
[versions]: https://www.npmjs.com/package/axytube.js?activeTab=versions
[codefactor]: https://www.codefactor.io/repository/github/luanrt/youtube.js
[actions]: https://github.com/axynera/axytube/actions
[discord]: https://discord.gg/syDu7Yks54

<div align="center">
  <br/>
  <p>
    <a href="https://github.com/axynera/axytube">
      <img src="https://luanrt.github.io/assets/img/ytjs.svg" alt="Axytube.js Logo" width="200" />
    </a>
  </p>
  <p>A JavaScript client for YouTube's internal API.<br/>Works on Node.js, Deno, modern browsers, and more.</p>

[![Discord](https://img.shields.io/badge/discord-online-brightgreen.svg)][discord]
[![NPM Version](https://img.shields.io/npm/v/axytube.js?color=%2335C757)][versions]
[![Downloads](https://img.shields.io/npm/dt/axytube.js)][npm]
[![Codefactor](https://www.codefactor.io/repository/github/luanrt/youtube.js/badge)][codefactor]

</div>

## Installation

Before installing, make sure your environment meets the [prerequisites](https://ytjs.dev/guide/getting-started.html#prerequisites).

```bash
# NPM
npm install axytube.js@latest

# Yarn
yarn add axytube.js@latest

# Git (edge version)
npm install github:axynera/axytube

# Deno
deno add npm:axytube.js@latest
```

Deno (deprecated):
```ts
import { Innertube } from 'https://deno.land/x/youtubei/deno.ts';
```

## Basic Usage

```ts
import { Innertube } from 'axytube.js';
const innertube = await Innertube.create(/* options */);
```

For detailed usage, read the [Axytube.js Guide and API Documentation](https://ytjs.dev).

## Contributing
All contributions are welcome, big or small. If you want to contribute, take a look at the [issues page](https://github.com/axynera/axytube/issues) and our [guidelines](https://github.com/axynera/axytube/blob/main/CONTRIBUTING.md).

## Contributors
<a href="https://github.com/LuanRT/Axytube.js/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=LuanRT/Axytube.js" />
</a>

## Disclaimer
This project is not affiliated with, endorsed, or sponsored by YouTube or any of its affiliates or subsidiaries. All trademarks, logos, and brand names used in this project are the property of their respective owners and are used solely to describe the services provided.

As such, any usage of trademarks to refer to such services is considered nominative use. If you have any questions or concerns, please contact me.

## License
Distributed under the [MIT](https://choosealicense.com/licenses/mit/) License.

<p align="right">
(<a href="#top">back to top</a>)
</p>
