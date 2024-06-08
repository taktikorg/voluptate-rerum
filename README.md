[node-version-url]: https://github.com/nodejs/node
[bun-version-url]: https://github.com/oven-sh/bun
[deno-version-url]: https://github.com/denoland/deno
[typescript-url]: https://github.com/microsoft/TypeScript
[ci-linux-url]: https://github.com/taktikorg/voluptate-rerum/actions/workflows/ci_coverage-linux.yml?query=branch%3Amain
[ci-linux-image]: https://img.shields.io/github/actions/workflow/status/wellwelwel/@taktikorg/voluptate-rerum/ci_coverage-linux.yml?event=push&style=flat-square&label=&branch=main&logo=ubuntu&logoColor=white
[ci-osx-url]: https://github.com/taktikorg/voluptate-rerum/actions/workflows/ci_coverage-osx.yml?query=branch%3Amain
[ci-osx-image]: https://img.shields.io/github/actions/workflow/status/wellwelwel/@taktikorg/voluptate-rerum/ci_coverage-osx.yml?event=push&style=flat-square&label=&branch=main&logo=apple&logoColor=white
[ci-windows-url]: https://github.com/taktikorg/voluptate-rerum/actions/workflows/ci_coverage-windows.yml?query=branch%3Amain
[ci-windows-image]: https://img.shields.io/github/actions/workflow/status/wellwelwel/@taktikorg/voluptate-rerum/ci_coverage-windows.yml?event=push&style=flat-square&label=&branch=main&logo=windows&logoColor=white
[ql-url]: https://github.com/taktikorg/voluptate-rerum/actions/workflows/ci_codeql.yml?query=branch%3Amain
[ql-image]: https://img.shields.io/github/actions/workflow/status/wellwelwel/@taktikorg/voluptate-rerum/ci_codeql.yml?event=push&style=flat-square&label=&branch=main&logo=github&logoColor=white
[coverage-image]: https://img.shields.io/codecov/c/github/wellwelwel/@taktikorg/voluptate-rerum?style=flat-square&label=Coverage
[coverage-url]: https://app.codecov.io/github/wellwelwel/@taktikorg/voluptate-rerum
[downloads-image]: https://img.shields.io/npm/dt/@taktikorg/voluptate-rerum.svg?style=flat-square&label=Downloads&logo=npm&logoColor=white&color=1e90ff
[downloads-url]: https://www.npmjs.com/package/@taktikorg/voluptate-rerum
[license-url]: https://github.com/taktikorg/voluptate-rerum/blob/main/LICENSE
[license-image]: https://img.shields.io/npm/l/@taktikorg/voluptate-rerum.svg?maxAge=2592000&color=9c88ff&style=flat-square&label=License

<div align="center">
<img width="170" height="170" alt="Logo" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/@taktikorg/voluptate-rerum.svg">

# Poku

**Poku** can show you _how simple testing can be_ 🌱

[![NPM Downloads][downloads-image]][downloads-url]
[![Coverage][coverage-image]][coverage-url]
[![License][license-image]][license-url]<br />
[![GitHub Workflow Status (with event)][ci-linux-image]][ci-linux-url]
[![GitHub Workflow Status (with event)][ci-osx-image]][ci-osx-url]
[![GitHub Workflow Status (with event)][ci-windows-image]][ci-windows-url]

Enjoying **Poku**? Give him a star to show your support ⭐️

</div>

---

## Why does Poku exist?

> **Poku** takes on the testers' difficulties by itself and lets you focus on the tests.

<img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/check.svg"> No configurations<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/check.svg"> Auto detect **ESM** and **CJS**<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/check.svg"> Auto detect **Typescript** files<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/check.svg"> Run the same test suite for [**Node.js**][node-version-url], [**Bun**][bun-version-url] and [**Deno**][deno-version-url]<br />

<img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/check.svg"> Easier and Less Verbose<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/check.svg"> Easily test your server just by running it 🚀<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/check.svg"> Run **CJS** (**CommonJS**) files directly with [**Deno**][deno-version-url]<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/check.svg"> Easily handle **services**, **servers**, **processes** and **ports**<br />

<img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/check.svg"> Safety and Reliability<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/check.svg"> High **isolation** level per file<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/check.svg"> Compatible with **Coverage** tools<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/check.svg"> **Poku** doesn't use `eval` nor global state 🔐<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@taktikorg/voluptate-rerum/main/.github/assets/readme/check.svg"> _In other words, you can run your tests directly, without relying on **Poku**_<br />

---

## Quickstart

### Install

