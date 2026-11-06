# Repolex Knowledge Graph of sphinx-contrib/jinja-autodoc

RDF knowledge graph data for [sphinx-contrib/jinja-autodoc](https://github.com/sphinx-contrib/jinja-autodoc), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/jinja-autodoc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b2aaf9fc0e00eff3a03b25b819c111d504e92a5c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b2aaf9fc0e00eff3a03b25b819c111d504e92a5c
│           └── chunk-001.nq.gz
├── blob
│   ├── 004846d8c705ac31404ceb462964967dd7e7987b.nq.gz
│   ├── 0898e7a2a5cc4770ad74d0ea15851daa83d1fa70.nq.gz
│   ├── 08e4fe2c301d1e7abc908dfd16265e154de0d672.nq.gz
│   ├── 0a2fa6c40594864b7e10913007ef7c7b7471dff6.nq.gz
│   ├── 0a634982edccc731ea35f0bbe777638b6cc6bed5.nq.gz
│   ├── 0b2cad68c91eea18d54f553a8c02ba9e7d481731.nq.gz
│   ├── 0c084e8508b3189f51805993c2ec0a756ffb6e9b.nq.gz
│   ├── 128e12bc722d420cae130d7d01a9b48352306373.nq.gz
│   ├── 13179f1418de484ff0b6f8da7d2cc37bd683c496.nq.gz
│   ├── 1ef80f76227e402f20c31bdc1200a6bd75895b95.nq.gz
│   ├── 219b4b27643189575c12598f2b551ec2b329fc2a.nq.gz
│   ├── 2fdf895ffb48b4ec019b1ccc05ed007063c64aad.nq.gz
│   ├── 31373ff8815f58521307d716ff1885463b602e57.nq.gz
│   ├── 3406d0a1d1a04e2f5c94caf8e1e9b6269e1fc826.nq.gz
│   ├── 386dc8f9b030692eb21be1b6e76c6a502ea6687e.nq.gz
│   ├── 3e67ea74e5336faf852b4b8a59ba5f70c1107c84.nq.gz
│   ├── 3f06bf8d86132dc0b84b265c414eed505bf4bb2c.nq.gz
│   ├── 410c3508d39585e797e699543f066a2404727e2f.nq.gz
│   ├── 426f99fc9a4ff1979c5538dba25b1395e1ba2a52.nq.gz
│   ├── 432a16e79dafd95ed8e5cc490d662f35cdb722e0.nq.gz
│   ├── 49ef970c62f8370df520096865ead82941a203a9.nq.gz
│   ├── 4bcd18a7a17d15377637e4ceb26d8d2ba29fbea2.nq.gz
│   ├── 4c05411a43cec5a3f2fc100e533e85a3fdecb273.nq.gz
│   ├── 592ad6412fe42ae4555c3c71a677eeb18a42b2be.nq.gz
│   ├── 5e190e02727d5bd778a3b60ea63b91677e0c34c9.nq.gz
│   ├── 612d4b2c6943060b88d102484e1c7a0169d38add.nq.gz
│   ├── 6ad5d9fed9c8f32f94f0f1aa9616df7c4b2d50db.nq.gz
│   ├── 7643103adde70b797b79de0efcd0bf33914ff54c.nq.gz
│   ├── 794cee42930068eae7e2e12207b2d8d4f914d506.nq.gz
│   ├── 9b6e1cf94dd30d18f5263c443262b148bb3c14d0.nq.gz
│   ├── 9d649d5a65d43472cc9d7b6887c760629f88ccab.nq.gz
│   ├── a40e9a1e02226009014dc95c89f9c9455d866d57.nq.gz
│   ├── a560d7597d33842d3c3e7a19557d43c26576c13a.nq.gz
│   ├── ab8a5e78bb0e905822c338517eddab2171fbca48.nq.gz
│   ├── ac0d3242f0937c7f2f18bfb4b45bed5dc5480662.nq.gz
│   ├── c24afee3f3f24511bacfde3844a1e387dce34897.nq.gz
│   ├── c3d335606e3caad19b5c8ea30f1e70adea770545.nq.gz
│   ├── c4d608abb3f71e27f5aa0d2ebd48718c244d3e9f.nq.gz
│   ├── c5a942fdb0b656e99d16a72aa1bdb5231728ac69.nq.gz
│   ├── ca4da7a7fd2019573906a6752e782908889f71f5.nq.gz
│   ├── cb210c2a41b5efc12cdc7f06417650f33c24fa60.nq.gz
│   ├── ce8803b1f374663180a280e58ec6f6a26a40a992.nq.gz
│   ├── d6ff6b86978a0fdfe9bd0ce874d7763a50004bac.nq.gz
│   ├── dc662eeb486ad1947f8114206e12c0558ed4d448.nq.gz
│   ├── dd02eb9b24a6e7288e2a3988164ce3e91c1370f8.nq.gz
│   ├── e2fd71579b8eb787f603cb0cd2b48c2d0093ed6d.nq.gz
│   ├── e436e23fe0b5cff6ed751936fc409a47f422f325.nq.gz
│   ├── e4fe0c34394be0aa4188eeb33d3c1d175db48505.nq.gz
│   ├── f46ece6242664984e9c57aecf6ff719e5d346570.nq.gz
│   └── f5446d2e90c3690482a8cf102fbb0c30ebb3d9ed.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b2aaf9fc0e00eff3a03b25b819c111d504e92a5c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 58 files
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

[sphinx-contrib/jinja-autodoc](https://github.com/sphinx-contrib/jinja-autodoc)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
