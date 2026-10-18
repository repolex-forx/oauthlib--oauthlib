# Repolex Knowledge Graph of oauthlib/oauthlib

RDF knowledge graph data for [oauthlib/oauthlib](https://github.com/oauthlib/oauthlib), parsed by [repolex](https://repolex.ai).

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
rlex download oauthlib/oauthlib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fa4570206dfeecb903dd0948d91bcdeaf07dfa0d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fa4570206dfeecb903dd0948d91bcdeaf07dfa0d
│           └── chunk-001.nq.gz
└── blob
    ├── 00d9576b01ecd9879a4485cf083c2affa79a520c.nq.gz
    ├── 023cf23623ba806446eec8716f34b62d06e00cff.nq.gz
    ├── 04533888e9f2a457ab8bb31a70157deb42dd9d31.nq.gz
    ├── 04bd3d02df255000c06193f4c211dc2c8edc557d.nq.gz
    ├── 062a6a7196fc67d14a5549b4905b833fb07650e3.nq.gz
    ├── 0659ee0d25c3b5c8d92a2e4ea084d651ecd83259.nq.gz
    ├── 07038ddf849d370649da649a7711899a69f59520.nq.gz
    ├── 08cef206e8074c36132e8a19f60fdd5e478624b8.nq.gz
    ├── 0915105bcbd0a0d392c68ff84ee0d1cdf80119ca.nq.gz
    ├── 0c14de9990b0a713f1c98dc37f5632fc04caae8f.nq.gz
    ├── 0c622451a3a622b9f36e40b1e14731d57a851ea6.nq.gz
    ├── 0d97df4ba74995b1d200c8e2f1ea8c11c384332d.nq.gz
    ├── 0e15c0098cb9849a593955d468cfb12d2b11fd8c.nq.gz
    ├── 10c1d0f875ed28ff0b140fd0b8c7e3de00b01554.nq.gz
    ├── 11bfaed21ba645ec17579e12452ee365f0602a98.nq.gz
    ├── 11c4a6291f339426e043bcc24ed73ee438349178.nq.gz
    ├── 130b52e3814bc40c0f483b1ab60b034d1374049c.nq.gz
    ├── 14108314f8b3f00fac69860702a4357e932ccad7.nq.gz
    ├── 15872608949a6a4f7513fccbe733e90eefc08def.nq.gz
    ├── 1695b41b663eded80893849ec0b4ecc6f69c0e5c.nq.gz
    ├── 179c0890c033934e78a14d2286db158a89b44571.nq.gz
    ├── 17df516d17e9409dedc8902fa3a9ae38195c2067.nq.gz
    ├── 1afacd291113f4ffd94568ec7fb6a6fcf420c9c3.nq.gz
    ├── 1cf0ee9f5b98f1534012314973f687d7ce4927c6.nq.gz
    ├── 1d59f4b64ed32727e53b86aab040f5cac7d14a03.nq.gz
    ├── 1f68dce84b5fbe36df08b1ccae678ef4082f4e0d.nq.gz
    ├── 2163772df3c7f53d539fa8cb0b73cc0e547614f2.nq.gz
    ├── 2212890819fc4534415cc5ef5ba3199ee33da68a.nq.gz
    ├── 22aa240d4a97eeba4f1d1e9618f3258338baac96.nq.gz
    ├── 23e3cfc84e0ee61cd461f476c435ef318945ff66.nq.gz
    ├── 24087aa1dec2f0db720b136ba7b334ba7e0a3d76.nq.gz
    ├── 25e4679aa8b2ddeb55108722edf38538cdfe62a9.nq.gz
    ├── 263328dcc1efd50848d8b2bc0b186d81ae7e96e1.nq.gz
    ├── 27ec4359ca7018a33de7379114ee3dc5599f8bd0.nq.gz
    ├── 286d6cbef9ccc11222ed01d216ca5de9ae58ee47.nq.gz
    ├── 28eac548d94ea61fee95be5e48f5ba9afa2fe784.nq.gz
    ├── 291cf13776871147e9660a35254bb70a595fc791.nq.gz
    ├── 292c467f2e9185f3c07e4a891df68483b4f5cc37.nq.gz
    ├── 29d583eb1c0677a5167ddccee274d596e3b1aca7.nq.gz
    ├── 2a897811824d77d0e267e69ab4acfad7f3ad2800.nq.gz
    ├── 2acce34d7d35443bcbe1ed898402901330d79549.nq.gz
    ├── 2c11b3f545035a69c10a46bb78bdf352983881fa.nq.gz
    ├── 2c1c0e29dc3e1c5cb84e918da48ed625c738d336.nq.gz
    ├── 2c4ce3df96c223c86192817ffa7c7c356a7e8240.nq.gz
    ├── 2e1ed0c65b3c73fb12851a936ec9cae426c5a711.nq.gz
    ├── 33261cc1c20a562774bc7f0a2b7aec82f6df20e6.nq.gz
    ├── 33a44bb68f3b6816aeaad47fafbd73ce48f81a84.nq.gz
    ├── 34274cba67baf4699d9c3f82ecc421a6af824d8e.nq.gz
    ├── 3968f2b61c4aa4e37ec3546cc75aa088a6dd4cef.nq.gz
    ├── 398e2395ef01953e71e3483fac0c46dc49078a87.nq.gz
    ├── 3ab35492434d31f1f45741233b9ceb31eb54b96a.nq.gz
    ├── 3b0c6a9798cac0ce84d64804a3e1fa637ae14e6b.nq.gz
    ├── 3bf94c4b51b30c85a94edf261394ddfce5bce2a5.nq.gz
    ├── 3e3ba84513efd402dc7fad780d4a534717923167.nq.gz
    ├── 3f242ff183e28058f69844f9c71b57999281cf51.nq.gz
    ├── 418dba775d13c97c76086b1882753165d7e154c6.nq.gz
    ├── 4291ef8540e8a3ed9cfd865335a3fb2638344986.nq.gz
    ├── 43b9fa5d7494429d8b80acbc3cc06722bc930a5e.nq.gz
    ├── 43e4499c53c77a7f1486981f84e7fe49cf71f545.nq.gz
    ├── 48334851953d50202b8797667fbb96442cdf99a0.nq.gz
    ├── 48b42f6bc8767cab7b40a815df9b2a247844bff9.nq.gz
    ├── 48be472c2e29c408e4bc0aad9bd46a2db6ab1d5e.nq.gz
    ├── 48dcb48cb1b99ecc8c6fdf82bb2f762741dc5315.nq.gz
    ├── 49923e1b0c85e864dc65a2d337bde0900a9a7d78.nq.gz
    ├── 4b75a8a196c6d9e3ff0815c97a7feccf95d9fcd9.nq.gz
    ├── 4be89b6878bdeafe2b17da4718ff6a58ee87d508.nq.gz
    ├── 4c5a84bf28a3360ec73f0863c1a39860722e7994.nq.gz
    ├── 4cbcf42ae3cecc6b89c3bad1294d9d0b75bc4d74.nq.gz
    ├── 4e19e7e6e7d90ad8761d44d6a165dcb1b0dee573.nq.gz
    ├── 4e751977909c543803ed388c885c6804da559900.nq.gz
    ├── 4f4176a7abe1d45f5aad115a7be484ba19bc1b3e.nq.gz
    ├── 4f7bec549d9fcd7b6df5c81044f7b43ba80da9b6.nq.gz
    ├── 50caf981ec1df4ba73369781f042ff5eee4967e9.nq.gz
    ├── 51bb1abb226a858365fbb4de64d460160fc86a06.nq.gz
    ├── 51cd1e9a6cdd29801ea559ff381e8226588a157b.nq.gz
    ├── 521036a4a5ebc75e94a303e316a227520e66d454.nq.gz
    ├── 52968973099b2305ee8e076b5bfbad55955a0fe7.nq.gz
    ├── 53ade8b2c4284acbd5a24fe57d56b1ef39c7ae06.nq.gz
    ├── 570243a2284782b7547c82a2adf59dd69e914ac1.nq.gz
    ├── 5afa4634310ef38f14b7434f00e9fc5d531840f4.nq.gz
    ├── 5b7c3ed969d69c9880e441a853017461c611b28e.nq.gz
    ├── 5e11d5e9835734302bbe9c9990b30810a4fef46c.nq.gz
    ├── 5eae1956f45257001e149d6aa420bdfb79a9f27d.nq.gz
    ├── 5faf16ae07d1d3c8187af33eee9fc693ed61c2b7.nq.gz
    ├── 60ec06b245cb99b329c39ebfe73d3af39edb6586.nq.gz
    ├── 61428ce043d201bcc9728cbbb65eaa0ed7b8f687.nq.gz
    ├── 61786a923a62f9cc8a811465c06e037fc5b39d7b.nq.gz
    ├── 623af6c9f2cd3f2b656bc257e1aced8c80539048.nq.gz
    ├── 65891445e3e687f136fc12896a7d745b70b1594d.nq.gz
    ├── 66394d96266dcd00e940ad6803b759343280b7f9.nq.gz
    ├── 69d2c9506a33035076d022bc1ba34229dae48fba.nq.gz
    ├── 6a5c0c0b529a9826f87ecf58027d0ddf3abbcf51.nq.gz
    ├── 6a6c2e7e9e098ce718ab02b06f5c65efed916d4a.nq.gz
    ├── 6a800d41cabe5c403538948ad898fe6f1f8785d8.nq.gz
    ├── 6afd7f57fd33d15a438c3d4392b0c31abfee7cb8.nq.gz
    ├── 6b2dcc3bdd12d27d280890494286efc5f0c9befb.nq.gz
    ├── 6bd4d6b8af773996d8fce546cdfdfa759f379cd0.nq.gz
    ├── 6bdea12d9ffaa14cf470199ef698799a265d94ef.nq.gz
    ├── 6cce683304ba7d86c78533fec44862f4568f7bfc.nq.gz
    ├── 6dc79713d4bb6294c4489fbea2039804ff197639.nq.gz
    ├── 6de76416d9500c8ad9e4435adc91399c85772dd5.nq.gz
    ├── 6f68334ebe7b6557a89c8a31e1a9d478a7bd9792.nq.gz
    ├── 6f69818e6b89ff4bf08afa55478af6db00f5f8b1.nq.gz
    ├── 6ffdc6e2300b423c75a5659b68e96f5a0f888641.nq.gz
    ├── 7017ff4f3211d2007ee5d297cfff47c0a5b27fd4.nq.gz
    ├── 71967865dce4a1d6cc344036a732f7bc008dbaeb.nq.gz
    ├── 725dea2a929e335807d603d39115273260fb4f65.nq.gz
    ├── 73f14188e97b21ac2cd6f3cf94c82a0848503717.nq.gz
    ├── 7438992ce792e4ec5e7b8712c3e999f05a49d3ad.nq.gz
    ├── 753c5a1544396579ac5f4f259901a301da9d69f1.nq.gz
    ├── 7651287057d9ea007e634d05e8aa357f9ba7eed2.nq.gz
    ├── 76d6388305620e693943d1ba1ba81d040037cb34.nq.gz
    ├── 791ef03d55c55f3b4cb040c077940327ede3cedc.nq.gz
    ├── 7a8d06b66876f3312298d21c1e3dee29c76a5a03.nq.gz
    ├── 7aa2bbe97d34fa5afce4168256aafe1c8ce5fcae.nq.gz
    ├── 7cd6b2069ce078a5d830a5e8563f06b29e0c38c4.nq.gz
    ├── 7e0739684f107801ff094f98190efcd17ae438c1.nq.gz
    ├── 821d3e6339f5a472762f3b492b50b30386acb612.nq.gz
    ├── 83d14ca6018ea4df6859665feac96a2c9f184494.nq.gz
    ├── 8417fe567056f9c8387597bf553defecfed93c3a.nq.gz
    ├── 84361d8bc26db4b9d4871b2f3a1a0d495a8852bb.nq.gz
    ├── 85e0b90b635398a3a2636ed8b5887d5ddb8c59c3.nq.gz
    ├── 8641152e4ee765c889ab608080ae3c6aee3e58e8.nq.gz
    ├── 86c3507e13e3f6539a83488f49f216bad24544f5.nq.gz
    ├── 86fdd8c07c39f73746af27798fe17d4e510314cc.nq.gz
    ├── 883a55056c566a4b4de36bdbc35d776b869c429d.nq.gz
    ├── 8c0de77f2791eea1b4e70ea9123c51f083b9a575.nq.gz
    ├── 8d34415040b9d1c0417c2013d87c5f2a37e6a245.nq.gz
    ├── 8dad5f607b9856704b3f074d31f3b701ddfafd94.nq.gz
    ├── 8f6aa32b7420c4447e0b7419276143955ead1e8a.nq.gz
    ├── 8fc6c955a24dfecd3181f2a2e876fb587299266e.nq.gz
    ├── 9151037b6d1e5093e35b42f0f782f83ee7833204.nq.gz
    ├── 91859fc388208f9d26ed07e126f95dd7c5275fea.nq.gz
    ├── 92b95c116707958ad4d32fa7a70f73869e1e5cf6.nq.gz
    ├── 952cfe4c1aaf82b03e6e9bc92be1ac46711e557a.nq.gz
    ├── 9538d098ce5384cb174cc0fb263ae9735011ad2d.nq.gz
    ├── 9592d9e1eeaa6208deb8fcf7479fe06f15d9a9da.nq.gz
    ├── 95fccf6f90938c6cce63c721e844f42ba55f7fc8.nq.gz
    ├── 97aaf86dffa6dd2c8e94383b42de6d11f9bf172c.nq.gz
    ├── 98f788c0767cd751743d50e247cb9ad0ebecaa76.nq.gz
    ├── 9920981d2c601761492ac1511c3ecd7a6a6a2e51.nq.gz
    ├── 9b5987e701ef74d31fd5c7aab386efa9f9e56fa2.nq.gz
    ├── 9c0cea116c4bfbe44a704e9608249b5511dcc54f.nq.gz
    ├── 9c1fc702f9496c592b06437e774c5d492c1b7de3.nq.gz
    ├── 9caf12a90d878efa4460811310818ee3572fcdd4.nq.gz
    ├── 9dffa81374f90faff86312433cdebc19dbfb5957.nq.gz
    ├── 9f2a730cb202b865d0f10c8a49ccb21202b9f618.nq.gz
    ├── 9f30389f239929754078e3f59688de418d986e29.nq.gz
    ├── a06d6360300f1da4f82b0797791e484960ed5d26.nq.gz
    ├── a108bf685ebe514e98c0fccb8b1750e9849d704c.nq.gz
    ├── a27cb2e76fcae785b8672401458e04c96ab25cb6.nq.gz
    ├── a32cf8a1b330ef3de9e233a7cf12c741d94f9fdc.nq.gz
    ├── a3810a609e540e36202462de03493d544c27bbf5.nq.gz
    ├── a415f6c5c6c417eff3fe62f20c33fa9210aeb377.nq.gz
    ├── a43593898ebb927d70d45f1482f1e5da465d3949.nq.gz
    ├── a4fe6049bc29a8d9b202b9e0244a1b6c559d99d6.nq.gz
    ├── a5ca9bae7dd94c3e09fe71c82332b8aae5ddbdf7.nq.gz
    ├── a7e7486c43582e6d9a90967a04c530e1d6045296.nq.gz
    ├── a80287bf7ff317450ca84e668185b736d80022fb.nq.gz
    ├── a88834b8070df209480e3c50387c74c1d7b9f6c9.nq.gz
    ├── aa409aece41c2cff0a2ca7cd37f6066b74a0b61a.nq.gz
    ├── abf5d322ab8c14fcd7d62fba3e2e9d24f84e5b16.nq.gz
    ├── ad87d80b74ae86962377d9666ad769952b107cc1.nq.gz
    ├── ae483b9ea58f469ba2a11f9735fff3f94daa0696.nq.gz
    ├── aeb4f920a26c6080f8a9256fa8f09d31bbbcf785.nq.gz
    ├── aeb985b4f3216bb49d813a248e1b364a1075ca15.nq.gz
    ├── afb69485b03ea1349a584a7c8c4ae7236d3929d2.nq.gz
    ├── b28c57d490e50b7209207430d580de34b785651f.nq.gz
    ├── b31a545714f78f74d20d5d6316f8747eb3e8be13.nq.gz
    ├── b32e1abcca211d9e562f732358cbda6665b2d29a.nq.gz
    ├── b490134469bb4d0c2cd80bdfd3b493c55ce860cc.nq.gz
    ├── b5a18194b7e6c429062b177ffc59c9b206d544c4.nq.gz
    ├── b6ce191e3790c21b9e7fa7fa88e2855a26f44838.nq.gz
    ├── b80fb0cf8b514d97fbadb64bb28ed1579d32462d.nq.gz
    ├── b8249cac0d23140476348f56b0c931a024f08d74.nq.gz
    ├── b95f4212630c89f8ab5ea91fec4ef7d245e9d926.nq.gz
    ├── ba41bc54063bfc2f0b0cbb98d55d497783282fcf.nq.gz
    ├── bb71c440eae7c6d8770d2bb088b41997efb40c59.nq.gz
    ├── bede3d00671b82321da4e77c91484754d7a7237a.nq.gz
    ├── c0fe2e2dfae19fb118754e914c38c245c0fd3409.nq.gz
    ├── c1489ac7c6b543142829dc75b2b6ea2578e1bfb1.nq.gz
    ├── c228a743e88590928512e95cc3ca8af597b553e8.nq.gz
    ├── c23efabc322a26ab8573706808936526fd328538.nq.gz
    ├── c2ee5d5d3891d1e149feea25cd9bb6c06c75cd6b.nq.gz
    ├── c40950c9786ab0e27bdb31e602530f9b3cc3004c.nq.gz
    ├── c4134877b925021aeec956b30e26d1870213b023.nq.gz
    ├── c639420b7619640b70f3c6ba2e6955b1f34606d0.nq.gz
    ├── c66c649d6978ce57fb5b94ea76b15b1077226e40.nq.gz
    ├── c7213283f72405a3628be6fd3a51785164ae615d.nq.gz
    ├── c726e38fe771dff6affb5aab543c8998d82ab7af.nq.gz
    ├── c7d66d9c5984245030a6f4ff5818d02f5f33a299.nq.gz
    ├── ca92306773a5717c1c6b259d169bab6bc9451e7e.nq.gz
    ├── cabd6e734bbb0c33221f71702dd7e12f78cf2c87.nq.gz
    ├── cabf1e7f4d7dabfd9c35c300174d6c828a51b276.nq.gz
    ├── ccbada490d2077b33e5e45f4e9ae4cbce1331a8d.nq.gz
    ├── cd3bfeb643b1e8e77a04804ef7d3809e07355420.nq.gz
    ├── d1dc343a0f2a56d4242d02d1ca0f3ddef313ed92.nq.gz
    └── d1ff5049d858311a88c4a4115f59437cf20f6243.nq.gz

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

[oauthlib/oauthlib](https://github.com/oauthlib/oauthlib)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
