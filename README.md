# Repolex Knowledge Graph of yaml/pyyaml

RDF knowledge graph data for [yaml/pyyaml](https://github.com/yaml/pyyaml), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download yaml/pyyaml
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 41309b0bcb4559edb1d691d47199035ef539d785
│   │   │   └── chunk-001.nq.gz
│   │   ├── 4808fba18e067a93a4fcc25ddda1aae9b976ceb8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 49790e73684bebad1df05ef8d828fa12f685bffb
│   │   │   └── chunk-001.nq.gz
│   │   ├── 538b5c93f7d5dee40322893c1e524e94a4f8bbde
│   │   │   └── chunk-001.nq.gz
│   │   ├── 539928ea80aa4b24b24ab4cb84805aa3c0d444c8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 58d0cb7ee09954c67fabfbd714c5673b03e7a9e1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5bda41909a4d93062bacaf48df599dbf0cb4cf1e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8cdff2c80573b8be8e8ad28929264a913a63aa33
│   │   │   └── chunk-001.nq.gz
│   │   ├── b79e34b37e676371a6a104970a8a944fb514b679
│   │   │   └── chunk-001.nq.gz
│   │   ├── c42fa3bff1eabdb64763bb1526d9ea1ccb708479
│   │   │   └── chunk-001.nq.gz
│   │   ├── dd9f0e1236775dcce682c91823e009556ce2a271
│   │   │   └── chunk-001.nq.gz
│   │   └── ee37f4653c08fc07aecff69cfd92848e6b1a540e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 41309b0bcb4559edb1d691d47199035ef539d785.nq.gz
│   │   ├── 4808fba18e067a93a4fcc25ddda1aae9b976ceb8.nq.gz
│   │   ├── 49790e73684bebad1df05ef8d828fa12f685bffb.nq.gz
│   │   ├── 538b5c93f7d5dee40322893c1e524e94a4f8bbde.nq.gz
│   │   ├── 539928ea80aa4b24b24ab4cb84805aa3c0d444c8.nq.gz
│   │   ├── 58d0cb7ee09954c67fabfbd714c5673b03e7a9e1.nq.gz
│   │   ├── 5bda41909a4d93062bacaf48df599dbf0cb4cf1e.nq.gz
│   │   ├── 8cdff2c80573b8be8e8ad28929264a913a63aa33.nq.gz
│   │   ├── b79e34b37e676371a6a104970a8a944fb514b679.nq.gz
│   │   ├── c42fa3bff1eabdb64763bb1526d9ea1ccb708479.nq.gz
│   │   ├── dd9f0e1236775dcce682c91823e009556ce2a271.nq.gz
│   │   └── ee37f4653c08fc07aecff69cfd92848e6b1a540e.nq.gz
│   └── repolex
│       ├── 41309b0bcb4559edb1d691d47199035ef539d785
│       │   └── chunk-001.nq.gz
│       ├── 4808fba18e067a93a4fcc25ddda1aae9b976ceb8
│       │   └── chunk-001.nq.gz
│       ├── 49790e73684bebad1df05ef8d828fa12f685bffb
│       │   └── chunk-001.nq.gz
│       ├── 538b5c93f7d5dee40322893c1e524e94a4f8bbde
│       │   └── chunk-001.nq.gz
│       ├── 539928ea80aa4b24b24ab4cb84805aa3c0d444c8
│       │   └── chunk-001.nq.gz
│       ├── 58d0cb7ee09954c67fabfbd714c5673b03e7a9e1
│       │   └── chunk-001.nq.gz
│       ├── 5bda41909a4d93062bacaf48df599dbf0cb4cf1e
│       │   └── chunk-001.nq.gz
│       ├── 8cdff2c80573b8be8e8ad28929264a913a63aa33
│       │   └── chunk-001.nq.gz
│       ├── b79e34b37e676371a6a104970a8a944fb514b679
│       │   └── chunk-001.nq.gz
│       ├── c42fa3bff1eabdb64763bb1526d9ea1ccb708479
│       │   └── chunk-001.nq.gz
│       ├── dd9f0e1236775dcce682c91823e009556ce2a271
│       │   └── chunk-001.nq.gz
│       └── ee37f4653c08fc07aecff69cfd92848e6b1a540e
│           └── chunk-001.nq.gz
└── blob
    ├── 00688696d9ddd6744d74be8addb745eca1ae4eb0.nq.gz
    ├── 00c97236d809e9f9e33e98c70fd98e9549d5504a.nq.gz
    ├── 00ce069c6f896d8a7d42af6c9ec24b364c7f9d47.nq.gz
    ├── 013896d2f10619e0e75d2579cd63220338a7fef1.nq.gz
    ├── 0168441770dc068e31a2343f249be0be8306da45.nq.gz
    ├── 016fb640aef84f982edfe8d86cb0f30c50a3701d.nq.gz
    ├── 020e6db88b7c5f71711f852527a06064b27db20c.nq.gz
    ├── 021635f30e72a8910438ccce0a66354faf5eaf48.nq.gz
    ├── 022446df466be658ef72b6c3a1c453078880c153.nq.gz
    ├── 02b82e73eecac9875336617a7ff38300ff4507ef.nq.gz
    ├── 02d4d377832dd40cbf45d3bfbb87d48c9aeadb95.nq.gz
    ├── 02d8411920ef2f4db6cf955002d4f59c2c3dba58.nq.gz
    ├── 03687b02d41c39b85d8911fd94d80d891aa1b2c2.nq.gz
    ├── 039c3857d22bb1901064856d78a6d1e49189095f.nq.gz
    ├── 04bcffc82f522905cc0629a183abae01de1a9862.nq.gz
    ├── 04c57985b710a2cca4793bbb7d77a883cecd0cbf.nq.gz
    ├── 04ebf691b566df202dd2315dacf7a014410f86bf.nq.gz
    ├── 05e102d8ebd4dc9febdfcdd8b8ae0a626909a7ad.nq.gz
    ├── 05f55b942606f094f5638b66e100008ed54e6692.nq.gz
    ├── 06307e06a1d3e1a7624f5ffb5bd06169b2f23e45.nq.gz
    ├── 06abdb5f66a4a15d018c5a50f02bbdb4415982f4.nq.gz
    ├── 06c033e634f04f6364e40d34fc9e229468b1ce9b.nq.gz
    ├── 06c7f0e47b48fa6e60ae3cf05be29fdb88b60425.nq.gz
    ├── 0783a21b1d28ea6935b377913ca16d6e325ff0d3.nq.gz
    ├── 07b15009842bc6fef1527f0ee3382f3789380af2.nq.gz
    ├── 07cc0c9879b134ac49853591f608e65ba4c10538.nq.gz
    ├── 08042c81592a472cdce86b18113ebced3ab9a23d.nq.gz
    ├── 08072d2fa69d5dfd9c49d33d300d98bd69c96cf5.nq.gz
    ├── 08074ea52669e4fc9ce6b4097a7c255d908bc752.nq.gz
    ├── 0823f7494bea13b6e939fd3ee694374f532828b8.nq.gz
    ├── 0835b6649924d31bfe5cb6ba9e40f0ee0f346fad.nq.gz
    ├── 0888b05422222ff406a23f65285ea5b98ac64325.nq.gz
    ├── 0892eb66dde8b79c1892f427cc30617fa596fa26.nq.gz
    ├── 0980789a97cc34b47cc71a315148ead84c9bde3b.nq.gz
    ├── 0988b63102cd9798152dcc9189b0e2ce2f0fb26d.nq.gz
    ├── 098bacbe98dfad235ea80a187cd7239b4354c3e7.nq.gz
    ├── 098ea7be82b43706c520c4fa956cfdd7aee1f4f1.nq.gz
    ├── 09eea2ed305b2ee7637195dfebfea0b0406b8719.nq.gz
    ├── 09fecb8efa60e77f4edb1e098cf112bc203068d2.nq.gz
    ├── 0a58c70f5110d1fc00f39fbae6b1306ac815a116.nq.gz
    ├── 0b40e61b71e7c0d4ddcc5d5ea5632a825c9915ae.nq.gz
    ├── 0bf1e96dc1623b34d69df91c8a93ef8a273d9430.nq.gz
    ├── 0c21345879b298bb8668201bebe7d289586b17f9.nq.gz
    ├── 0c5cda186dc8f217e04be9ca221e318a61db918a.nq.gz
    ├── 0c90c05dff9262ee3040e0804df9245fdf693e31.nq.gz
    ├── 0ca49912bed281bc3c30a7098f41dcd828896203.nq.gz
    ├── 0ca95142bb715442d0c2c82a7c573a08c4593845.nq.gz
    ├── 0cb482c9e08efc43be7016e3cf03eeea5f0bc356.nq.gz
    ├── 0cbab899532f08432c23a288da4e78f16579f732.nq.gz
    ├── 0cd90a2bd15bbc378bc6e99d60621ac9d55cf7a7.nq.gz
    ├── 0d6080494209b176582c0560dc5c5e022046dc0e.nq.gz
    ├── 0d93013b5d9bc6f12af11848a4ce124d33317bb4.nq.gz
    ├── 0dd51eb38ab73b481ae4bdda240d25a166c213fa.nq.gz
    ├── 0e414495f39246bcdf92f58bdca5c632acf17745.nq.gz
    ├── 0fdd14f2c72ea0d8addf0d308420e0e79ab3e476.nq.gz
    ├── 1058f7b0f070032fc4a21899fbcc39a9a3cf328a.nq.gz
    ├── 10d4a8fcb320cae1f566dbd1c154c49304504fc2.nq.gz
    ├── 11357e453fa3ff9fff0d29ccd1cca75b7bc27c28.nq.gz
    ├── 1180757d81cb6c1149dc3ac2838518d0ca86b39f.nq.gz
    ├── 118d5e358e8910cafc4f096fe46e8853e4be3a19.nq.gz
    ├── 11db439f6a0a5c66b6e299c7ff60b96ab04c50e5.nq.gz
    ├── 11eef3bb378fc0cf2ba72fcb89d62bbbdbf7699d.nq.gz
    ├── 1209d47b34657f63711c69ebd5f9349c451e09e0.nq.gz
    ├── 1263d96f8955c593911e1cca28bdc44daf67abb4.nq.gz
    ├── 12e95b14f8ae96882ca22b635ea5a21f01878849.nq.gz
    ├── 12f48c1774daa524b6ca96f2f84ba820ec825d64.nq.gz
    ├── 130cfa74199dd0699bcc359e7ecdfbce7686f2aa.nq.gz
    ├── 1379ca506d8f92dfcf40b71fc4cea8ba8727c0b6.nq.gz
    ├── 13a5995d292045d0f865a99abf692bd35dc87814.nq.gz
    ├── 13d687c501c854057404469446c680231fbc92e5.nq.gz
    ├── 13fb656010274a38022eb6ecc2eb80d854cbe0e3.nq.gz
    ├── 1443395b53d371760159d62b89481db5d63bbb1d.nq.gz
    ├── 153fd889aedf00190c419b17b94ff7f65d36aa50.nq.gz
    ├── 160d8e47f48c43490b07f3e2705c47d1c3f8ec76.nq.gz
    ├── 1672d0d93b497e3ef89a1c6acbbe97960120d861.nq.gz
    ├── 16a6db1833cbc211f57ac048f5d8ded966c2eb9e.nq.gz
    ├── 170da01331ed3ecbedc5510cff0887b5440443fa.nq.gz
    ├── 171facec1f7d4e9d1f3c06bb453b241fba6238a5.nq.gz
    ├── 17a6285bf33a3a4eb6d47cce251319e3cacab4d8.nq.gz
    ├── 17ebad46336af43d7fb261a9b80a1887421c7283.nq.gz
    ├── 185e7807b06000e09a1500b25735d2d21191975b.nq.gz
    ├── 18e16e38c5de68635347d560e655fada9acc0fab.nq.gz
    ├── 190a18037c64c43e6b11489df4bf0b9eb6d2c9bf.nq.gz
    ├── 19110c7c5710a86867b50cee62918ddfa4151488.nq.gz
    ├── 1948b125c205261864156b18178c1af3f535ad76.nq.gz
    ├── 1966f6a2550411f298dbf5c4c659b12e8fe79d28.nq.gz
    ├── 1a1bbdeb3a10eb53807c0fb3bd8599dd19696390.nq.gz
    ├── 1c0bcddd7d21323f343329e63c2e5b6d16665c1d.nq.gz
    ├── 1d4897ffdddfcff7121e46047dbd4fc2d75b7464.nq.gz
    ├── 1db650a810b3eddd11b45f78641abe2052ad0988.nq.gz
    ├── 1df36161b02ffb32eece8aacaa8bb02c8fbf17e7.nq.gz
    ├── 1e12343bb5c0a078f96ce3c9701a6749bd91650a.nq.gz
    ├── 1e606c74b9470c3ea0db4bd66629af45d28c2b9a.nq.gz
    ├── 1ea921cf8d07f306d9f5259b37f6172e3e2e9878.nq.gz
    ├── 1fc33f9d7720746e8b1e9fac4063e138395f2755.nq.gz
    ├── 2013936a4a4be13de3b2a223bc90ed9fedbce09d.nq.gz
    ├── 2028d04459f30847b48766738f8a94befb9602b8.nq.gz
    ├── 20ced9883cfc814cf172c5f6412a6c73397e164a.nq.gz
    ├── 2113eb610ae8213581a28a8360ffba7cef975ec9.nq.gz
    ├── 211fc8665ec7856d9844acfadaf0031504d6dad7.nq.gz
    ├── 21fd6a991b31b808d198fcd5d84be9ed4bade7ea.nq.gz
    ├── 235c8998b09f96370ab20fbc7d9bfed33014913f.nq.gz
    ├── 23c25ca80af7e9e555299fe39668aaf84bbe114c.nq.gz
    ├── 245f4a141d03b3350b8727c2e0c55efcb2271a74.nq.gz
    ├── 24cff73d9a3778c9d8c32e12fd8dc176e4b63400.nq.gz
    ├── 24d105286020af9e8efe2318bc8a73c6d33af5ba.nq.gz
    ├── 2553a4f329b6cb4f98b89559d5241c5d0514dde5.nq.gz
    ├── 25de5d27f7ced4dab9a7243fd099093de6975719.nq.gz
    ├── 25fac24e62b9f4f95b277e0208e4b94933851e23.nq.gz
    ├── 264df0dfe3f00603ff59d2164adbd924abd16aee.nq.gz
    ├── 266dc6da76bb4753ea7f209b95416401fb65fa50.nq.gz
    ├── 26caa2b198b9a4433fafb47be59596f6c22219c4.nq.gz
    ├── 2793ac7f7309a353122fbedf6e8b2ed9936f25a9.nq.gz
    ├── 27a4ae502854adcc225478a7a5a256ea967b9510.nq.gz
    ├── 27e11bfaf7efd1837607a85bf89975d7acf6efff.nq.gz
    ├── 28633926e16f1c9ecfbbb3e3235b8e322227aca8.nq.gz
    ├── 288000914a147241238bbbb156e94d4d2c2ff6a8.nq.gz
    ├── 28a6cf13f70296ae8b453c96bc190cafeebfa5a7.nq.gz
    ├── 28edc3c6df3aa6dcf3ac106b09c112377d879bc8.nq.gz
    ├── 2905b0d9d093ee5a3c048c2d9b630be9c250b639.nq.gz
    ├── 29326dbb2bd6f73ddf4077c503f156c7cea4fcf1.nq.gz
    ├── 2a4f50d9846a5761ca7f5cb3802f5b8c3fbb78d3.nq.gz
    ├── 2a5df00dfa5c8266a559d971b9f86a9f54b4b0e8.nq.gz
    ├── 2bf5ec8096be861930092d5f2f0188c6663e2913.nq.gz
    ├── 2d36d0e0a254c1ffd9b2901682b958d6a48018ad.nq.gz
    ├── 2d5f0639f0135e787a568e49757bc2b0663cc775.nq.gz
    ├── 2d78a6195dc88b14d9a574af06aa7f4cf79e6ea8.nq.gz
    ├── 2dadafc1002b3bf98189a6f44890b5efa41c8e1f.nq.gz
    ├── 2dc1c25da3ccc74fd7724794a377c07fa510a8f1.nq.gz
    ├── 2eb4f5a57f437a5db994eebc27e72479e06570b0.nq.gz
    ├── 2ec4f203c7e12941ff807c9def9e35b9ae1ab2bd.nq.gz
    ├── 2f1b8e15e5627d92f0521605c9870bc8e5505cb4.nq.gz
    ├── 2f62d082375ff43b449de887667c90586905b1c8.nq.gz
    ├── 2fbb1f70c9a2f10de82c08e0754301c1fcc19629.nq.gz
    ├── 3029a11629516a8110c130561f622bba92ff38ba.nq.gz
    ├── 30bfc3f8537c20df10ec889c4c373aa045a11dab.nq.gz
    ├── 312204ead76a334eb38e18ec5d34b84cbad12244.nq.gz
    ├── 31354ec1389994b5f6708c7d915fdcc6bb76ba6e.nq.gz
    ├── 31389eaeb247283ffaf0986c92e8745da9f87eab.nq.gz
    ├── 313a91b424598d8f2178dfc61191aae84f6c281a.nq.gz
    ├── 3143763dd0971a146f57ce459dae1b033b389fb7.nq.gz
    ├── 32423c1b1af6af6054fe0887d94ef11b1d31ed0b.nq.gz
    ├── 32c40f465d37212418911365805a132f8242e49f.nq.gz
    ├── 32d9e943e7be83a87b2f65867282eb007350c376.nq.gz
    ├── 345e7842d4a32cd4927f28e0a0ff2bcb49653ba1.nq.gz
    ├── 34a1d401105296ff703ac0c3f828f1afadec1dd8.nq.gz
    ├── 3522bdaaf6358110b608f4e6503b9d314c82d887.nq.gz
    ├── 35250629082adcbcf3224ca03148eec3f599f222.nq.gz
    ├── 352cd8d152a76b9ab602c23df84972e8841d641c.nq.gz
    ├── 3576ae6d094965769ebcd44518620ff0f62d0b03.nq.gz
    ├── 36ceca3ee005634ce70366d50f439992c4d4da5e.nq.gz
    ├── 36d6519b6ba0348c5bd4b426eba1b1d726e1862c.nq.gz
    ├── 3732a06a34aac540bcf31b7d0e700eb88bfe38ff.nq.gz
    ├── 37613f5b52c74537bb1e2e1cd7c95bcb97630bf6.nq.gz
    ├── 3805daf01d44d204a9d04406fabd21953c256b60.nq.gz
    ├── 3807d57da1bc26afec1a20375fc47c9892c8737a.nq.gz
    ├── 384c62f0d0b44fbc2236d9aafe52624f17933e27.nq.gz
    ├── 3979e1f79349a6cbd3f7b3bff13ef7dcf49ed19f.nq.gz
    ├── 399eb177b6e6d1ee1e727f8a7d426dd146c6812b.nq.gz
    ├── 39bee044bc0595769b62fccd4c182df64674b81a.nq.gz
    ├── 3a0647b3f770bf64a586850f99a5cac02cb78496.nq.gz
    ├── 3a36700a450d17b4f4ea947f6ca3bdf9b8ff2ddc.nq.gz
    ├── 3ab0c4f460d3de0ef6453305281be894dc2bc63f.nq.gz
    └── 3b0b192ef32ed7f5b7015456fe883c3327bb841e.nq.gz

30 directories, 200 files
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

## Source repository

[yaml/pyyaml](https://github.com/yaml/pyyaml)

---
*Parsed on 2026-09-19 by [repolex](https://repolex.ai)*
