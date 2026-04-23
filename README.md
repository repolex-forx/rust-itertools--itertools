# Repolex Knowledge Graph of rust-itertools/itertools

RDF knowledge graph data for [rust-itertools/itertools](https://github.com/rust-itertools/itertools), parsed by [repolex](https://repolex.ai).

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
lexq download rust-itertools/itertools
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a015a6831525ee1637df747d3f530a627d9741bf
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a015a6831525ee1637df747d3f530a627d9741bf.nq.gz
│   └── repolex
│       └── a015a6831525ee1637df747d3f530a627d9741bf
│           └── chunk-001.nq.gz
├── blob
│   ├── 018333d316c1e626b82dadb25b0f8eb63780a928.nq.gz
│   ├── 051b148834815e38f236cf84a9c665fa2b4f68b3.nq.gz
│   ├── 0984c5de963971227b884b00055a13bc97c6b78e.nq.gz
│   ├── 0f6397e48fb9dec83054eaa6b066c5d3b0792b55.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 19b9e19189a5f1346cddff0d9b78ae6b68202f88.nq.gz
│   ├── 1d8a68f83623b294f633a90db599f66fb1e6220c.nq.gz
│   ├── 1dbf6f59dd546b5445cc53e61284c4bca1c2d329.nq.gz
│   ├── 20226d88a00af7d78261a455a67ab6e2a393eb97.nq.gz
│   ├── 2c79c2d842cbc19488ec6cabc248761b7dd0fea4.nq.gz
│   ├── 2d56bb9b224710e4e713a9ccb27b7a135ee7d90b.nq.gz
│   ├── 2eca34712ad56e136f7780170144ec8b96945a24.nq.gz
│   ├── 31389c5fda8b295549e93cded6858ac4823b7cf8.nq.gz
│   ├── 314d4a46ef92728625fb06f86ac9e3e97fa019c2.nq.gz
│   ├── 3240a40eb3cd3d46cc9a1201eee8cdf8dab590d4.nq.gz
│   ├── 3abdda369c909be9a310f0e00c9d057fb3de8f66.nq.gz
│   ├── 3ada0296caac16524c5a80b63bbc82c0afdbfec7.nq.gz
│   ├── 3db5ba021967c82a549ad75007f1073a090d591c.nq.gz
│   ├── 3dcee83afd00b39dba9cc343cea3898a6df7bec5.nq.gz
│   ├── 420da9847af977ea9e8453088459501248db977b.nq.gz
│   ├── 42a452111ea8d87edf60431461633f50e859a2ba.nq.gz
│   ├── 46acc3fcae096086be239673aa46e22dee020b11.nq.gz
│   ├── 48f1e90a647965c6166c004dd0e3d70f0fb4807e.nq.gz
│   ├── 4936160850d716f2f7e0b1431676b480f5bef584.nq.gz
│   ├── 4c6820543caf6849e4de01c0e21c33612c3d2646.nq.gz
│   ├── 4e26b282e853f70ea8916a8286e1409fa80fb47c.nq.gz
│   ├── 509ed7f8abd70c32c6b15c05941d6b1bfa76daaa.nq.gz
│   ├── 53e77b0da46a00eb3272bb7d65a3d0e59b7c972d.nq.gz
│   ├── 54a027551607d7e4a3023b6dc168dae3a18bc6b4.nq.gz
│   ├── 5595b42bacf21de1af9ddb39cdaba8cab74a6726.nq.gz
│   ├── 5847c8f7d1f770551882de4becdf10fc48bcc5a0.nq.gz
│   ├── 5be97271dd80ef0272b673433e33065461113554.nq.gz
│   ├── 5c08456590ebd9e2e1ae1031deb1188a7ccc970a.nq.gz
│   ├── 5c9674e01124ef3cac39e8d0d0248e56d04dc8c9.nq.gz
│   ├── 5f4a605fa251996ce2c652f41b9cdcc0669873cb.nq.gz
│   ├── 5f4f7938ad052e2565ef9d161d3a42d0fb3b5b3a.nq.gz
│   ├── 63f9c48326041df7b29ed2489552675cffc0af5f.nq.gz
│   ├── 672901e7c70aad98e4eeddc893712da42c3b9e57.nq.gz
│   ├── 6b08f68309ab37b31fbb072700a42d36793f4966.nq.gz
│   ├── 6cfead7f2b42d46758ae3fc1876da4dc21fd0532.nq.gz
│   ├── 6f800b6fb6c9070d5af9d97555b1abd793dbfade.nq.gz
│   ├── 71607d0c3c26d5fa19aff16eef1bd71e29aeac58.nq.gz
│   ├── 734eaf6149ac6606858084efbefd927bd4e0a8f8.nq.gz
│   ├── 77192f26eb70646fb17270640ad8b7d8e78a982c.nq.gz
│   ├── 776252fc58d1791863422c7bd9825addcafbb3f3.nq.gz
│   ├── 7d353821f36ba9bc67e512b1e3c67a02b328ee61.nq.gz
│   ├── 7e4ace262b72512ae26a5a8f56fd89abc4b25e3a.nq.gz
│   ├── 7e86260b48f530ea3dcdbb27d0c7e12b927ed49f.nq.gz
│   ├── 86480b19740f316235804c3816123d11eea05b30.nq.gz
│   ├── 86cb55dc007721d33f4570734c92617a367c58be.nq.gz
│   ├── 8e2a9d66cce0f6cbb20d3755d2911a2c23930df6.nq.gz
│   ├── 8e4fa3dc3b1bce9b1eb0c3dbdf214fe21ba6a924.nq.gz
│   ├── 91389a73a7528f1ab458a016d4caaa8e51bca9ed.nq.gz
│   ├── 9203baa055d41d89e1ab8f4d6aa9180a49e078a7.nq.gz
│   ├── 96a0fd69c5bff7cae222bf26278250b5c8802f3c.nq.gz
│   ├── 96ef6c0b944e24fc22f51f18136cd62ffd5b0b8f.nq.gz
│   ├── 977224af29f70aa1d753d0f60aaf64fa7fc3f13e.nq.gz
│   ├── 9ea73f9e8b10cd4b2294d3f005376abd26633707.nq.gz
│   ├── 9fc8b3cc78a56691e179df1beb96b126b07e0c7d.nq.gz
│   ├── a0db15432d854ff87cee72bf61a62ace8dc2fae6.nq.gz
│   ├── a3490e0e07dc9d99f655a73e4f53580c8ead9b7d.nq.gz
│   ├── a9eb4179c49a0537cef133eb6106d618754c91ce.nq.gz
│   ├── aadaa72a766912c0363a94133d1c25d2e60e9062.nq.gz
│   ├── ab1ab5255dd62ee40a5b3210abc938d17f7b04ac.nq.gz
│   ├── ad391faad6487a6b5c9910a5a5e601052e9b0d8d.nq.gz
│   ├── b03a3ef5f2a77621f79b08658822682c1265fec9.nq.gz
│   ├── b44f34721463076cb73c284fdb1079d9c55e848c.nq.gz
│   ├── b7a7fc14115b40a4908d7ee240e8415a9b694011.nq.gz
│   ├── bf835b5d70a173e24fef421187fb238fdba1e97f.nq.gz
│   ├── c0d556fc95b1f6a2ecc66d0dcfef85a1c586f66a.nq.gz
│   ├── c17e752508f87077bdbfd8017d9a12b7bbc867ef.nq.gz
│   ├── c405ffdc7196e97bf7ad61987bda8ecf21cdd9df.nq.gz
│   ├── c559d33adc5dfebf056d4c43dc0d610f0fc0ae77.nq.gz
│   ├── c78b9be698035ece1e0b426863a111acc596f41b.nq.gz
│   ├── d06394ae04a138acaa9885e1e79f4ed1eb7a33bd.nq.gz
│   ├── d4eb9a882e3a3109df6a873e50108a5c70a35c8d.nq.gz
│   ├── d86ad9facd3324f9b7d4768b40eca88b7447cd6b.nq.gz
│   ├── daed31e32da45e63d52fa9d044a3966cc70d25be.nq.gz
│   ├── dc80839ce797e215ae944ac4cf7b64f9dd43b37d.nq.gz
│   ├── df88d803286fe79bf140b9db5d4c6160fad00a68.nq.gz
│   ├── e6694c8e7a326b247e73d9d31df946bd3d06b7cb.nq.gz
│   ├── e6e89555562bcd1a1bbb7a462ad3c58d3b181167.nq.gz
│   ├── e70323f8e6c2c1782acc52d20978756b03c5deca.nq.gz
│   ├── f3259a91901367face0f3cd70fd37d092c28bfac.nq.gz
│   └── fafa5f726131d574b041e6272bc45b61edc932cf.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── a015a6831525ee1637df747d3f530a627d9741bf.nq.gz
├── filetree
│   └── a015a6831525ee1637df747d3f530a627d9741bf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 95 files
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

[rust-itertools/itertools](https://github.com/rust-itertools/itertools)

---
*Parsed on 2026-04-23 by [repolex](https://repolex.ai)*
