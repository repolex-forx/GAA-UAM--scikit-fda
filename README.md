# Repolex Knowledge Graph of GAA-UAM/scikit-fda

RDF knowledge graph data for [GAA-UAM/scikit-fda](https://github.com/GAA-UAM/scikit-fda), parsed by [repolex](https://repolex.ai).

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
rlex download GAA-UAM/scikit-fda
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 903c4c9f7f0fe557be55a8a1386d887f08d80ec6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 903c4c9f7f0fe557be55a8a1386d887f08d80ec6
│           └── chunk-001.nq.gz
└── blob
    ├── 01b9f21660931c39d0cf65901aaec187d75884ac.nq.gz
    ├── 0207b1fb2d1c8e6cd19a8c143ecd768f22897af9.nq.gz
    ├── 042fc67122308402d53c1f6d6d980ba23fabd116.nq.gz
    ├── 0475f796a2520b4d43063fc10600bdfdaeeb0eb7.nq.gz
    ├── 0560200f492703cac0372d5bc688bb83701ac06d.nq.gz
    ├── 06008943e44f6a5d9d4970c302ce611d9132859c.nq.gz
    ├── 06c8364ad8f4087fcd9bb1450fbea1ad1fe8f173.nq.gz
    ├── 0717542334de2791bcb9ecc57fb82c8a15b8c340.nq.gz
    ├── 0882408ff4abb10e400609359ef61608e154b8ad.nq.gz
    ├── 092a68f574c3676fae4120a3dcc18c66b2ae124f.nq.gz
    ├── 0943b2f4d4ef7a3133593e33e4a77be341675a56.nq.gz
    ├── 0a3d0e448feae2de48c68342f48955cd9ba0dcb3.nq.gz
    ├── 0b87ef41b5624fbb5b8eb14e77470e9be1b91b45.nq.gz
    ├── 0bbd1a4880102f6ccbae2fb1e7bf15c1c0b7767d.nq.gz
    ├── 0e977299f1fe6ed23caa7990a4c6d0eec34615d3.nq.gz
    ├── 106806473d2a64cdf81537c30fc407ec59350b4c.nq.gz
    ├── 127e7bce2ef06d94cba271174a7f21d516c69da4.nq.gz
    ├── 13535eafba83702318192e2c659e2143efa746c3.nq.gz
    ├── 1363f637e2337fd3af8e16bbf3c847e4668512cd.nq.gz
    ├── 13931ac87cd5e67b889079438de1347bca2a9482.nq.gz
    ├── 13ccd49dc6f8c070b95d2876e79568171fefa2bd.nq.gz
    ├── 15613b0afb63022a03e1b9ddd65decf947c7c6a6.nq.gz
    ├── 16411f3d10609c8f1d51af68278d8cd14db98fed.nq.gz
    ├── 17390f488e27ec7b11af571f1472095a943bf836.nq.gz
    ├── 196591ab10099007b7f79ff63485cd18f9b07434.nq.gz
    ├── 1b91fc60a03000e5c87f4c39cbc72e4ba9df288b.nq.gz
    ├── 1c107564bf4888e0432650c31e6ef7158cfd1b0b.nq.gz
    ├── 1d89bc86e0a1cb365656d1eee760eac5c58eec91.nq.gz
    ├── 1e8550564f2be4d97c650f5fbe9b5f0960006ebc.nq.gz
    ├── 1f8a080374c8c017c22e79464e4e9979f24ea855.nq.gz
    ├── 1ff7496c87c9c64d6100a59713fef006ebe9a179.nq.gz
    ├── 2004210d634b8498da49ded93fd10bd8d66af544.nq.gz
    ├── 201a7e81ed7c8181f7375ab20cb72b3166e1df63.nq.gz
    ├── 201ccb1d88014831d42d613f80fec8be818e9903.nq.gz
    ├── 203e629ac03b49e87277294102b0cfc533b08f8b.nq.gz
    ├── 209aad36beb4cfed84d6f1fd603f74e741fc54b7.nq.gz
    ├── 212c5460e68e3f91ade38b2c18d3c1053ae23714.nq.gz
    ├── 221c4ac89816e71bbf1b3e5b5c1b4f5a8000711d.nq.gz
    ├── 22b74a4370d3a9e5b5d8d6c2d934a43a4a018ff4.nq.gz
    ├── 23b5fe49868e8911a653afbfa6308821c70726b8.nq.gz
    ├── 23faa49bb70ae6e30d3cfbe40990bdba285479c0.nq.gz
    ├── 24dea768041a8b7083ac13f874ef64eb1e09e7fd.nq.gz
    ├── 2526fd1a56558983cbd6dcdb338d34d70257c8d1.nq.gz
    ├── 28e736f7ebb1e55f7c6078384592ee1d55d20170.nq.gz
    ├── 28fb28f2123f84c11b7dbadfaf0e2e52777b22f6.nq.gz
    ├── 295d30d2a42d31a183646e966836e1796a699f08.nq.gz
    ├── 299499eeb24a0481f40ebe15d8bfe8f06fe35d23.nq.gz
    ├── 29fd65ef652f85bac24aed4e15653ba4f6f31ab2.nq.gz
    ├── 2a4af170b3dd694329a6d56284c0106b031965aa.nq.gz
    ├── 2b7291db7b271bdbb889f6fde8c80cac2be2e849.nq.gz
    ├── 2be244576a6777f4d73511c6be0e0c8a6abbbe2b.nq.gz
    ├── 2be25e30ee2666bbb66a054e4162f9063b8d6420.nq.gz
    ├── 30d1fae7e524ca6237289578823c652b29e19b1b.nq.gz
    ├── 319da371eb7124026e2fc0e43226926c49e3dfe1.nq.gz
    ├── 31d21cfb93684a55c3e501d55a26f8ba9a9555a2.nq.gz
    ├── 31e3338d6d34fd7efb4c8bb6238211a1e295b75e.nq.gz
    ├── 32373dffb2c8acc32ca9e6bad0c6f7d627ce2bc2.nq.gz
    ├── 3305ba21af01aa38b932c526e749a8b0c11d385d.nq.gz
    ├── 33716893d0a6ee8cd73db4e552a303522a42270e.nq.gz
    ├── 33742cc8c46c4ad1103a0fae479295e146821fe3.nq.gz
    ├── 345eb30acb07c275ef2a09f15071a310ceda93c9.nq.gz
    ├── 34ace0f67026d232419225ab614cb0cedfdf50fe.nq.gz
    ├── 34b7cc4b3986637891634579db4c6d17a58bb094.nq.gz
    ├── 35129ac3ab3df8102641cffd2aae70aab9416860.nq.gz
    ├── 36896a1f079eaef284f77bb6ce7bf9d97b7c3101.nq.gz
    ├── 36afa1a5bc4206a415883cbdfbc2a485e5ebc6ba.nq.gz
    ├── 36b54860f8e53b510404795f2292dce62db9d1d5.nq.gz
    ├── 3850ac336a309e315816938c01013cca06000c67.nq.gz
    ├── 387dfcdb85ca086010dcbfbf30de825a0b4c1462.nq.gz
    ├── 38c219a75ec5965ea386c4169d022dfaf858f68e.nq.gz
    ├── 38e1df7fb4f9b45e39990e1e7b4a2ed63a8f7a8a.nq.gz
    ├── 38fba4a8b856fdc1dbab8c48e73ae9798c3a0011.nq.gz
    ├── 3934b97e8d994a082d45b87567dad8623033e7c7.nq.gz
    ├── 3978f20c3543fc853bef172ade503d9d72f5f0d1.nq.gz
    ├── 3a708edbaac627b4af5e4d047fc90bc481d14a64.nq.gz
    ├── 3beedcd7337e87ef275d1643a0a641248c528973.nq.gz
    ├── 3c028b21e7af0bc976ba433526312e76ac2a7997.nq.gz
    ├── 3c6b36ea35b72fec246f3dbb329adb3f8d8db475.nq.gz
    ├── 3cf0155af0941762a5177fc120d806f55f1d2ec4.nq.gz
    ├── 3d863b00eef630e29087626b652996a0b9fcbdbe.nq.gz
    ├── 3e1ff98a8ce647cd8efb5bbe44bbc1fc5c1d57ec.nq.gz
    ├── 3fb0a892c9d5d45fa14615c61657a3197035b990.nq.gz
    ├── 409803097e0527cca9dbcd24db6fdcf19d00d869.nq.gz
    ├── 40a23d9bf06c8ce054dcd71979ed05eb6e01ce9d.nq.gz
    ├── 429e110e599b7097af816cc1d0558890c979ff72.nq.gz
    ├── 42ed5bdbdf500472c307342db3aca4709d98a2e6.nq.gz
    ├── 432e572a1ff0a286fdc71ca3fa9ca6efd7e1c3be.nq.gz
    ├── 438e8fe5510b93dd065e6c4c51beec47622f45de.nq.gz
    ├── 43be259cfd83634399b5b33d8bafe7879285a07f.nq.gz
    ├── 46ea191d335c31de9791a3d120364691fd691b2b.nq.gz
    ├── 472933699a324ffaa7c46a6c05e431ceef00bb64.nq.gz
    ├── 482a3a5cb59668991f04d82d917f6706b8fd11eb.nq.gz
    ├── 4997ace4aca832c8930c44c2d41a72ea77db87a3.nq.gz
    ├── 49c8c0a51f5c7b466b1805f3032c2f6e29015311.nq.gz
    ├── 4a1c480ec2bd8247877cdff70d32ff273a5763d0.nq.gz
    ├── 4a89f4b731b69aa4f06e0b089520a5502b322302.nq.gz
    ├── 4a9113cd68276739c064beba0faddc676b696ce2.nq.gz
    ├── 4c2081efffe8ec1ddca3d3949dbfdfe0ec337b0f.nq.gz
    ├── 4c86047ebc2d8ab17e12239b8d627c5be9db1cfa.nq.gz
    ├── 4cdf014358adcfa944204ed843e6bd3b91faf82a.nq.gz
    ├── 4cfa3b054f1b086d4397108d69f4db11598dedd7.nq.gz
    ├── 4d3840d1eddacb9408e12addd32fbc27093caa14.nq.gz
    ├── 4d7dd7bd57a36875e75e52a8a7aa13c03edd83a8.nq.gz
    ├── 4edf80ae3079005dbfe52d7c1ea045132bf213fc.nq.gz
    ├── 4f08a55671a8ad3af8ba7c9fd0aa0dd55e08a489.nq.gz
    ├── 4ffe4c1d26d5719af28d55d0ecd98820d0e87ccb.nq.gz
    ├── 5132a4bd8064e0bedeb68723182b319579b1cec1.nq.gz
    ├── 51375d20c42c3cff6cdec2d4d415ebe9a111974b.nq.gz
    ├── 51694ede0a069a19d786b7695477649f4e0615d9.nq.gz
    ├── 517a631907b4f3edd4178a17c45e44e1010806d4.nq.gz
    ├── 52285c34f1bbdf38c8f44284e3482d95cc438596.nq.gz
    ├── 5243a1356689d8423c1f399e0f438691a523c39d.nq.gz
    ├── 529c5eea87fe18387936053441487d879c032877.nq.gz
    ├── 53334422b55ce5ed3e82434d01a11a49abe5c252.nq.gz
    ├── 536673163f4729e00f98ef92699b2a245cb14847.nq.gz
    ├── 541b5447a9d215b808417399d5085e0fd692c3e3.nq.gz
    ├── 54d8914f99d4f5c2142badcacffa0b2cdc936dff.nq.gz
    ├── 553cfdb801d0b1d1620fdc975bc2440a86990cfb.nq.gz
    ├── 5658b818970202f77ccd4c498729b1321026498d.nq.gz
    ├── 5699e73b940c37db7f2b317558cb69acaaf38362.nq.gz
    ├── 57e93b2fac2c4bfe9808d952544b1960156ffae7.nq.gz
    ├── 5806b9cb215b298ecc62fa22d18073b5d521d5d7.nq.gz
    ├── 58930e3968bb98a6ff2512a1c35e367b15734a0c.nq.gz
    ├── 58bacc1d5dc108fdb3710be41b9a1c1bfff0a899.nq.gz
    ├── 58bdf4e6dafbdea57f3b16d4c5d5f3c6269de85c.nq.gz
    ├── 58d8efab49fb367cd826bb2b2d88f09e3acd2a6e.nq.gz
    ├── 590eeea9909c7db9f2278a90ab2bdf0da6bac133.nq.gz
    ├── 59951162f9f46180f1f853ac2f458bc01ba1cb04.nq.gz
    ├── 599b3c4fbcbddd9243e916eadea9acd276e71050.nq.gz
    ├── 5b5555e5bc18d5d1e78a03d374d25e91f2f4a2a0.nq.gz
    ├── 5cd8d9eb0abef39011e148d4e84117495d240d5e.nq.gz
    ├── 5ea79043085203b04769348783c99b9e28730371.nq.gz
    ├── 5f2b0cc8682939d9fc5861d3535241496763480a.nq.gz
    ├── 61222cf54bf7ad8fc637c9bfab34f6909038ba22.nq.gz
    ├── 6249a0d9b4b0021bbf31af4810e161d5562d0276.nq.gz
    ├── 6253934d7d83206cee191aa30cff0f80d00c764c.nq.gz
    ├── 62f99b2b8be394f4d105338ac9dfc83cafc8210f.nq.gz
    ├── 642e6a31ec5d37becb7490e1f47f980d4e03691f.nq.gz
    ├── 650414008ff4fa4e1265d8b54b6cad9095ba071c.nq.gz
    ├── 650dfff608a0c1ac758165d5f193075c576761a7.nq.gz
    ├── 65d382b86e525bb88189e51638664d04a34f8936.nq.gz
    ├── 66ae63c3031683f8c39a74307899efcdd327e693.nq.gz
    ├── 6703495b4ade7d273896ae109f7d3125917ee8f2.nq.gz
    ├── 672326657a69294996434ab34783b10100b7309c.nq.gz
    ├── 673cc9da31411f3c12399579d5309a10e7724098.nq.gz
    ├── 67655fb6b56655bfd505f6fdfb309d2a39296ee8.nq.gz
    ├── 6a977724a479fc4ccf8c08050a2fd2dc9e747571.nq.gz
    ├── 6ab45a8135eb1b798ccd391d5ee83e6b3cbb6cdd.nq.gz
    ├── 6c18cf0f0e948281388c8309e337913115ed2679.nq.gz
    ├── 6c4753199ac404527d7d528eb267122520d16bc4.nq.gz
    ├── 6d1669f9c63dcd5658474f8e1bd7f05185ecfb3b.nq.gz
    ├── 6f28a04dd5ff5af4e1f6f15909b327df6f2dcfec.nq.gz
    ├── 6f8142b681ccdfb1fd06789944a8880e67ff7be9.nq.gz
    ├── 702c3444409ab122f4f3003b6e1f9229be95cef6.nq.gz
    ├── 70fefcd98ae81db64e8ebe5500d0e2de2d4fe50d.nq.gz
    ├── 720bfb848893a31d6f9c6eb87add9a11da4c98f2.nq.gz
    ├── 7539c308831bc2d6eae93b1d2bd1e365407365f9.nq.gz
    ├── 755d4b255f48afc0f52faf27a841af220cea91bb.nq.gz
    ├── 75bab293f3bdafc6d8bcbbf123e8f8f7c1c65bbf.nq.gz
    ├── 76c4e7111ca178fadda3aaaca51b9f483dce8864.nq.gz
    ├── 7897f363c35854f14e5caa9577a9f3571ccb201b.nq.gz
    ├── 78f1dc76b23b19fab28056c1d622a040eda06d92.nq.gz
    ├── 7dde09b7338766fdad3b6775d94f0e31e81f899b.nq.gz
    ├── 7e0d13771431aa869484b795ca654b94564852b0.nq.gz
    ├── 7eb59171dc27a17d87a3ab33312f26ba3584483c.nq.gz
    ├── 7f28425b6fcaeb8f202decc553b7473648fced2f.nq.gz
    ├── 7f634daf14556582e6b54ea8542966745569203c.nq.gz
    ├── 7feffc105cbdb58af63e7caa6f2eaba134f2c658.nq.gz
    ├── 7ff55fe5f0fc4648573400b16defc130a91e0b53.nq.gz
    ├── 833395c2f51919863362c4a79c74b670ee0e82e0.nq.gz
    ├── 836fa27faea26c53c823536313a3266e4d47c1a5.nq.gz
    ├── 840c6c84d13d705c7927f00241db4076cf620304.nq.gz
    ├── 846c962d1538affe8cca0d168bf7b9564eacc68d.nq.gz
    ├── 84fd01323f633b59aaedde888b7f1f168af760e5.nq.gz
    ├── 85c26762290beb4b5c0125927cb3a8135e64517a.nq.gz
    ├── 85ec04f1c5cedfabf7c129af84ada4d9891b9cef.nq.gz
    ├── 8747947439884e8851ae077d805d36f76e0daac8.nq.gz
    ├── 884d29c2678302f5578fc077b99976a9286b7150.nq.gz
    ├── 889733d9bd69ce61e0481842679430c9d277c056.nq.gz
    ├── 89e42a77e26a52b9909a3d391bd25b8e98eb390a.nq.gz
    ├── 8ab1412e36048e1469d4ff871ba9ab5f8ee060ac.nq.gz
    ├── 8bbc64d5b66d9e4ba09b86794916b5a6b36cc5b9.nq.gz
    ├── 8d940ec6b4aaf5c4827c4cf6fdf474ebe189cec4.nq.gz
    ├── 8db82bb56d40b07d88e2b826f865d065adf4253f.nq.gz
    ├── 8e5348cdcb88a73bd87567ebb5b0183900414c96.nq.gz
    ├── 8f7c9b98029e40c6196cfb35adeb5d9295bc4c09.nq.gz
    ├── 8fad96c424051da04d35c626318aa2dee10d078c.nq.gz
    ├── 90a18832edc47c2486dd5349f162a282ebfa03fa.nq.gz
    ├── 90a719e24dcf9145b5f1499e60121b91e9491ebf.nq.gz
    ├── 9120e7abc07f277c6aa18adfb262a1d382941dbd.nq.gz
    ├── 91f1487c7258557d83a8bffa169fc7c277ad836b.nq.gz
    ├── 9467213a3ace774fdf754107dcec10ff3d950583.nq.gz
    ├── 9822158ade55fb0eee00fb892ef04250f2b41f6e.nq.gz
    ├── 9890198a74630075397033a13920a2af93588e6a.nq.gz
    ├── 9aad0fc3fe79b34fc998c6e0546862b60dc2d4ee.nq.gz
    ├── 9b43a202245d7a0c14a1530cdf061a8e9ec21afd.nq.gz
    ├── 9bb7bc5fb9162acac7510c0517935d793eae26c7.nq.gz
    └── 9dcb7ca5278af1c3ca5438d744f13e6db5e3a011.nq.gz

7 directories, 200 files
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

[GAA-UAM/scikit-fda](https://github.com/GAA-UAM/scikit-fda)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
