# Repolex Knowledge Graph of scverse/annbatch

RDF knowledge graph data for [scverse/annbatch](https://github.com/scverse/annbatch), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/annbatch
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── aa20094e6f8c32755dc0c982d6abf154c59a884c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── aa20094e6f8c32755dc0c982d6abf154c59a884c
│           └── chunk-001.nq.gz
├── blob
│   ├── 002054bd1c692dd9890721e62ee0cd4a4db58e55.nq.gz
│   ├── 00ad6a6ea9418df96256615a564065e38c8332ea.nq.gz
│   ├── 016f81894de7d57e0ac3d92a06cdaa4727ef6960.nq.gz
│   ├── 044f9072f44b8e38d2a2539e088ffd5410b0b3d7.nq.gz
│   ├── 0478047485d964e2c9107e6b381cd2cf4831e8fb.nq.gz
│   ├── 0793e4ea601d8620577780b710a3a6c04628960a.nq.gz
│   ├── 0b77ddca1b9269562e44b8be1062cabfbc1ef046.nq.gz
│   ├── 10207f3f90960fd0e80cb9e6123defdd1760df3c.nq.gz
│   ├── 115240e8331de7d2f53dbd5427abe772ceb897d2.nq.gz
│   ├── 124493bece8bef5020ef3289372da1ea663319f0.nq.gz
│   ├── 1293b4d98eb2c31b5385500b351a4475f2dd3223.nq.gz
│   ├── 12ced9e9ce2e9a92617594c22c7f2c8e451d12e6.nq.gz
│   ├── 164146a8436c478843b08dc71bf230df086a7ec9.nq.gz
│   ├── 165b137b4f22f63024e3551cbb87c1abdcb1d6f5.nq.gz
│   ├── 17570faefdf7a3e8dc94a28145ab74f32c8d4bdd.nq.gz
│   ├── 1e398f5db8478ecdf6bed457952c363f204c2924.nq.gz
│   ├── 1f04e669e1a3b4706d07f9c28c2ddd1327022d92.nq.gz
│   ├── 215ceeb9b20d443c169206d50eae36f5c5f1196a.nq.gz
│   ├── 273b3fb4186c60109702e6c8ddf8b506ed01c7f7.nq.gz
│   ├── 279a9af179269cfdccf4973178f50854a88ba80f.nq.gz
│   ├── 2cd8d50816818338f8cbb196a2993738e9711150.nq.gz
│   ├── 30e830b2ddf8d792b6dc51b31834a9cedd742528.nq.gz
│   ├── 32c07de6ea2dcaafe745662cdd7135778ad55e32.nq.gz
│   ├── 3cc2f31ef62708d0c468c95a1bad4973215724ba.nq.gz
│   ├── 3e324ba2001a0d14a4e309ab080ad453b839c688.nq.gz
│   ├── 433609251879b18ea1b3df70c44a85b4a11c8bed.nq.gz
│   ├── 480749ff0a37dde766fe20c69f500ca8dee6de40.nq.gz
│   ├── 4b59e683a3ed1cc91e8e468fb18a4435f0b95c26.nq.gz
│   ├── 4fbe8690a3b9ced23cbf15b89b00d12bbd6fa381.nq.gz
│   ├── 53f7dabe158fcd6435e7cbcde0d46b252af383f8.nq.gz
│   ├── 5b18ff75dc1e0f77509da4d9f6cbd54e67ee1279.nq.gz
│   ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
│   ├── 5c5e9821550eb1b446a704b1b023aabf0ba08b0e.nq.gz
│   ├── 66678e378b55a7e2b28d2087164af8999aff39cb.nq.gz
│   ├── 6d380fd0ff234e687ff76fb85d08ed189630d875.nq.gz
│   ├── 6fef0679d9431c772d42f56b18cb5669406701cf.nq.gz
│   ├── 72a8cb633b09558b819d8fa7e23e8d1f58a3d83f.nq.gz
│   ├── 74a828063bf308cc36da961d5bcbf8267ad03064.nq.gz
│   ├── 76ff88d0422aef59349ffe3ae7b2ec1b052ac85e.nq.gz
│   ├── 7a06c2fa96eeb750367a55801256a0211ca0b8e1.nq.gz
│   ├── 7b4a0cf87d73bbe25166dd0330e358876a2f0756.nq.gz
│   ├── 7c76084bb425203b99e9031541b59bc021b8a446.nq.gz
│   ├── 7f637d71a274fe11059e410711bfa892c52a08fb.nq.gz
│   ├── 8a67a857175ed53d276fb90a7de86e762d81e9aa.nq.gz
│   ├── 8cc5e85ea94f0432436c5ef3716c20a31024ff74.nq.gz
│   ├── 914ad69d5046bebb8743ad4f7a9f003284d56925.nq.gz
│   ├── 91e60fdf20566d00b898def26964a4c1e226d5e4.nq.gz
│   ├── 9a3f765f27ee420de800302de7ab343d4214f54e.nq.gz
│   ├── 9b108c70239657af34923940ad6cd2f09071051a.nq.gz
│   ├── 9f8f2208c4bdc0f0b0cafb4c0d0b5c79d32c32da.nq.gz
│   ├── a3701c8d27a12cb107a8ba62923aa53de96eeb6b.nq.gz
│   ├── a7c05e7725a516d01e88033227c19eea8b549a25.nq.gz
│   ├── aa2538830901b3d66bf70b830dbf148c665264c5.nq.gz
│   ├── ab9989ceedf58e36986d516bcf2884d9a47c44fe.nq.gz
│   ├── ad4b05233b911835b3989ffa238347f1e2a4555e.nq.gz
│   ├── b05c97d9a03c8429e5512567567576c0050891b4.nq.gz
│   ├── b230dabb5419bef1cd7bdabb33288156b150e1d5.nq.gz
│   ├── b25e9c150d4975d39c70c505f6d4b0ed5b11809f.nq.gz
│   ├── b2a69a623eac9f9ca42bef08603534d837ef6ca4.nq.gz
│   ├── b46451619d23d026c2928c17895ab996dc6247ea.nq.gz
│   ├── b85509fe73433bb8672739ba931f2e3cd02967e4.nq.gz
│   ├── bc0277cac81fd38f208bb4009901ee14f3833a6b.nq.gz
│   ├── beb02973edfa98563d24f74174a9b51733f1c988.nq.gz
│   ├── c1e8a19f01e2d7b436bdedc49656f39bf3f40068.nq.gz
│   ├── caaeb4f73220343cf55564c4b747c6434c231fd8.nq.gz
│   ├── cc32eda8a90cc20e1e9fdc7039b83be81e3d1445.nq.gz
│   ├── cdd2808258093bad6e3c16efc8614f6f0c78bb28.nq.gz
│   ├── cf1158369a49e2ef386b32ebf466f9d46da7473a.nq.gz
│   ├── d25ed8851e869b47c82d1bdfa8d42b9934f06fba.nq.gz
│   ├── d49323359aabd491f2eddd61ce6714e44cfa4e1c.nq.gz
│   ├── d70d5120cb5a828b8835481adc99a483f480071c.nq.gz
│   ├── d9e79ba64848091a9bccd21dc241c61c669dad7f.nq.gz
│   ├── da44adb2b93a50ec9e473a7c1e5ccf77e34e5f4a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e80a57b48872de6448c5bfe34df21e7dbd1c440c.nq.gz
│   └── f5a8e0395f47380b5adfbf550f4ae0e2909b415c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── aa20094e6f8c32755dc0c982d6abf154c59a884c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 84 files
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

[scverse/annbatch](https://github.com/scverse/annbatch)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
