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
│   │   ├── 0f64cbfa54b0b22dc7b776b7b98a7cd657e84d78
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2eed9c7679251298c5d604cd96d232f285c979fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2f463cf5b0e98a52bc20e348d1e69761bf263b86
│   │   │   └── chunk-001.nq.gz
│   │   ├── 38cb7e2e6b803a534bd28d06132c93243d0761a8
│   │   │   └── chunk-001.nq.gz
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
│   │   ├── 5986257f9fc978d4a61b6e0001df554f80e565cb
│   │   │   └── chunk-001.nq.gz
│   │   ├── 5bda41909a4d93062bacaf48df599dbf0cb4cf1e
│   │   │   └── chunk-001.nq.gz
│   │   ├── 62a4eddf315b97a9445bb59cff9727ca2e5970fe
│   │   │   └── chunk-001.nq.gz
│   │   ├── 69b025a9f32fd864ed2096a444a718b7492eb892
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8424b5861467d0e98391799b3db21530bf9eba97
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8cdff2c80573b8be8e8ad28929264a913a63aa33
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8da04ac09699b073da649c4c899172e2968c12c1
│   │   │   └── chunk-001.nq.gz
│   │   ├── a204d840220a044ce782b5b5906d150dc053de0c
│   │   │   └── chunk-001.nq.gz
│   │   ├── a5c2a043a26a6bf2787870eec9006b96ba6bca91
│   │   │   └── chunk-001.nq.gz
│   │   ├── a94428474424e75e438959b7ad9c0a396dece038
│   │   │   └── chunk-001.nq.gz
│   │   ├── a9b98a3daa43d43afd8051b014d5b4154d141913
│   │   │   └── chunk-001.nq.gz
│   │   ├── b79e34b37e676371a6a104970a8a944fb514b679
│   │   │   └── chunk-001.nq.gz
│   │   ├── c42fa3bff1eabdb64763bb1526d9ea1ccb708479
│   │   │   └── chunk-001.nq.gz
│   │   ├── d3eb7daf88e29bc20ffd4cfb833da3c49c617625
│   │   │   └── chunk-001.nq.gz
│   │   ├── dd9f0e1236775dcce682c91823e009556ce2a271
│   │   │   └── chunk-001.nq.gz
│   │   ├── e471e86bf6dabdad45a1438c20a4a5c033eb9034
│   │   │   └── chunk-001.nq.gz
│   │   ├── ee37f4653c08fc07aecff69cfd92848e6b1a540e
│   │   │   └── chunk-001.nq.gz
│   │   ├── f2092f4803a149b1feeee6558ab0a0088a8e577b
│   │   │   └── chunk-001.nq.gz
│   │   └── f813bc00f5d0f6f42984edd89ca11f4b5245d5e7
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0f64cbfa54b0b22dc7b776b7b98a7cd657e84d78.nq.gz
│   │   ├── 2eed9c7679251298c5d604cd96d232f285c979fa.nq.gz
│   │   ├── 2f463cf5b0e98a52bc20e348d1e69761bf263b86.nq.gz
│   │   ├── 38cb7e2e6b803a534bd28d06132c93243d0761a8.nq.gz
│   │   ├── 41309b0bcb4559edb1d691d47199035ef539d785.nq.gz
│   │   ├── 4808fba18e067a93a4fcc25ddda1aae9b976ceb8.nq.gz
│   │   ├── 49790e73684bebad1df05ef8d828fa12f685bffb.nq.gz
│   │   ├── 538b5c93f7d5dee40322893c1e524e94a4f8bbde.nq.gz
│   │   ├── 539928ea80aa4b24b24ab4cb84805aa3c0d444c8.nq.gz
│   │   ├── 58d0cb7ee09954c67fabfbd714c5673b03e7a9e1.nq.gz
│   │   ├── 5986257f9fc978d4a61b6e0001df554f80e565cb.nq.gz
│   │   ├── 5bda41909a4d93062bacaf48df599dbf0cb4cf1e.nq.gz
│   │   ├── 62a4eddf315b97a9445bb59cff9727ca2e5970fe.nq.gz
│   │   ├── 69b025a9f32fd864ed2096a444a718b7492eb892.nq.gz
│   │   ├── 8424b5861467d0e98391799b3db21530bf9eba97.nq.gz
│   │   ├── 8cdff2c80573b8be8e8ad28929264a913a63aa33.nq.gz
│   │   ├── 8da04ac09699b073da649c4c899172e2968c12c1.nq.gz
│   │   ├── a204d840220a044ce782b5b5906d150dc053de0c.nq.gz
│   │   ├── a5c2a043a26a6bf2787870eec9006b96ba6bca91.nq.gz
│   │   ├── a94428474424e75e438959b7ad9c0a396dece038.nq.gz
│   │   ├── a9b98a3daa43d43afd8051b014d5b4154d141913.nq.gz
│   │   ├── b79e34b37e676371a6a104970a8a944fb514b679.nq.gz
│   │   ├── c42fa3bff1eabdb64763bb1526d9ea1ccb708479.nq.gz
│   │   ├── d3eb7daf88e29bc20ffd4cfb833da3c49c617625.nq.gz
│   │   ├── dd9f0e1236775dcce682c91823e009556ce2a271.nq.gz
│   │   ├── e471e86bf6dabdad45a1438c20a4a5c033eb9034.nq.gz
│   │   ├── ee37f4653c08fc07aecff69cfd92848e6b1a540e.nq.gz
│   │   ├── f2092f4803a149b1feeee6558ab0a0088a8e577b.nq.gz
│   │   └── f813bc00f5d0f6f42984edd89ca11f4b5245d5e7.nq.gz
│   └── repolex
│       ├── 0f64cbfa54b0b22dc7b776b7b98a7cd657e84d78
│       │   └── chunk-001.nq.gz
│       ├── 2eed9c7679251298c5d604cd96d232f285c979fa
│       │   └── chunk-001.nq.gz
│       ├── 2f463cf5b0e98a52bc20e348d1e69761bf263b86
│       │   └── chunk-001.nq.gz
│       ├── 38cb7e2e6b803a534bd28d06132c93243d0761a8
│       │   └── chunk-001.nq.gz
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
│       ├── 5986257f9fc978d4a61b6e0001df554f80e565cb
│       │   └── chunk-001.nq.gz
│       ├── 5bda41909a4d93062bacaf48df599dbf0cb4cf1e
│       │   └── chunk-001.nq.gz
│       ├── 62a4eddf315b97a9445bb59cff9727ca2e5970fe
│       │   └── chunk-001.nq.gz
│       ├── 69b025a9f32fd864ed2096a444a718b7492eb892
│       │   └── chunk-001.nq.gz
│       ├── 8424b5861467d0e98391799b3db21530bf9eba97
│       │   └── chunk-001.nq.gz
│       ├── 8cdff2c80573b8be8e8ad28929264a913a63aa33
│       │   └── chunk-001.nq.gz
│       ├── 8da04ac09699b073da649c4c899172e2968c12c1
│       │   └── chunk-001.nq.gz
│       ├── a204d840220a044ce782b5b5906d150dc053de0c
│       │   └── chunk-001.nq.gz
│       ├── a5c2a043a26a6bf2787870eec9006b96ba6bca91
│       │   └── chunk-001.nq.gz
│       ├── a94428474424e75e438959b7ad9c0a396dece038
│       │   └── chunk-001.nq.gz
│       ├── a9b98a3daa43d43afd8051b014d5b4154d141913
│       │   └── chunk-001.nq.gz
│       ├── b79e34b37e676371a6a104970a8a944fb514b679
│       │   └── chunk-001.nq.gz
│       ├── c42fa3bff1eabdb64763bb1526d9ea1ccb708479
│       │   └── chunk-001.nq.gz
│       ├── d3eb7daf88e29bc20ffd4cfb833da3c49c617625
│       │   └── chunk-001.nq.gz
│       ├── dd9f0e1236775dcce682c91823e009556ce2a271
│       │   └── chunk-001.nq.gz
│       ├── e471e86bf6dabdad45a1438c20a4a5c033eb9034
│       │   └── chunk-001.nq.gz
│       ├── ee37f4653c08fc07aecff69cfd92848e6b1a540e
│       │   └── chunk-001.nq.gz
│       ├── f2092f4803a149b1feeee6558ab0a0088a8e577b
│       │   └── chunk-001.nq.gz
│       └── f813bc00f5d0f6f42984edd89ca11f4b5245d5e7
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
    ├── 03b9a28a6a926db102b51ba38b0b94f43360921b.nq.gz
    ├── 04834de7a17cb9c74dfb5673669688231b244582.nq.gz
    ├── 04bcffc82f522905cc0629a183abae01de1a9862.nq.gz
    ├── 04c57985b710a2cca4793bbb7d77a883cecd0cbf.nq.gz
    ├── 04ebf691b566df202dd2315dacf7a014410f86bf.nq.gz
    ├── 05e102d8ebd4dc9febdfcdd8b8ae0a626909a7ad.nq.gz
    ├── 05f55b942606f094f5638b66e100008ed54e6692.nq.gz
    ├── 06307e06a1d3e1a7624f5ffb5bd06169b2f23e45.nq.gz
    ├── 067c6bc37960e6fd63d44d807dac167ac4ce2831.nq.gz
    ├── 0688b7d9bfaac5653ec7632756645b994ef6ceb3.nq.gz
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
    ├── 08c8f01b34608e03fcea3e496ec035aaeb4b0923.nq.gz
    ├── 092736875642e06eb9b70ce9385062c5fc86af55.nq.gz
    ├── 0980789a97cc34b47cc71a315148ead84c9bde3b.nq.gz
    ├── 0988b63102cd9798152dcc9189b0e2ce2f0fb26d.nq.gz
    ├── 098bacbe98dfad235ea80a187cd7239b4354c3e7.nq.gz
    ├── 098ea7be82b43706c520c4fa956cfdd7aee1f4f1.nq.gz
    ├── 09eea2ed305b2ee7637195dfebfea0b0406b8719.nq.gz
    ├── 09fecb8efa60e77f4edb1e098cf112bc203068d2.nq.gz
    ├── 0a58c70f5110d1fc00f39fbae6b1306ac815a116.nq.gz
    ├── 0b40e61b71e7c0d4ddcc5d5ea5632a825c9915ae.nq.gz
    ├── 0b691287712c0807c1ca0d06e1eb9638ea895a3b.nq.gz
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
    ├── 12d53913e5a595fe57cdf3a05086e3d8ae5a8b0b.nq.gz
    ├── 12e95b14f8ae96882ca22b635ea5a21f01878849.nq.gz
    ├── 12f48c1774daa524b6ca96f2f84ba820ec825d64.nq.gz
    ├── 130cfa74199dd0699bcc359e7ecdfbce7686f2aa.nq.gz
    ├── 1379ca506d8f92dfcf40b71fc4cea8ba8727c0b6.nq.gz
    ├── 13a5995d292045d0f865a99abf692bd35dc87814.nq.gz
    ├── 13d687c501c854057404469446c680231fbc92e5.nq.gz
    ├── 13fb656010274a38022eb6ecc2eb80d854cbe0e3.nq.gz
    ├── 14069a1d10853e885b9ecdab124a2609db2db3b3.nq.gz
    ├── 1443395b53d371760159d62b89481db5d63bbb1d.nq.gz
    ├── 14c66355d62a26df0e5f71bf2ddbb23a67169567.nq.gz
    ├── 153fd889aedf00190c419b17b94ff7f65d36aa50.nq.gz
    ├── 160d8e47f48c43490b07f3e2705c47d1c3f8ec76.nq.gz
    ├── 1672d0d93b497e3ef89a1c6acbbe97960120d861.nq.gz
    ├── 16a6db1833cbc211f57ac048f5d8ded966c2eb9e.nq.gz
    ├── 16e9fab9ffbcc9ffcb572fef589601423e1a3b3e.nq.gz
    ├── 170da01331ed3ecbedc5510cff0887b5440443fa.nq.gz
    ├── 171facec1f7d4e9d1f3c06bb453b241fba6238a5.nq.gz
    ├── 17a6285bf33a3a4eb6d47cce251319e3cacab4d8.nq.gz
    ├── 17ebad46336af43d7fb261a9b80a1887421c7283.nq.gz
    ├── 185e7807b06000e09a1500b25735d2d21191975b.nq.gz
    ├── 18e16e38c5de68635347d560e655fada9acc0fab.nq.gz
    ├── 190a18037c64c43e6b11489df4bf0b9eb6d2c9bf.nq.gz
    ├── 19110c7c5710a86867b50cee62918ddfa4151488.nq.gz
    ├── 1948b125c205261864156b18178c1af3f535ad76.nq.gz
    ├── 1954704797e3149cf03fb2e0db6d2a3fa5e916e4.nq.gz
    ├── 1966f6a2550411f298dbf5c4c659b12e8fe79d28.nq.gz
    ├── 1a0413a943a60c452c0a81c1b91ae8ebd70fb4dd.nq.gz
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
    └── 211fc8665ec7856d9844acfadaf0031504d6dad7.nq.gz

64 directories, 200 files
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
