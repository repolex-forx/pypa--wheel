# Repolex Knowledge Graph of pypa/wheel

RDF knowledge graph data for [pypa/wheel](https://github.com/pypa/wheel), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/wheel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4ae6d07d38611cb0619864621c06fc032622eaef
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4ae6d07d38611cb0619864621c06fc032622eaef
│           └── chunk-001.nq.gz
├── blob
│   ├── 0294cb3c1ab108d4b09245f5dd14ad1a1582ecad.nq.gz
│   ├── 08e173b124352712d88be1cb628e8accc98e2998.nq.gz
│   ├── 0b1a03480a3883d3bf0870a003cd9dd0421980e1.nq.gz
│   ├── 0ebddc06ca9e8f043b2b3ae5e928a2adefa67b69.nq.gz
│   ├── 1b74b211e11f63ac861026b374cedff5f5ad96a2.nq.gz
│   ├── 1dd2503397aa2b6dba4f5d7dfda9faea820aea5d.nq.gz
│   ├── 24199c246d44a6874ad991c2f3492ca30fc10f27.nq.gz
│   ├── 258bf5d757ba50851300b8328b7d72ccd457ebec.nq.gz
│   ├── 27ad47a28601e939f11714c49c809490d10763c3.nq.gz
│   ├── 2aa2212ae94b7e6bb9d444e93c5ed46105447429.nq.gz
│   ├── 3153a260bbf05b9e01ebd881b9fd200165609bcf.nq.gz
│   ├── 364d950687435b269e06ce133a244db590888cc5.nq.gz
│   ├── 394b1dafd5c5f27d63ef7c2e3aa072b5b48618cf.nq.gz
│   ├── 4306c9aee63dd9a5275f554a8e5c4f40aa2e74f8.nq.gz
│   ├── 49bf571053bb510d4822b6ec15a59c9a743b8928.nq.gz
│   ├── 4a0ebc98b917b754d03218f2b25b9507b12000b9.nq.gz
│   ├── 4e65b45b727e448536afc21b65b7ab2110403b55.nq.gz
│   ├── 5164d0082e2027b98631a1ad5928a82923a0cbda.nq.gz
│   ├── 547f66ef594dcb73a4dd861e27853144eefe79ed.nq.gz
│   ├── 54b44f927759acfc60f3578ee26d71b20b75c155.nq.gz
│   ├── 568df1fe47ff5077c1da0c3ff4c1a66a47b89dea.nq.gz
│   ├── 575fbfb35105eb82faee5a368781ecf818379354.nq.gz
│   ├── 5d139d9450ca1dd7d0239c0986f659966d37a324.nq.gz
│   ├── 6873ecf9bb7172ca9debb3a55813e0ca391b9a39.nq.gz
│   ├── 755dd149c76f16b39251d5602322b1ffe20293d1.nq.gz
│   ├── 7588eaf50ef91333bbb77061bffa5b0f8da53b07.nq.gz
│   ├── 76e798b37e0298faa8b67ea02eb858fd05463374.nq.gz
│   ├── 79a860401df327ab87e89070658aea06c8808b1f.nq.gz
│   ├── 7c0d31d29c3f6ba2123a668cae42731ab6e083db.nq.gz
│   ├── 8083236d7466f8969eae8ddbf0514f10139c7a1d.nq.gz
│   ├── 901150a3f168c9a71f1a439e7ad46ba58a783af3.nq.gz
│   ├── 972b43241952b214de4c9a2753d7517790e2f79a.nq.gz
│   ├── a1a2482ba29ac5290c8f7d7688452ec3faf59332.nq.gz
│   ├── a31470f14c5978d5fcc3bc173b8399b6c9a6443f.nq.gz
│   ├── a6f1c6e349fc57e9f94990fc64c7e76821ab10d4.nq.gz
│   ├── a70b38cea52b8aac4e97f8b7df7062369ae21ed5.nq.gz
│   ├── a735a489589fb97ec33b072f7cbe5008ca0e4b0f.nq.gz
│   ├── b7a0e19a2b018ce3c4f834869c5f68131251ea9c.nq.gz
│   ├── bb96a2ac706b8504c7c2556df20fe35eea02a083.nq.gz
│   ├── cb499c9457ce48be18a8d30c6efd74287fb8c9ad.nq.gz
│   ├── cbbf31121c0d83713603d98f9117a32f002b8786.nq.gz
│   ├── ce9a58d3b945a810109aaa3211f091630c19d72b.nq.gz
│   ├── cf1436c54a9ad1f77fb1bc10c7cf3d3c0cd2cdc9.nq.gz
│   ├── d422120a48ab81d02c77d8f221ce74b44bb5813d.nq.gz
│   ├── d4fec85dfa205257082c1905726cdb207adbd935.nq.gz
│   ├── d6b0a3fb869be314c13c1a894ac1209a81b1a09a.nq.gz
│   ├── d7fa45bcbefd230cd3e05e50f9919855ba7d0603.nq.gz
│   ├── e17a7b924526b9fcad83fc44996f17695dea0161.nq.gz
│   ├── e27900a2565c859ff32b0e4bf497c2548e4912de.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ecf1094b4f34991766ca20f1d5437841a3033fbc.nq.gz
│   ├── ee76f3cee0ed18eb6028e84c8dd5997c1f73f88d.nq.gz
│   ├── f8c7e104479ae51f034f5ecd2517edaa344ac36b.nq.gz
│   └── fb857f4f08cbf3a01f7cda6600ce8490e5debaa4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4ae6d07d38611cb0619864621c06fc032622eaef.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 62 files
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

[pypa/wheel](https://github.com/pypa/wheel)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
