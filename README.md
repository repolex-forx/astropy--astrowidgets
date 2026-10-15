# Repolex Knowledge Graph of astropy/astrowidgets

RDF knowledge graph data for [astropy/astrowidgets](https://github.com/astropy/astrowidgets), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/astrowidgets
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1694d14c9df89ff28cecde37630aea4da5b5e1f6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1694d14c9df89ff28cecde37630aea4da5b5e1f6
│           └── chunk-001.nq.gz
├── blob
│   ├── 0adcc017bf7b74af54f0ebd57fe95a0ccccc19da.nq.gz
│   ├── 0f976a37dad56e0724d671a3419c45e951df1cc1.nq.gz
│   ├── 0fa59f28180b7e104f894478f79eb423811c583e.nq.gz
│   ├── 1138cd73d0da3957b50b0297f2357621f9031242.nq.gz
│   ├── 1142f3e452d693c4fd27ff0af338090f4beac930.nq.gz
│   ├── 142ae9889768143c2d838bb527f295b266a9490d.nq.gz
│   ├── 16217194a93a6d51c2c53697c949abd48515c84a.nq.gz
│   ├── 1a2ae4875fe1a84e72802a559cdc8698c6b1896b.nq.gz
│   ├── 1f3d8757472ac4b757fa9db73e30eee6f72ed8cc.nq.gz
│   ├── 230cd6e20ddda4a66b501be05af441ced411c102.nq.gz
│   ├── 23a9ad555a722f36e030734f0824b895e69d75c5.nq.gz
│   ├── 262b317f3d1fad2e99419e22f6d7af3026ff6aaa.nq.gz
│   ├── 2d76ede36e993bd29b3f89377b51c0c5b9e86412.nq.gz
│   ├── 37d8171d06db1beb53f8d495be1799beb17c91f5.nq.gz
│   ├── 382f6e7693a2a0f3d078984f7e227a8757462a84.nq.gz
│   ├── 401a24beaf53c09ed26b6937b2cb7382c1080a63.nq.gz
│   ├── 43c478b1b26ee2c9c900e000486b070df1a592c2.nq.gz
│   ├── 4a33ae858a6e5e3eaa4f8c49052e0da3d9904013.nq.gz
│   ├── 4af5f04e43832ffa4286aaede790b73b176bdead.nq.gz
│   ├── 4fbf166d49412cae4477e26c095e2c6cf73d5199.nq.gz
│   ├── 59889ac9463a8377cc9cd7400ce3fc34be24211a.nq.gz
│   ├── 6199bfd57204b25309b45735049aeb1cdc701bcc.nq.gz
│   ├── 6260b50bc324129fe8c8e5bedd8030c2808d8231.nq.gz
│   ├── 67b82f693f53cef785f9750c2c65c0bc3c191c8b.nq.gz
│   ├── 6a2d9e7ba207dca6c920b4be99b0cfe68fd0295b.nq.gz
│   ├── 780a44aa04cbaa8ec4bb790efc205d3a69cebd0d.nq.gz
│   ├── 8215fb5426e7f02805189ceb7ca6cd12a4a3f815.nq.gz
│   ├── 838b45731c902e27136554667fb12a421858e8d8.nq.gz
│   ├── 8409d4dc5e24c00261010d0890a727a9dd7fc6d5.nq.gz
│   ├── 8a0ae38ad4998c30957dbae8ed5a41efad81e3c5.nq.gz
│   ├── 8d7bbf481a47ea15640a60ff332748d3e15b7b9d.nq.gz
│   ├── 93dfe92b9c98e009c2f75b6477817411d3a15585.nq.gz
│   ├── 997504b465e8f8c409ebee298542e7e0b8e84d94.nq.gz
│   ├── a84d812b1a943a0ded19ffe56896fa05b733fa8e.nq.gz
│   ├── b701ed3aebdbd1b364a4df4cb135af1f28b61913.nq.gz
│   ├── b777aecaf460b51005b29ad8eb0a8c6e0d8bc4e4.nq.gz
│   ├── b88937ff6121c3073d5b2f2416dcc679c0a6dda7.nq.gz
│   ├── ca4416dcb14ae4b7783605907cfee2ad6cf81680.nq.gz
│   ├── cdf420b7aff37b80e6a2a5a4be071452768e8cfb.nq.gz
│   ├── cf14e8e49e2911a29b62f57f739ea26f995118ee.nq.gz
│   ├── d5bfe98849c26380840d4af98187c2987d865a2d.nq.gz
│   ├── e728adb6bc5738c80d20c78c07330eb1e20bbb17.nq.gz
│   ├── e8461512d40c0e70e2f5ff7f68c9a9439094dbfa.nq.gz
│   ├── f433e12fbbcf1378357a148502a902d60a55709e.nq.gz
│   └── fb03f26e6be82581a39a45b00c82f59717bd983d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1694d14c9df89ff28cecde37630aea4da5b5e1f6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
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

[astropy/astrowidgets](https://github.com/astropy/astrowidgets)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
