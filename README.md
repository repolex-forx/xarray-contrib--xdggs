# Repolex Knowledge Graph of xarray-contrib/xdggs

RDF knowledge graph data for [xarray-contrib/xdggs](https://github.com/xarray-contrib/xdggs), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download xarray-contrib/xdggs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2995840a620a39a3c15bae40972c950316d29342
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2995840a620a39a3c15bae40972c950316d29342
│           └── chunk-001.nq.gz
├── blob
│   ├── 02e13e05f6ba8a6693a53876cfcca1c6ad7f68d9.nq.gz
│   ├── 0a63b7fbc4126c5762bac5fdb88b704deabb9f3e.nq.gz
│   ├── 0e7a6634335b99927ba158fa81cdbdaf3f1b94e3.nq.gz
│   ├── 0ec4c33a42165c01c4b5903ebf53eb2d4b38e08e.nq.gz
│   ├── 0fa8ea2017eedb7ba5577ae81443849a33ff045a.nq.gz
│   ├── 11706f559a3eb9d285194cc9ae9e3244334966d6.nq.gz
│   ├── 11e645989f828eac58a0b6e07cf99d367cc871b4.nq.gz
│   ├── 14e904b3f59b3d3a0bdb851bcfd0331ffd4cdc08.nq.gz
│   ├── 158c5563c58f840a5125e8a8896a5a24daa92837.nq.gz
│   ├── 17af35f00d0a0777deb4b332f9517ae705c5d077.nq.gz
│   ├── 19169665b88011937823dc59210f3734c2b2b381.nq.gz
│   ├── 1c4eb3883ed0a42b8c56b416448c2f83952eafd4.nq.gz
│   ├── 1d5c7115e96db79c346a76889dd392c35616c8af.nq.gz
│   ├── 1e6301dc0e4dc20dce20bc28045148bd6f36f3a7.nq.gz
│   ├── 1f851360768556c52338d516bf62173fa83239da.nq.gz
│   ├── 2083e48264e9300cf18ad65b1cba41c58510d193.nq.gz
│   ├── 20daa081d426f546f50716dc6f3afca40c404d71.nq.gz
│   ├── 21c9d81dbc868f238c4a3bb144ebabe18ef67907.nq.gz
│   ├── 22a3b8a6d7462ec10b97ff89ae00563d7cea0291.nq.gz
│   ├── 23244a08cb2e787b92799a3a1b2ba60a6a9b4e0e.nq.gz
│   ├── 246be8de4b8ccb8e07e0c43a805cc5c8de699504.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 279f5208c8ee3b4829b47f29e487b28420c45323.nq.gz
│   ├── 2c1e4b04930e696127ac8e36546d88a4f8309bac.nq.gz
│   ├── 2e859fac9cb60b185677b8e783af9996b1acaaa9.nq.gz
│   ├── 337b4e08c5296c45626e884d42b359a03d819b55.nq.gz
│   ├── 35d846c91105cad515005aaf9991beefb24b8752.nq.gz
│   ├── 38ac9f8c3fea4d168d8664619b5f90ddf6c21696.nq.gz
│   ├── 3980d9c07957191bf4c793e335f9592e5dff1ed8.nq.gz
│   ├── 3db54fac05ff1eddc2160b29053329b64a126f73.nq.gz
│   ├── 473669845552d57eb628f00e28201bb92519f207.nq.gz
│   ├── 481a80f5164d8f93eb22989259fa260ff1ce1d7d.nq.gz
│   ├── 4c0349589afc88eb83b95981bccc2de774af66a8.nq.gz
│   ├── 5052f88f222353a9ef6f6c9496b7819a1da375f3.nq.gz
│   ├── 51bd7698465dc95f9319beef912e45140c71f152.nq.gz
│   ├── 5213d7d5a6f066973a1e87237786e4f5875ad6a5.nq.gz
│   ├── 54b683e3eb9eea4dd23f2913ab09da7df1c43618.nq.gz
│   ├── 5716ae1c6ca022611b05a2bc3d76337b7ebdec28.nq.gz
│   ├── 5823941fd68b8f95b743cb294968bb574f4a1f73.nq.gz
│   ├── 5b956ccfa704199a13b404826f5191c9a812fd94.nq.gz
│   ├── 5bd4d87c4fca45dd22fbc206588612c4e304fb97.nq.gz
│   ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
│   ├── 6133e2328ac526bed82a1f8f5dc101edc7ddc817.nq.gz
│   ├── 6317224a7b29b75f83224936f632196a8c64594f.nq.gz
│   ├── 64de0ee3bad22b6f5aa951f629254319affe8a5f.nq.gz
│   ├── 65ea5732bdf3d87a020faa221be69eddf40ad5e9.nq.gz
│   ├── 6619a7ca9fae0d0f7a259554bf26f4a536aabe33.nq.gz
│   ├── 66a7a47329cc063378e3a4af7cad80c417538fe6.nq.gz
│   ├── 68fd3397660c7fa7af00df506399828a9362663c.nq.gz
│   ├── 6f23fa9913418c386d2a378cd8dcec1a10d4e823.nq.gz
│   ├── 71ecf405e23998a26fe506028d66269e2afc0984.nq.gz
│   ├── 74bd0123cdaecde6335b1d081f7b00f1fc8f22d8.nq.gz
│   ├── 75dd061d6856292534ecfcc2fe84ddc57a69cc96.nq.gz
│   ├── 7664d414b28ef91c7baffbd161cfe04f1222fcbe.nq.gz
│   ├── 7c7a882bbb16ede8311551380d5c875215ef3e6a.nq.gz
│   ├── 7d82c65b86434981547bac182cfedc627af75a4f.nq.gz
│   ├── 81e2181e63d7367037ba2d1c7ea2e522c9f2a0e3.nq.gz
│   ├── 880aeb91a9cb77feae68fa29a00bbb5fd03c8aa3.nq.gz
│   ├── 887a2c18f01df0784f690be728f22c1f9d1fa5c4.nq.gz
│   ├── 8a9777468e3a0fa87c140678d9a230aef0b769e3.nq.gz
│   ├── 8aef6e2d8dc1c204aff34a4e9e4264fff543699a.nq.gz
│   ├── 8d32f1aac6a4bd7b097f0a624638182ba0e4d116.nq.gz
│   ├── 8d7807d0ca469076768f1bf7c4444ca2f2ce8ef2.nq.gz
│   ├── 94de92465c89c9d2811fc1c6687a24a0cb544b26.nq.gz
│   ├── 9a6494f516db8b1102af887895bf7704bce9525a.nq.gz
│   ├── 9aae558f3144c1051ccdfa65cbefc0857130f647.nq.gz
│   ├── 9aca49cb37161287dd35f1a81eb958435621a89d.nq.gz
│   ├── 9b3af9220ade3b00376cbbceaefcd6fae7207a15.nq.gz
│   ├── 9d5280b935a1cde1129b27cfb71462363d14bd14.nq.gz
│   ├── 9dd984050b691d163ac1d1c8ccf13d0c8088dff7.nq.gz
│   ├── 9e0634d6fb4b6f1e32d05cfbb7777e027934223d.nq.gz
│   ├── 9f45b0961c21327498cc571eb525ea1473a5cff0.nq.gz
│   ├── a00dd4f4ff6095fc684a7bd2f568c543f8eff99e.nq.gz
│   ├── a82632b213c893322fc522888fc63dc3cb3a074f.nq.gz
│   ├── a93ef5f0d049cdf4a66d2d027bfee96d0cc695a2.nq.gz
│   ├── af71182ece5892ab4bedec91e51497ea9b2f6f00.nq.gz
│   ├── b767bc4707b1be3723072f69c84794a0ea04c772.nq.gz
│   ├── bae1acb37937e1bc4abc4de38dca76c42c7904bf.nq.gz
│   ├── bf6bd2e57ed6ffe393fd7037e13ccbee0edafd60.nq.gz
│   ├── c2f7f55f3c6e9fca531fa9145603f0a81138029d.nq.gz
│   ├── c35b1480c62857e5f268847f329d41e655c2e7f8.nq.gz
│   ├── c598f599fee3e31b41d61aea350ebfeab19fbb1b.nq.gz
│   ├── c70de2235a6c8e2cd1d5eeefc0435fe685e38a83.nq.gz
│   ├── cf39eaed64d2209c5fc8f704db39690332fbb7da.nq.gz
│   ├── d45bdc07d255e508802622a4f1d32534bd9362ec.nq.gz
│   ├── d793c8513df183a4c2522f80923f69a97ae28208.nq.gz
│   ├── d8fbaf7591c0e7e08d4c008f94f38a6cb3d067e1.nq.gz
│   ├── e23b658b17ed8b48dcaad80061c45111e2af766b.nq.gz
│   ├── e9a0276f5e7c46baacba0893081585cc2c81d365.nq.gz
│   ├── eb90cff4ba50dcf7b478169d0de3504fa6424852.nq.gz
│   ├── f05762a77b3834b8751c3758452536ccfdedf03f.nq.gz
│   ├── f0e0f95b45c61c60585dcceb7a9710aca00e79b1.nq.gz
│   ├── f74e21e8f50077a82d69431a6fce156ac0504907.nq.gz
│   ├── f95777068e5841a493f688f051bc3fc2674b1b5c.nq.gz
│   ├── ffd14bd3df6f1b6af1f34ae3d47e2ef820e7da2d.nq.gz
│   └── ffd8bf450ba8906ddd19ea3fe76ba158bd3cdae2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2995840a620a39a3c15bae40972c950316d29342.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 104 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[xarray-contrib/xdggs](https://github.com/xarray-contrib/xdggs)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
