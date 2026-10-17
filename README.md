# Repolex Knowledge Graph of lmfit/lmfit-py

RDF knowledge graph data for [lmfit/lmfit-py](https://github.com/lmfit/lmfit-py), parsed by [repolex](https://repolex.ai).

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
rlex download lmfit/lmfit-py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e270500e3efb4ff9cce91416b3f55678d6271811
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e270500e3efb4ff9cce91416b3f55678d6271811
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d8f794bfe802a9e4714348b116a73537102978.nq.gz
│   ├── 034217ca61de42c6001d3e52f3b2ba42a68678a5.nq.gz
│   ├── 05e909bce5904091fa6e068f8e0d90a3d41a3e02.nq.gz
│   ├── 07fa7eb9cda694594c1401068a54367b79c3afb6.nq.gz
│   ├── 08ae5f5d30ab47d2ba852aa3440feb05b46b3ee5.nq.gz
│   ├── 08b266278c9544e0b27a328ab771eae22949e145.nq.gz
│   ├── 0d0e92897afb7169dab58f956faf37bcf25aa84c.nq.gz
│   ├── 0ebf76507509bfc0cf23913f07364e3a01477ee5.nq.gz
│   ├── 103acf24159a1394b9b5d3342f0d0c405361b494.nq.gz
│   ├── 10ee5c3d0293b1dc7f2d12ec33b37c5a90e41205.nq.gz
│   ├── 111aba9e9f1b02720b4012d87916e2e812248cbc.nq.gz
│   ├── 115c985328fcd37358d7e9e918f2604474655513.nq.gz
│   ├── 11b22da0b7c38aff97eea1f4c4e881a1f7f4f528.nq.gz
│   ├── 123a6631254cfdc6915bafcbc8379a1738fb14e1.nq.gz
│   ├── 136006a3521beb5399472e78b24bc83c1c7d8516.nq.gz
│   ├── 14130e315cca073c3b8086df6e1c610fad70e0ae.nq.gz
│   ├── 161e444db50a63b0fb6ae9ee24092cec0df74cbd.nq.gz
│   ├── 164770596e34b959915322dda415044a96e04822.nq.gz
│   ├── 1c244b4adf7d159f24cc0328381b90d5b69b4404.nq.gz
│   ├── 1c4f2da8e57f38a258cad4fecdcbc7bbe9c15f4f.nq.gz
│   ├── 23824cc6447c7dc0ac665e2824803cb1fec5f99e.nq.gz
│   ├── 2393829272bab4b60535ac38812e27092b124593.nq.gz
│   ├── 23dc998d9e1a3081243931d0650bc08d9662cfa0.nq.gz
│   ├── 2416fd2b8af230e73b36a777315a4e6df3f5e92e.nq.gz
│   ├── 24939f64ea874f49130f52397511151b29d0da79.nq.gz
│   ├── 251d55128beb5c2f65eee0d4fff2d5fe966ca3e4.nq.gz
│   ├── 2822cb06ecd7e1370d9311790735b98f1fdabb1a.nq.gz
│   ├── 2906603b30de27d06ec2289f2b5634071854c697.nq.gz
│   ├── 2a1528a0bc49974ba03886387ecb0dc4286acdb9.nq.gz
│   ├── 2b4b56b3eb34c527eb028cd26963877abae751c4.nq.gz
│   ├── 2b8dd928db4ceeff5b7413b9dd3dc4da7c62618f.nq.gz
│   ├── 2bf542f46cd2cdcb98e5d9c7564e1fcaa5cf1b4f.nq.gz
│   ├── 2dfa1b45827991faf1e581605c1a049648967cef.nq.gz
│   ├── 2e6c820bad0035bb3210db861c5c3c26d485b341.nq.gz
│   ├── 3005ca642aa14f1a65433f7ca693ac24fe22312f.nq.gz
│   ├── 309ac0ff417977ae631d63877f1f37f120ac8f92.nq.gz
│   ├── 31a3800c17b9909ae3b6583b592a82f52910b3f9.nq.gz
│   ├── 3486c1ac817d3f063f853b01a2d9e5dbef96ace9.nq.gz
│   ├── 3561eea69739b33d07d4fadc16bc5182fd629374.nq.gz
│   ├── 372f734c091014754bec2b5abf1f12f2f8ea5615.nq.gz
│   ├── 379417f899c148f8567fee0fec173e2f024621ce.nq.gz
│   ├── 37ad494b9effe0ab21caede385b333c2a0252ced.nq.gz
│   ├── 3947fb1e7c19efaf70a4ab1b006a4f139e99966b.nq.gz
│   ├── 3a8cecbb026cbe48349f8260c79043ff019a1d35.nq.gz
│   ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
│   ├── 3bbe16e36b6b4d4f9ebd89e0982abb5a28bd05c5.nq.gz
│   ├── 3c7cca59627555000cd9213043ab970913a254c0.nq.gz
│   ├── 3db894bde28368b241637141ec6739bf914695bd.nq.gz
│   ├── 3dbac16c1f7343e8f50bd38175021cdfe529a75e.nq.gz
│   ├── 40a721496c4022e3e3635dde69019d0eb588cd19.nq.gz
│   ├── 42ee3488c88c18d6a43997b302a0f1ae06498d4c.nq.gz
│   ├── 440fcedd5cc7eebee3c22096147970b008023ec4.nq.gz
│   ├── 45e838f17cd567857981dcff1f0f1ffa94de0693.nq.gz
│   ├── 46557a1032176e5f2506f1abb5cb5645ef10636a.nq.gz
│   ├── 479bd3df918c5f4c8e8e752dfb13158bfa4fa1d1.nq.gz
│   ├── 47dc6015ac65d803abd8d04e55d7e117e4496f24.nq.gz
│   ├── 48d1fff7c0cca33050d5362ce583984ea2bb5b08.nq.gz
│   ├── 49695ffdc23c650df89fe9626f2c2403dbc0daa3.nq.gz
│   ├── 4a2bf3659e92e5b1b97e5c59981170f7853d2753.nq.gz
│   ├── 4acfc011cfb685ed2fe870b5fb55b81f1a9583af.nq.gz
│   ├── 5049ac263ada2ddf1d7e3532fe407042d65c199b.nq.gz
│   ├── 522504964d5fd3c7d9d0e267d9b76361fae3b017.nq.gz
│   ├── 53d09424a4bcefdc6cf030166f99053c11702a7e.nq.gz
│   ├── 5756f2bd74257911e42b0765f0b18b97cf7ffe8b.nq.gz
│   ├── 58bb076478e98a9b287748b46c45078ec285c755.nq.gz
│   ├── 5e3d946d5b5424552bb9c4d54acb985a642b098c.nq.gz
│   ├── 5ed4247193bca5d94ad5faae04fe8ffedd27bbf7.nq.gz
│   ├── 60ff11fe15cffb0525f909dfeb80d5f5766a3cac.nq.gz
│   ├── 64b7aaa842a9c04677e50b9335ecb940be5a2cab.nq.gz
│   ├── 68a9b77eb745d122203baf0e93fb946f12b131a0.nq.gz
│   ├── 6ab804ed8b4e6253e36f158d17e1e7af9a2795ee.nq.gz
│   ├── 6aed14fac5b1ef088cdedefa043b0d15439da461.nq.gz
│   ├── 6b7f79a787459af0edb21685b22763212b007ccc.nq.gz
│   ├── 6c18f3010c7016e13a626032073d73da14f0fa00.nq.gz
│   ├── 6de5a6514f208639f81ac179f5055069e70aa086.nq.gz
│   ├── 6e7dbbc88e4ad67d5ef2c0288ed61e92ec82e7a4.nq.gz
│   ├── 6f667b99e1c5ff6590bcd9bbc47db5358c3b8533.nq.gz
│   ├── 71af67a96ac56fbe55d58679123f350bd1703e3d.nq.gz
│   ├── 7222b79665cc9768f8ab5583f1f4fe7c1adab023.nq.gz
│   ├── 72582c390965d3f65b1791ecc994eaec4799e6cd.nq.gz
│   ├── 73a3bc5fa9e9a631d4f8aaae5cf90f8d5f67fe77.nq.gz
│   ├── 747364b4eb123d7ff4f1a0f82fe3495165a62309.nq.gz
│   ├── 7537e862f99285998c90d430b7d3b19f4824456a.nq.gz
│   ├── 7567737f9fec96eef4462cd5d1427906fa0b2f1a.nq.gz
│   ├── 763b35f00358e24c475defffde4b8bde5cd320b8.nq.gz
│   ├── 785759178b7b111a3479ff1a0a22565393d8c5fc.nq.gz
│   ├── 792da57e4ed6e65f9b9972328c7f89975426d857.nq.gz
│   ├── 79bee1b218fb66e3018c1f415b3e1c6d3658f1ce.nq.gz
│   ├── 79ff42a2d7b4b0ff8ca3c06a73d7addd9fdfd187.nq.gz
│   ├── 7b331cee5d4e88d76fa3b11e90a7548ab566faad.nq.gz
│   ├── 7dafb7760cf0c562298d5858b161d968ff554b91.nq.gz
│   ├── 7f35c5846c3a019520be619dc1a1b14b8f68f7b5.nq.gz
│   ├── 7f90fa07351e17ce9cf0249e1a2e6d7ed3a66d7e.nq.gz
│   ├── 802f045d85f6eccbbc51ee9750a9c74d991ab0eb.nq.gz
│   ├── 80ce2f5c2deffc8e97bdca18de688ecc4d3bf753.nq.gz
│   ├── 834e6d06fc577a939b47c8843be134024fea1705.nq.gz
│   ├── 838f2fedc376f7f8d515ff077ba425e4066c5a81.nq.gz
│   ├── 840b93a5feab49e6ca5f8a147034efc4fe8afa17.nq.gz
│   ├── 85aa3633e5fb04b2798bfde17740d1318ce050cb.nq.gz
│   ├── 876b19803fbe1eb4beee050f6345a1d673df2932.nq.gz
│   ├── 8774b657aff247f43512681faafcfaf24428c804.nq.gz
│   ├── 879af6aa6ccd1b28876c5f6050acdb5fc982b778.nq.gz
│   ├── 880d1a0b704ef8ae52baa033c3aa208b9c51aa33.nq.gz
│   ├── 8862479016db715e8ad1684208dbc5610bf88aff.nq.gz
│   ├── 898e6d2eb1fe6bc2732efb4be092d933716d5898.nq.gz
│   ├── 8aa7daa0e0349dc2a10cd400a4a4d20ad3c8e6a3.nq.gz
│   ├── 8b732fc972fe6d6842bc45298be590b7271c7fc5.nq.gz
│   ├── 8b9c26399a30631a1309ba2459ec42b12762b257.nq.gz
│   ├── 8ca90ffea8eea231199722acfe416c0b31d64864.nq.gz
│   ├── 8e0776c32a125f01ffcc49fee2814157f0f83375.nq.gz
│   ├── 8e4b970bc5e3c66cddb46fe7cce2962e76183c30.nq.gz
│   ├── 8f6c6dbbba434c5d09e2d2b521c7833ce7e222be.nq.gz
│   ├── 9071866dfd0a07a1d8b20dbda1da8cba4ccac939.nq.gz
│   ├── 94b6761145637e28fabe71e6f2235348bc351321.nq.gz
│   ├── 954649ccbe3fe84f8b4b0bf31df0c0d80057a60d.nq.gz
│   ├── 960c191303340682a7a242982507cba4bc3b0359.nq.gz
│   ├── 96453c7a32d6b82809476dc4297b76c194c58ddb.nq.gz
│   ├── 98351d825092cf79a142a9ce20940d884e087a6a.nq.gz
│   ├── 9bbe82d144c11f8b00b484ea5e5389f18ed9515c.nq.gz
│   ├── 9c5f2dc766eda0fbd3d1017e69ae3d0fa7ec2537.nq.gz
│   ├── 9c7aa4731437ff116ba3313480a84f9d9d81dda5.nq.gz
│   ├── 9d4065f2c10235e1a647723557597181a644bad5.nq.gz
│   ├── 9fdcca0b19151bab383deef79433542a5bbcf366.nq.gz
│   ├── a15d0e6cd105cfe760145509f99164a24ec52fee.nq.gz
│   ├── a58766c8cde6f2b3275f9e56311374edd28ce0e3.nq.gz
│   ├── a7cfcb838243f2acc3d05e417585af663b46685f.nq.gz
│   ├── a83483042bd34f8be4dd92f91879542b28bfe9fc.nq.gz
│   ├── a8bc625a4296e81e39a9592ebf545c8be9135ffd.nq.gz
│   ├── a98f0de497ce2b442f85eb11de31fd5c2a4657e7.nq.gz
│   ├── a9d9010d6ad64efa5a2ea7793acdd6280be4e0e0.nq.gz
│   ├── aba7cde7a08c950538d31e92cca73561826a8bfc.nq.gz
│   ├── ac69033329056aa32b721cabde503f7ae86164f0.nq.gz
│   ├── b002fce552e69bce10eb50f3a1cce75fa0cc70d6.nq.gz
│   ├── b047bea63712563367114b413893890bf42a2f0b.nq.gz
│   ├── b17d19ed75518a5cf354477cc77cf14f546bfd69.nq.gz
│   ├── b2004d5dee627dc2dcaf0c1364ec9db0f62f8d37.nq.gz
│   ├── b491e7f1a3e584f7b63284e61c032daa88b5cb00.nq.gz
│   ├── b7463cdc2e01504ac9539d19c8dc020fab79ab36.nq.gz
│   ├── b868a4dcd268e3e915e3288b59930bbcf6c7e82a.nq.gz
│   ├── b973bb8bb91e2c707e830a5ad9ca1ccfa5fb8df0.nq.gz
│   ├── bac24a43d994dcbc87a3336adbb1540bfc5c7b62.nq.gz
│   ├── bc48256f80a08f62daccb4f5f9177e6dfa4a2461.nq.gz
│   ├── bd911422354404eaed76521b4bf1082f460596d3.nq.gz
│   ├── c206c7548784e14a24c4bd1c67ce5e82bf465975.nq.gz
│   ├── c4661c4f7e758dddd8e07f91cbb04c0b6f9256df.nq.gz
│   ├── c5f2732625eb5a00dcde43476e0b1a4f7101e5f8.nq.gz
│   ├── c76a05f56260ac46939f9af73067cafe77ade0ae.nq.gz
│   ├── c7d4bd362b608cf5bf038f21b5bf19d351ac968f.nq.gz
│   ├── c86773882d6be24a8b9b9e71f3a4b845abcd3f8c.nq.gz
│   ├── c8fb2e5c99b620699cdee571be4c16452fca327c.nq.gz
│   ├── cd177bb988544970cdd650d2aa4a903612cc9f4d.nq.gz
│   ├── d06cbc269a62766ec2afd036b2c839db95b702eb.nq.gz
│   ├── d0b12e1d37a4cb14a1fdcda1c86cd5cc697f723d.nq.gz
│   ├── d1bcb009b75769085411a848927b1d13b8d7891f.nq.gz
│   ├── d3d8f330d6dbcabe9b6509bd74a9f82491c1befc.nq.gz
│   ├── d41dc39101ff3285f85db431120bb6a8d0cd68b2.nq.gz
│   ├── d4fa50b77447c2e58afa68126c4903d9ce103f98.nq.gz
│   ├── d5d3a348a8cc251203fcefbdf068ec030b302a69.nq.gz
│   ├── d6bc176a7c70b317c3a9ca9c696871bbdd50e299.nq.gz
│   ├── d6c3e25a99233b282ef825d512f87427b8c26c64.nq.gz
│   ├── d90801409f780a89fcf2c226d33d623019844791.nq.gz
│   ├── d9555e69ee907e69de955590e75c19744a4695a9.nq.gz
│   ├── da22b1ac284ff5642d99b8487768b1bd99791e6c.nq.gz
│   ├── dc0e6760b1c2dc7c9fe4a8cba121ea054def65b5.nq.gz
│   ├── ddc9ab53fd9dcb6304e8cd6022465bc57b15177e.nq.gz
│   ├── df37b0eafbbc7053e9b83eab5abfaf29f79d471c.nq.gz
│   ├── e0553fd93703a81a8cfa6930111721c08f8928b3.nq.gz
│   ├── e06e631883a8a8c7638addd6bdadadaf57c95e99.nq.gz
│   ├── e0ceda927d33d3cc51c5cb79f155aa5d0027db1e.nq.gz
│   ├── e1d76b3dc9d96a7316413caf236bcad67f5ffc11.nq.gz
│   ├── e41abb49391d060d6335af92d80f83dd55ecb93f.nq.gz
│   ├── e4299e6c61542487f138bd31a662d72b5f1dadea.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e80d4947a825517891c50a6d5012ac0751a6d890.nq.gz
│   ├── edc1549e1d06252f817b0c1d146b8d1e4499348f.nq.gz
│   ├── eed2f1eb67be00477ad4edd7bb9bc7e9ca9b78b6.nq.gz
│   ├── f1616fbb140619f8466f79fe4907d326e33c64ab.nq.gz
│   ├── f2e959259a85b259dd1b24d03e23f3a4ac94ce83.nq.gz
│   ├── f5c893bb645605403e10c31a4868812dd6667974.nq.gz
│   ├── f6508e414d26a2bb08ffe326bd4c262790039cad.nq.gz
│   ├── f789f025569d583f01c9b5e6a469d403ff6a5d36.nq.gz
│   ├── f7f814d0021bdda29b7105ce3e57b344f786247e.nq.gz
│   ├── f81111e899a642ab4d3db2badc58a33f5fcf2ec9.nq.gz
│   ├── f8f4d17c5437fbc6bb4a0c174810918f9e8b76f3.nq.gz
│   ├── fa3525ab3147fcf18aab0a0ec12c7e8816d7b98f.nq.gz
│   ├── fa51d5aea69b339cfe79bd9e86d1c458f4a28605.nq.gz
│   ├── fd948be72c4d6bdfd2d55d8277357ba60f7e618b.nq.gz
│   ├── fdb80b7edf3c951d1151d472e6724544b9ff987a.nq.gz
│   ├── fdb9dd84e53a8be0ba92ce4d3cfe74a1a87783ba.nq.gz
│   ├── fddbceb9d9621175671a3980d9056f159612ab23.nq.gz
│   ├── fde14d4e162232a32adcf034aa759453e234551d.nq.gz
│   ├── ff5d9e3323a2edea37d77858fb896fd10e2b3c83.nq.gz
│   └── ffdff319e1748187780da728d95d98ec475980f0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e270500e3efb4ff9cce91416b3f55678d6271811.nq.gz
├── issue
│   └── issue.nq.gz
└── pr
    └── pr.nq.gz

12 directories, 200 files
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

[lmfit/lmfit-py](https://github.com/lmfit/lmfit-py)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
