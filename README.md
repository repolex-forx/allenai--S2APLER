# Repolex Knowledge Graph of allenai/S2APLER

RDF knowledge graph data for [allenai/S2APLER](https://github.com/allenai/S2APLER), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/S2APLER
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bb4bfbcea7f7037fd0d5e4d86033690ce5f81399
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bb4bfbcea7f7037fd0d5e4d86033690ce5f81399
│           └── chunk-001.nq.gz
├── blob
│   ├── 0204eb2a6e17dd3677a381134c876ef02f8d99c1.nq.gz
│   ├── 02199f6427e207fc0e65700e68bcbbe669b47f21.nq.gz
│   ├── 08770883ad33e5561f64fe2152e81f6577f53b6d.nq.gz
│   ├── 0bc6a0ccad101fbb9b9d0d9d3bcc690e8c921d93.nq.gz
│   ├── 0cf0aef171cd023a8332cb4ab21205d541f78ef8.nq.gz
│   ├── 0e2a57cb0436cf12861cb192e4afd36ea9dbbdf1.nq.gz
│   ├── 0f17c7df241f5dd3de0f1aa7578982e94493a947.nq.gz
│   ├── 169aba4de10927088f16ed4dbe131a90058cbf42.nq.gz
│   ├── 218282ce9cb7e80ca3951ec18b99e20693e4d9fa.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 41264e966fa34e847f6f200ac11451b3f17844fd.nq.gz
│   ├── 42331599f8d46884cad0c1c4024b80fae1b0b06d.nq.gz
│   ├── 46c4c8557c9e0385ade82cc636b7cf8c36d619e2.nq.gz
│   ├── 49359bd4f9d602394dc7c93d34fb8fa1c55c3880.nq.gz
│   ├── 4ebda213c4554d3bbb101aa03daad4bc86909d5e.nq.gz
│   ├── 52bb52e4ac270db530eab1ec4bbf7eb8f0be9d72.nq.gz
│   ├── 5c31ec8b1c64aca4dc45806fe1ca79fee43058bd.nq.gz
│   ├── 5d9b14e20055878fa3e995f064639ce1a170583d.nq.gz
│   ├── 5db86af9a5898afafa24fae442535673d7f9aa90.nq.gz
│   ├── 6cd51c4bb6b76117ea307fa98115a99efbdd35ca.nq.gz
│   ├── 6e80a91b865c43f52dca9795dc86007d097d4799.nq.gz
│   ├── 72589a69aed12a1393ce8009bf7735ca8a8cde44.nq.gz
│   ├── 780dd16dc4494285d3d75ce752051155e41df9ae.nq.gz
│   ├── 8ebe7d280aa861dfa8697e009a2a35613ab2c552.nq.gz
│   ├── 94f19dcd0fb87e3a860c339781fa6e1f3a717db4.nq.gz
│   ├── 984c8a7ee24bc6d4ec871f0cd5bd202440e138d0.nq.gz
│   ├── 9a55ef494571f68e465fc45c839ed68a063b6097.nq.gz
│   ├── 9ca9519baf5c4afb6af44637ec58a7ab4539f79d.nq.gz
│   ├── a2728bb25afcd3e8946364e216da28da4f2e027e.nq.gz
│   ├── ab03513dcd735184441a23b3fa973013db968f4b.nq.gz
│   ├── b76e60cac31362ed66767779b536ccb9b343eeda.nq.gz
│   ├── bdeb271c1217db030413d3fa1b1e6d3ae5328932.nq.gz
│   ├── c2d68ca51a0f623f961fa2855729c09d7dda469e.nq.gz
│   ├── cd663e6d0f0c4a53cf0d2b7e47d2800092e80eab.nq.gz
│   ├── d8c36959378ea659fe4e63dc462497b071847c76.nq.gz
│   ├── e423f2e75f58f790e43a0f006be7003d6d2deaa0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ebb2ed07c0c74fdfea8ee2bdd1df89c242737b0a.nq.gz
│   ├── ebbfccce215d37250d85e7bc4e46a2c38b5346ee.nq.gz
│   ├── ecc3f56b46bc9d21da76c24b4889fdee310f0a27.nq.gz
│   ├── ed12ab87820a666db1bda9e7805d957893682c09.nq.gz
│   └── f54521df2ed1eecd4a296c50b6cc9623ef9ffcab.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bb4bfbcea7f7037fd0d5e4d86033690ce5f81399.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[allenai/S2APLER](https://github.com/allenai/S2APLER)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
