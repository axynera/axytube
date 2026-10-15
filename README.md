<!-- BADGE LINKS -->
[npm]: https://www.npmjs.com/package/axytube.js
[versions]: https://www.npmjs.com/package/axytube.js?activeTab=versions
[actions]: https://github.com/axynera/axytube/actions
[discord]: https://discord.gg/syDu7Yks54

<div align="center">

# Axytube.js

<p>Axynera's JavaScript client for YouTube's InnerTube API, built for Node.js, Deno, browsers, and other supported JavaScript runtimes.</p>

[![Discord](https://img.shields.io/badge/discord-online-brightgreen.svg)][discord]
[![NPM Version](https://img.shields.io/npm/v/axytube.js?color=%2335C757)][versions]
[![Downloads](https://img.shields.io/npm/dt/axytube.js)][npm]

</div>

## Installation

Requirements: a supported JavaScript runtime and a package manager. See the [local API reference](./docs/api/README.md) for exported APIs.

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

## Basic Usage

```ts
import { Axytube, UniversalCache } from 'axytube.js';

const axytube = await Axytube.create({
  cache: new UniversalCache(true)
});
```

For detailed API information, start with the [Axytube.js API reference](./docs/api/README.md).

## Contributing
All contributions are welcome, big or small. If you want to contribute, take a look at the [issues page](https://github.com/axynera/axytube/issues) and our [guidelines](https://github.com/axynera/axytube/blob/main/CONTRIBUTING.md).

## Contributors
<a href="https://github.com/axynera/axytube/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=axynera/axytube" />
</a>

## Upstream attribution

Axytube.js is derived from [YouTube.js](https://github.com/LuanRT/YouTube.js), originally created by LuanRT and contributors. The public `Innertube` export remains available for compatibility; `Axytube` is an additional branded alias.

## Disclaimer
This project is not affiliated with, endorsed, or sponsored by YouTube or any of its affiliates or subsidiaries. All trademarks, logos, and brand names used in this project are the property of their respective owners and are used solely to describe the services provided.

As such, any usage of trademarks to refer to such services is considered nominative use. If you have any questions or concerns, please contact me.

## License

Axytube.js uses the **Axynera License, Version 1.0** for original code and materials owned by Axynera. Unless Axynera grants prior written permission, commercial use and redistribution of Axynera-owned materials are not permitted. Attribution and copyright notices must not be removed or misrepresented. If distribution of a modified Axynera-owned version is authorized in writing, the corresponding modified source must be made available under the Axynera License unless otherwise agreed in writing.

**Important third-party notice:** This repository is derived from YouTube.js by LuanRT. Code inherited from YouTube.js remains covered by its original **MIT License**; the Axynera License does not revoke or restrict rights granted under that license. Keep the applicable MIT copyright and license notice with copies or substantial portions of that upstream code. Other third-party files may be subject to their own licenses.

See [LICENSE](./LICENSE) for the complete Axynera License and the preserved upstream MIT terms. The Axynera License is a custom license and is not an OSI-approved open-source license; permissions and restrictions may require legal review before publication.

<p align="right">
(<a href="#top">back to top</a>)
</p>
