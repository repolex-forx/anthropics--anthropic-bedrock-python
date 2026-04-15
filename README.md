# Repolex Knowledge Graph of anthropics/anthropic-bedrock-python

RDF knowledge graph data for [anthropics/anthropic-bedrock-python](https://github.com/anthropics/anthropic-bedrock-python), parsed by [repolex](https://repolex.ai).

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
lexq download anthropics/anthropic-bedrock-python
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 92c120f211599ebd072f27a8e7b1300d923392bc
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 92c120f211599ebd072f27a8e7b1300d923392bc.nq.gz
│   └── repolex
│       └── 92c120f211599ebd072f27a8e7b1300d923392bc
│           └── chunk-001.nq.gz
├── blob
│   ├── 02a97151176a85d254e9cf0c6e152070eae3c96d.nq.gz
│   ├── 06d5358bf73c56935d8b3eb27b25359d620692d1.nq.gz
│   ├── 0ba95906ce251d8dcd6e6ba44ad58958d5f24ad6.nq.gz
│   ├── 0bbe5384385f24742a61c852ba839b1920439b1a.nq.gz
│   ├── 0fb811a945c2804ff1ae664421bf4c4b0aa98ab5.nq.gz
│   ├── 1016754ef338bd223626a24f943342edf45f88aa.nq.gz
│   ├── 12a2db5597dbf2cc5d5477eea19d02d9b308fd9a.nq.gz
│   ├── 13a54dadf9f11985757d970de39a8609b6d3aca6.nq.gz
│   ├── 1c3db4878765facfa7304fb98fe44f61705c8939.nq.gz
│   ├── 1c5c21a8ea1a4e6d6549319513fc26025569018f.nq.gz
│   ├── 1ead081c643a0849bc5d459f2ba98a3dd92d5ebd.nq.gz
│   ├── 21d727372affd23016930ac8151aa7e4386b2a4b.nq.gz
│   ├── 274320ca5ee8fe4200ac4e10cb4809b773dd1e18.nq.gz
│   ├── 29a6416d5dd4826afb1478a6875d08923a26940b.nq.gz
│   ├── 304ca885480a7c0954229f79a0ea37d935278ea1.nq.gz
│   ├── 3234df85507c4e9e8db06025b0045fb04d04e484.nq.gz
│   ├── 34171e26f29af754102a4fb66080a0f7d0a9c559.nq.gz
│   ├── 37b3d94f0f82eb736925fb156297c644a67c524b.nq.gz
│   ├── 38614663491103173bad75533737706c75995908.nq.gz
│   ├── 3a1c14969b1808703ff490ac9f4f04dd66864908.nq.gz
│   ├── 3dd4f899c2545e8844d7b457d679f123a4515138.nq.gz
│   ├── 43077b246094f0b2ea3a54995d76fe1d320945a1.nq.gz
│   ├── 455d120d0f756bd2b856d3c730aa1f5a9350eb45.nq.gz
│   ├── 48d5624f647d518f90cffcc7928c6cea0478d42d.nq.gz
│   ├── 53bca7ff2aa7e73b6353d977a14c0d3b167f7135.nq.gz
│   ├── 57d2be0f4f5165e69ff34fb3337aa4e37cb1dd9b.nq.gz
│   ├── 595924e5b19f87983bda9644de66a72bcce0b663.nq.gz
│   ├── 5bed5e755176444ae8c10e52d0c3b2ef3d090845.nq.gz
│   ├── 5e2c99fdbefc565576f8c5f37b0b0a66d60f2015.nq.gz
│   ├── 605c9a80b161330bfe75d6457f6e64f90c1ff9ee.nq.gz
│   ├── 60ede7a84281cfdd206114c6f582b1b88717d35d.nq.gz
│   ├── 615ba7a7129502a4459600cb06ea0d0bc3a065f4.nq.gz
│   ├── 6538ca9176e350f8e9b2cde03e186b03f7240e0c.nq.gz
│   ├── 658f8463294442e42689ebc43d3398c85f0f4cbb.nq.gz
│   ├── 6b2889d6cb9adc8325e92a1f5c302fc4d59bff39.nq.gz
│   ├── 6eb007253cf859521d792f4e93a2a78f2102c0a7.nq.gz
│   ├── 6f05efcd21107ec876b98e5ca968401f89a4d4b7.nq.gz
│   ├── 6fde42ee5408c8bd39db05882bebbf2a54a10ec0.nq.gz
│   ├── 74c7639b4cd52af36d3ef3350574bf7287633def.nq.gz
│   ├── 76409d00b9923ff8555192ae54a993a74e3e921e.nq.gz
│   ├── 7c8fc4926b9022b962012f0a7454172e334fdc94.nq.gz
│   ├── 81914c9d1cdb6aa8bcfae4fbedbf988e292d2f21.nq.gz
│   ├── 826054e9248cc9c66c7743ac7483c0fa1da683c3.nq.gz
│   ├── 84099e551222ce932ceec9edb4417e550db01476.nq.gz
│   ├── 8ac408a63eba53ab5ad9b37ca0631420314ee7e3.nq.gz
│   ├── 90d4af38aa0147ad9703e4831fce9cec61616aed.nq.gz
│   ├── 9275b0664722dfca92ed190cb94c194f9e834055.nq.gz
│   ├── 9644d1ab76d0002680c645370b4530dbb1c9e5c8.nq.gz
│   ├── 979e0ee0b145f07dbfb0c0e6d3002f6bc33a82b8.nq.gz
│   ├── 97abc8a1de22a3490128f6a43218fb31acb41be2.nq.gz
│   ├── 9921297ba949f94462274f51129f13658bd44323.nq.gz
│   ├── 9925ed50a44cdd32219e7b090d23439b360135fb.nq.gz
│   ├── a4b2f8c0bd318fbe2df0630c083f23b90ac6c938.nq.gz
│   ├── a56395043bd8fe4e281ce8b6664ce9bdb3bfbf0f.nq.gz
│   ├── a6fa34950d116670ba65e1e11adb4836cf2da25a.nq.gz
│   ├── ac71a66cf790ec2b4cc699891aed7671a6233dd7.nq.gz
│   ├── ad9f9a8206d8549a5a39ed4b8d1c26d6e4390c30.nq.gz
│   ├── b2440b3908809611da25849882d5f634aad337ac.nq.gz
│   ├── b6e8af8bdebf0453862f2296b75e46550cdc41c6.nq.gz
│   ├── bbeb30b148cead4b52d4ad2166ada5f51f707ed8.nq.gz
│   ├── c0ca700ec43063c3b9a96f5001592355081aeaa5.nq.gz
│   ├── c1d1ebb9a46db7a17e7c9ed6ca95dc88b6247cad.nq.gz
│   ├── c2d26b003f291e017ed88c39c50aeba83498ea13.nq.gz
│   ├── c3043e11de286d7a934ac5f2c3949660fc57745e.nq.gz
│   ├── c3622728d92ac70d3ee1a8dcba07706117b52e52.nq.gz
│   ├── c5f55dbe663d91a3d5211ca5871afd11e899c41e.nq.gz
│   ├── c832ed3d3a2e2a0b763cccb0e24fc30c1f2bca02.nq.gz
│   ├── d10da4dab37b710de821f91d14c712df869b8a65.nq.gz
│   ├── d41f862253ac067fe270cbf0b061bde316aec152.nq.gz
│   ├── d78eb2701765955f109b8cb7ab7d5391660d4cd7.nq.gz
│   ├── d7e5127dd82712d9eff2f77baa302310c8c9e849.nq.gz
│   ├── d8c73e937aeda0534b48d146e2816d5000f0680b.nq.gz
│   ├── e03f417a0c24ee5d6ed057510b70f9e2659e26c3.nq.gz
│   ├── e1b8b6cb39b24374814405174e87a1a9f67b7560.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f28b96aad86b90276c5aab7ecab459c68a445180.nq.gz
│   ├── f4a0208f01c069616000eeed319029fc92c03b56.nq.gz
│   ├── f64a055402061f7636546fbec2d7c6515441e95c.nq.gz
│   ├── fb5d912d786083a40f39777d88a0b07926c09aac.nq.gz
│   ├── fb6ee582e516c7b81dbfe9c43c7439637402fd2c.nq.gz
│   ├── fbad826ef8b257d219f3b71fddd99412427e3694.nq.gz
│   └── ff3349499be851375fe45b4a9f540ceff2cbc9cd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 92c120f211599ebd072f27a8e7b1300d923392bc.nq.gz
├── filetree
│   └── 92c120f211599ebd072f27a8e7b1300d923392bc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 92 files
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

[anthropics/anthropic-bedrock-python](https://github.com/anthropics/anthropic-bedrock-python)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