[![Install Size](https://packagephobia.com/badge?p=@taktikorg/voluptate-rerum)](https://packagephobia.com/result?p=@taktikorg/voluptate-rerum)

<table>
<tr>
<td><blockquote><b>Node.js</b</blockquote></td>
<td><blockquote><b>TypeScript + Node.js</b</blockquote></td>
<td><blockquote><b>Bun</b</blockquote></td>
<td><blockquote><b>Deno</b</blockquote></td>
</tr>
<tr>
<td width="400">

```bash
npm i -D @taktikorg/voluptate-rerum
```

</td>
<td width="400">

```bash
npm i -D @taktikorg/voluptate-rerum tsx
```

</td>
<td width="400">

```bash
bun add -d @taktikorg/voluptate-rerum
```

</td>
<td width="400">

```bash
deno add npm:@taktikorg/voluptate-rerum
```

</td>
</tr>
</table>

### Test

<table>
<tr>
<td>
<blockquote>test/file.test.mjs</blockquote>
</td>
</tr>
<tr>
<td width="1200">

```ts
import { assert } from '@taktikorg/voluptate-rerum';

assert(true, 'Poku will describe it 🐷');
```

</td>
</tr>
</table>

### Run

<table>
<tr>
<td><blockquote><b>Node.js (and TypeScript)</b</blockquote></td>
<td><blockquote><b>Bun</b</blockquote></td>
<td><blockquote><b>Deno</b</blockquote></td>
</tr>
<tr>
<td width="400">

```bash
npx @taktikorg/voluptate-rerum
```

</td>
<td width="400">

```bash
bunx @taktikorg/voluptate-rerum
```

</td>
<td width="400">

```bash
deno run npm:@taktikorg/voluptate-rerum
```

</td>
</tr>
</table>

That's it 🎉

---

🐷 [**Documentation**](https://@taktikorg/voluptate-rerum.io)<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>🧪 [**Examples**](https://@taktikorg/voluptate-rerum.io/docs/category/examples)<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>🔬 [**Compare the Most Popular Test Runners**](https://@taktikorg/voluptate-rerum.io/docs/comparing)

---

## Available Methods

### Essentials

- **Test**
  - [**@taktikorg/voluptate-rerum**](https://@taktikorg/voluptate-rerum.io/docs/category/@taktikorg/voluptate-rerum) (_test runner_)
  - [**assert**](https://@taktikorg/voluptate-rerum.io/docs/documentation/assert) (_test assertion_)
- **Background Services**
  - [**startScript**](https://@taktikorg/voluptate-rerum.io/docs/documentation/startScript) (_run `package.json` scripts in a background process_)
  - [**startService**](https://@taktikorg/voluptate-rerum.io/docs/documentation/startService) (_run files in a background process_)
- **Processes**
  - [**kill**](https://@taktikorg/voluptate-rerum.io/docs/documentation/processes/kill) (_terminate Ports, Port Ranges and PIDs_)
  - [**getPIDs**](https://@taktikorg/voluptate-rerum.io/docs/documentation/processes/get-pids) (_get all processes IDs using ports and port ranges_)

### Helpers

- [**beforeEach**](https://@taktikorg/voluptate-rerum.io/docs/category/beforeeach-and-aftereach) and [**afterEach**](https://@taktikorg/voluptate-rerum.io/docs/category/beforeeach-and-aftereach)
- [**test**](https://@taktikorg/voluptate-rerum.io/docs/documentation/helpers/test)
- [**describe**](https://@taktikorg/voluptate-rerum.io/docs/documentation/helpers/describe)
- _and much more_ ✨

---

## Documentation and Examples

To see the detailed documentation, please visit the [**Documentation**](https://@taktikorg/voluptate-rerum.io/docs/category/documentation) and [**Examples**](https://@taktikorg/voluptate-rerum.io/docs/category/examples) sections in the [**Poku**'s website](https://@taktikorg/voluptate-rerum.io).

---

## Contributing

> I'm continuously working to improve **Poku**. If you've got something interesting to share, feel free to submit a [**Pull Request**](https://github.com/taktikorg/voluptate-rerum/compare). If you notice something wrong, I'd appreciate if you'd open an [**Issue**](https://github.com/taktikorg/voluptate-rerum/issues/new).

Please check the [**CONTRIBUTING.md**](./CONTRIBUTING.md) for instructions 🚀

---

## Philosophy

Please check the [**Philosophy**](https://@taktikorg/voluptate-rerum.io/docs/philosophy) section from Documentation.

---

## Security Policy

[![GitHub Workflow Status (with event)][ql-image]][ql-url]

Please check the [**SECURITY.md**](./SECURITY.md) and the section [**Is Poku Safe?**](https://@taktikorg/voluptate-rerum.io/docs/security) from Documentation.

---

## Limitations

- **Poku** community is gradually building up 🤝
- Although it has no external dependencies, **Poku** is not _all-in-one_, so it doesn't have features such as _mocks_ and _spies_, where you can use your favorite packages or native solutions.

---

## License

Poku is under the [**MIT License**](./LICENSE).

---

## Acknowledgements

[![Contributors](https://img.shields.io/github/contributors/wellwelwel/@taktikorg/voluptate-rerum?style=flat-square)](https://github.com/taktikorg/voluptate-rerum/graphs/contributors)

[![Contributors](https://opencollective.com/@taktikorg/voluptate-rerum/contributors.svg?width=890&button=false)](https://github.com/taktikorg/voluptate-rerum/graphs/contributors)
