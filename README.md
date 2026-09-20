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
│   │   ├── 03b28d0fc787f60532bc16c6f494925ad8af2887
│   │   │   └── chunk-001.nq.gz
│   │   ├── 066417ba61f7caf9ffcf5f17be3854f1234c2b4a
│   │   │   └── chunk-001.nq.gz
│   │   ├── 0f64cbfa54b0b22dc7b776b7b98a7cd657e84d78
│   │   │   └── chunk-001.nq.gz
│   │   ├── 23c952fe08b2e7ea0f8d7673f45b17547e331f4b
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2b9937bd049a37f6430e2fcb75125705ff08e463
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2eed9c7679251298c5d604cd96d232f285c979fa
│   │   │   └── chunk-001.nq.gz
│   │   ├── 2f463cf5b0e98a52bc20e348d1e69761bf263b86
│   │   │   └── chunk-001.nq.gz
│   │   ├── 38cb7e2e6b803a534bd28d06132c93243d0761a8
│   │   │   └── chunk-001.nq.gz
│   │   ├── 3f96307018244fab5a5c4805626dc7d0b255f591
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
│   │   ├── 72992fe01c88a5b6bccb03a75a9498b4fe747ac2
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7e026bfee9cc0bddeb1bbca0c4a0bcd826c2bfdf
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8424b5861467d0e98391799b3db21530bf9eba97
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8cdff2c80573b8be8e8ad28929264a913a63aa33
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8da04ac09699b073da649c4c899172e2968c12c1
│   │   │   └── chunk-001.nq.gz
│   │   ├── 8e88d11b41b8cbec4c51180589fd77b6a3d7c1f9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 93ec8bc45faf12c2906aba737b20832d775b5213
│   │   │   └── chunk-001.nq.gz
│   │   ├── 96ee4cbfcc0aadb73d46f06f0672b7b4d5a29fb6
│   │   │   └── chunk-001.nq.gz
│   │   ├── a204d840220a044ce782b5b5906d150dc053de0c
│   │   │   └── chunk-001.nq.gz
│   │   ├── a2d481b8dbd2b352cb001f07091ccf669227290f
│   │   │   └── chunk-001.nq.gz
│   │   ├── a5c2a043a26a6bf2787870eec9006b96ba6bca91
│   │   │   └── chunk-001.nq.gz
│   │   ├── a94428474424e75e438959b7ad9c0a396dece038
│   │   │   └── chunk-001.nq.gz
│   │   ├── a9b98a3daa43d43afd8051b014d5b4154d141913
│   │   │   └── chunk-001.nq.gz
│   │   ├── b79e34b37e676371a6a104970a8a944fb514b679
│   │   │   └── chunk-001.nq.gz
│   │   ├── be67e2df27a33f11511c6aef96ebb146f5ae41bc
│   │   │   └── chunk-001.nq.gz
│   │   ├── c42fa3bff1eabdb64763bb1526d9ea1ccb708479
│   │   │   └── chunk-001.nq.gz
│   │   ├── d3eb7daf88e29bc20ffd4cfb833da3c49c617625
│   │   │   └── chunk-001.nq.gz
│   │   ├── da8f3caa440b7dab22b9e4f88888bd65472d1127
│   │   │   └── chunk-001.nq.gz
│   │   ├── dd9f0e1236775dcce682c91823e009556ce2a271
│   │   │   └── chunk-001.nq.gz
│   │   ├── df47f5f18a247830419bae1d5b43b2bd77a1c0fd
│   │   │   └── chunk-001.nq.gz
│   │   ├── e471e86bf6dabdad45a1438c20a4a5c033eb9034
│   │   │   └── chunk-001.nq.gz
│   │   ├── ee37f4653c08fc07aecff69cfd92848e6b1a540e
│   │   │   └── chunk-001.nq.gz
│   │   ├── f18dbe7f5d272f569d3e343d12174c0298cf7e2d
│   │   │   └── chunk-001.nq.gz
│   │   ├── f2092f4803a149b1feeee6558ab0a0088a8e577b
│   │   │   └── chunk-001.nq.gz
│   │   └── f813bc00f5d0f6f42984edd89ca11f4b5245d5e7
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 03b28d0fc787f60532bc16c6f494925ad8af2887.nq.gz
│   │   ├── 066417ba61f7caf9ffcf5f17be3854f1234c2b4a.nq.gz
│   │   ├── 0f64cbfa54b0b22dc7b776b7b98a7cd657e84d78.nq.gz
│   │   ├── 23c952fe08b2e7ea0f8d7673f45b17547e331f4b.nq.gz
│   │   ├── 2b9937bd049a37f6430e2fcb75125705ff08e463.nq.gz
│   │   ├── 2eed9c7679251298c5d604cd96d232f285c979fa.nq.gz
│   │   ├── 2f463cf5b0e98a52bc20e348d1e69761bf263b86.nq.gz
│   │   ├── 38cb7e2e6b803a534bd28d06132c93243d0761a8.nq.gz
│   │   ├── 3f96307018244fab5a5c4805626dc7d0b255f591.nq.gz
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
│   │   ├── 72992fe01c88a5b6bccb03a75a9498b4fe747ac2.nq.gz
│   │   ├── 7e026bfee9cc0bddeb1bbca0c4a0bcd826c2bfdf.nq.gz
│   │   ├── 8424b5861467d0e98391799b3db21530bf9eba97.nq.gz
│   │   ├── 8cdff2c80573b8be8e8ad28929264a913a63aa33.nq.gz
│   │   ├── 8da04ac09699b073da649c4c899172e2968c12c1.nq.gz
│   │   ├── 8e88d11b41b8cbec4c51180589fd77b6a3d7c1f9.nq.gz
│   │   ├── 93ec8bc45faf12c2906aba737b20832d775b5213.nq.gz
│   │   ├── 96ee4cbfcc0aadb73d46f06f0672b7b4d5a29fb6.nq.gz
│   │   ├── a204d840220a044ce782b5b5906d150dc053de0c.nq.gz
│   │   ├── a2d481b8dbd2b352cb001f07091ccf669227290f.nq.gz
│   │   ├── a5c2a043a26a6bf2787870eec9006b96ba6bca91.nq.gz
│   │   ├── a94428474424e75e438959b7ad9c0a396dece038.nq.gz
│   │   ├── a9b98a3daa43d43afd8051b014d5b4154d141913.nq.gz
│   │   ├── b79e34b37e676371a6a104970a8a944fb514b679.nq.gz
│   │   ├── be67e2df27a33f11511c6aef96ebb146f5ae41bc.nq.gz
│   │   ├── c42fa3bff1eabdb64763bb1526d9ea1ccb708479.nq.gz
│   │   ├── d3eb7daf88e29bc20ffd4cfb833da3c49c617625.nq.gz
│   │   ├── da8f3caa440b7dab22b9e4f88888bd65472d1127.nq.gz
│   │   ├── dd9f0e1236775dcce682c91823e009556ce2a271.nq.gz
│   │   ├── df47f5f18a247830419bae1d5b43b2bd77a1c0fd.nq.gz
│   │   ├── e471e86bf6dabdad45a1438c20a4a5c033eb9034.nq.gz
│   │   ├── ee37f4653c08fc07aecff69cfd92848e6b1a540e.nq.gz
│   │   ├── f18dbe7f5d272f569d3e343d12174c0298cf7e2d.nq.gz
│   │   ├── f2092f4803a149b1feeee6558ab0a0088a8e577b.nq.gz
│   │   └── f813bc00f5d0f6f42984edd89ca11f4b5245d5e7.nq.gz
│   └── repolex
│       ├── 03b28d0fc787f60532bc16c6f494925ad8af2887
│       │   └── chunk-001.nq.gz
│       ├── 066417ba61f7caf9ffcf5f17be3854f1234c2b4a
│       │   └── chunk-001.nq.gz
│       ├── 0f64cbfa54b0b22dc7b776b7b98a7cd657e84d78
│       │   └── chunk-001.nq.gz
│       ├── 23c952fe08b2e7ea0f8d7673f45b17547e331f4b
│       │   └── chunk-001.nq.gz
│       ├── 2b9937bd049a37f6430e2fcb75125705ff08e463
│       │   └── chunk-001.nq.gz
│       ├── 2eed9c7679251298c5d604cd96d232f285c979fa
│       │   └── chunk-001.nq.gz
│       ├── 2f463cf5b0e98a52bc20e348d1e69761bf263b86
│       │   └── chunk-001.nq.gz
│       ├── 38cb7e2e6b803a534bd28d06132c93243d0761a8
│       │   └── chunk-001.nq.gz
│       ├── 3f96307018244fab5a5c4805626dc7d0b255f591
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
│       ├── 72992fe01c88a5b6bccb03a75a9498b4fe747ac2
│       │   └── chunk-001.nq.gz
│       ├── 7e026bfee9cc0bddeb1bbca0c4a0bcd826c2bfdf
│       │   └── chunk-001.nq.gz
│       ├── 8424b5861467d0e98391799b3db21530bf9eba97
│       │   └── chunk-001.nq.gz
│       ├── 8cdff2c80573b8be8e8ad28929264a913a63aa33
│       │   └── chunk-001.nq.gz
│       ├── 8da04ac09699b073da649c4c899172e2968c12c1
│       │   └── chunk-001.nq.gz
│       ├── 8e88d11b41b8cbec4c51180589fd77b6a3d7c1f9
│       │   └── chunk-001.nq.gz
│       ├── 93ec8bc45faf12c2906aba737b20832d775b5213
│       │   └── chunk-001.nq.gz
│       ├── 96ee4cbfcc0aadb73d46f06f0672b7b4d5a29fb6
│       │   └── chunk-001.nq.gz
│       ├── a204d840220a044ce782b5b5906d150dc053de0c
│       │   └── chunk-001.nq.gz
│       ├── a2d481b8dbd2b352cb001f07091ccf669227290f
│       │   └── chunk-001.nq.gz
│       ├── a5c2a043a26a6bf2787870eec9006b96ba6bca91
│       │   └── chunk-001.nq.gz
│       ├── a94428474424e75e438959b7ad9c0a396dece038
│       │   └── chunk-001.nq.gz
│       ├── a9b98a3daa43d43afd8051b014d5b4154d141913
│       │   └── chunk-001.nq.gz
│       ├── b79e34b37e676371a6a104970a8a944fb514b679
│       │   └── chunk-001.nq.gz
│       ├── be67e2df27a33f11511c6aef96ebb146f5ae41bc
│       │   └── chunk-001.nq.gz
│       ├── c42fa3bff1eabdb64763bb1526d9ea1ccb708479
│       │   └── chunk-001.nq.gz
│       ├── d3eb7daf88e29bc20ffd4cfb833da3c49c617625
│       │   └── chunk-001.nq.gz
│       ├── da8f3caa440b7dab22b9e4f88888bd65472d1127
│       │   └── chunk-001.nq.gz
│       ├── dd9f0e1236775dcce682c91823e009556ce2a271
│       │   └── chunk-001.nq.gz
│       ├── df47f5f18a247830419bae1d5b43b2bd77a1c0fd
│       │   └── chunk-001.nq.gz
│       ├── e471e86bf6dabdad45a1438c20a4a5c033eb9034
│       │   └── chunk-001.nq.gz
│       ├── ee37f4653c08fc07aecff69cfd92848e6b1a540e
│       │   └── chunk-001.nq.gz
│       ├── f18dbe7f5d272f569d3e343d12174c0298cf7e2d
│       │   └── chunk-001.nq.gz
│       ├── f2092f4803a149b1feeee6558ab0a0088a8e577b
│       │   └── chunk-001.nq.gz
│       └── f813bc00f5d0f6f42984edd89ca11f4b5245d5e7
│           └── chunk-001.nq.gz
└── blob
    ├── 00688696d9ddd6744d74be8addb745eca1ae4eb0.nq.gz
    ├── 00c97236d809e9f9e33e98c70fd98e9549d5504a.nq.gz
    ├── 00ce069c6f896d8a7d42af6c9ec24b364c7f9d47.nq.gz
    ├── 00d83349e1132f673a6ec8019e99d2e3d4dd948a.nq.gz
    ├── 013896d2f10619e0e75d2579cd63220338a7fef1.nq.gz
    ├── 0168441770dc068e31a2343f249be0be8306da45.nq.gz
    ├── 016fb640aef84f982edfe8d86cb0f30c50a3701d.nq.gz
    ├── 01de2cd08dac3da9baa48410bda2ae7b8eba6ba6.nq.gz
    ├── 01f2f5686efd4c1b35a2904998c8e364ed52d9b4.nq.gz
    ├── 020e6db88b7c5f71711f852527a06064b27db20c.nq.gz
    ├── 021635f30e72a8910438ccce0a66354faf5eaf48.nq.gz
    ├── 022446df466be658ef72b6c3a1c453078880c153.nq.gz
    ├── 02b1605e184e2540ad787e605a5735f66fcf8199.nq.gz
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
    ├── 04f54ef808f1894c229e3dde2979cc77c1564ddd.nq.gz
    ├── 050ced23f688452a6333a44de9b7cae80ec494d5.nq.gz
    ├── 0573512ce06eb2e2b3051103c556d552a51bb583.nq.gz
    ├── 05e102d8ebd4dc9febdfcdd8b8ae0a626909a7ad.nq.gz
    ├── 05f55b942606f094f5638b66e100008ed54e6692.nq.gz
    ├── 06307e06a1d3e1a7624f5ffb5bd06169b2f23e45.nq.gz
    ├── 067c6bc37960e6fd63d44d807dac167ac4ce2831.nq.gz
    ├── 0688b7d9bfaac5653ec7632756645b994ef6ceb3.nq.gz
    ├── 06abdb5f66a4a15d018c5a50f02bbdb4415982f4.nq.gz
    ├── 06c033e634f04f6364e40d34fc9e229468b1ce9b.nq.gz
    ├── 06c7f0e47b48fa6e60ae3cf05be29fdb88b60425.nq.gz
    ├── 06e5ac782f1ade899fe0f7e3c4f754784e498efe.nq.gz
    ├── 07621450c630dccf2e878785cd4b83ae68ac4186.nq.gz
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
    ├── 093294204b760853acc17eab6ce381d12bad30f1.nq.gz
    ├── 0980789a97cc34b47cc71a315148ead84c9bde3b.nq.gz
    ├── 0988b63102cd9798152dcc9189b0e2ce2f0fb26d.nq.gz
    ├── 098bacbe98dfad235ea80a187cd7239b4354c3e7.nq.gz
    ├── 098ea7be82b43706c520c4fa956cfdd7aee1f4f1.nq.gz
    ├── 09eea2ed305b2ee7637195dfebfea0b0406b8719.nq.gz
    ├── 09fecb8efa60e77f4edb1e098cf112bc203068d2.nq.gz
    ├── 0a58c70f5110d1fc00f39fbae6b1306ac815a116.nq.gz
    ├── 0aacf1722c963a09d9c49e6cb562dc1e72202095.nq.gz
    ├── 0aef98283e4c2aca62f218504a3f449812ff676b.nq.gz
    ├── 0b40e61b71e7c0d4ddcc5d5ea5632a825c9915ae.nq.gz
    ├── 0b691287712c0807c1ca0d06e1eb9638ea895a3b.nq.gz
    ├── 0bf1e96dc1623b34d69df91c8a93ef8a273d9430.nq.gz
    ├── 0c21345879b298bb8668201bebe7d289586b17f9.nq.gz
    ├── 0c5cda186dc8f217e04be9ca221e318a61db918a.nq.gz
    ├── 0c873e9e860486a141020de3a1b42d4fd3456345.nq.gz
    ├── 0c90c05dff9262ee3040e0804df9245fdf693e31.nq.gz
    ├── 0ca49912bed281bc3c30a7098f41dcd828896203.nq.gz
    ├── 0ca95142bb715442d0c2c82a7c573a08c4593845.nq.gz
    └── 0cb482c9e08efc43be7016e3cf03eeea5f0bc356.nq.gz

94 directories, 200 files
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
*Parsed on 2026-09-20 by [repolex](https://repolex.ai)*
