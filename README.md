# Repolex Knowledge Graph of psf/bpo-django-gae2django

RDF knowledge graph data for [psf/bpo-django-gae2django](https://github.com/psf/bpo-django-gae2django), parsed by [repolex](https://repolex.ai).

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
rlex download psf/bpo-django-gae2django
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a949341b00639f1227fcd26b9ca65bf6027aa3fd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a949341b00639f1227fcd26b9ca65bf6027aa3fd
│           └── chunk-001.nq.gz
├── blob
│   ├── 0183cfa2e536d101e29b726a015a6c195ad3286a.nq.gz
│   ├── 01ac9c01177206a598d53988d90defd710bd7b75.nq.gz
│   ├── 03aa052b08969c68fb4c3a12777e896788abe440.nq.gz
│   ├── 064824cdc5be3cf1fd2141783fcfff7cbc15bd2b.nq.gz
│   ├── 091c8cac7551380ec146aa0e5d70de1438e7e073.nq.gz
│   ├── 0bbaba6ab56b7353fa69e5fb6f32b30a33456f10.nq.gz
│   ├── 15d668b05eb200887687f2cb7036b691d7be3087.nq.gz
│   ├── 1c5fb569a81669414f156e0825a14eb6bb612c6b.nq.gz
│   ├── 20abb96eefcbcddefd7e3cace2799832c75ef887.nq.gz
│   ├── 289471d8da0879b050b41ebb52f8e49b042f3713.nq.gz
│   ├── 2c09dc4c3a01bdcf4c7f5b7f557550ed0f00caae.nq.gz
│   ├── 2e6e20e6e11cea459643241b1ea2afb1a1fc3d96.nq.gz
│   ├── 32d87645b4bfc00ddf96d863d6bce32d33d833cd.nq.gz
│   ├── 36efc90c5d2988734dd435c0002dc1af505ccec9.nq.gz
│   ├── 3cd231f5cd90da210740d32c4b97592a6e426a35.nq.gz
│   ├── 3db81911591cf7db62ea9a321497d44bb4cc2036.nq.gz
│   ├── 40fda4f59504cd8095b94b783dd63fb9f8c78629.nq.gz
│   ├── 4677dee27afe411ba2325f5d6b7281a1d02c570d.nq.gz
│   ├── 5e749b9825f64786cac56b7d99f33ae314ca4ed0.nq.gz
│   ├── 60d9420b2230fd3d2cb160f6ac7ec16cfe8bb904.nq.gz
│   ├── 682de3e903786a3edb4f3764f35e218fb225b0a8.nq.gz
│   ├── 691be181455c84db4add5b220e8207445093ecbb.nq.gz
│   ├── 6a944205cd8d04bf3f6d7a652e834885bb62286c.nq.gz
│   ├── 6def8f22636bf06ad185e41c352a9da3bdae4b7d.nq.gz
│   ├── 6e537505edec10116983e9b4475c9806cad9331d.nq.gz
│   ├── 6f6482abd796dbb4cb8418075bf4b85ac4617c3d.nq.gz
│   ├── 71a836239075aa6e6e4ecb700e9c42c95c022d91.nq.gz
│   ├── 765eb6e3752435e8a961dfcba15ad746d286f536.nq.gz
│   ├── 768b3e0d21784f4d9c23e0003e340d48789c5eae.nq.gz
│   ├── 793c08b297a4fc66ec6d6946696439338f80850f.nq.gz
│   ├── 7df7e58153bebb8d522a4cb6421674396f7656eb.nq.gz
│   ├── 87d0cbf2ec4359808919c0c56bc923bd49b5b6e7.nq.gz
│   ├── 8c391df9761d7db2a473f138717b83d7bd7251ac.nq.gz
│   ├── 8c4d7be08f0468c6ab5d8b3913b2d0d802081895.nq.gz
│   ├── 90501e7f7951cb3ea890849535758bf137656f8c.nq.gz
│   ├── 907463a1aea80e397244f9d83518468713c03aca.nq.gz
│   ├── 9080e9d0ab034e313c25a0667247de2a122ece8b.nq.gz
│   ├── a18b8052f99c6b564a9979de27ac9e895d76db3b.nq.gz
│   ├── a80d8c76dfddd017b188a93d3a7cf110d154e4dc.nq.gz
│   ├── adfc787f83f4ef3a368416d851de7da26f044d08.nq.gz
│   ├── b0185765b9d1d8005169e8223ed035eb705b8a34.nq.gz
│   ├── b10a43c15e0fd428fd3bd49636e9655c7b402e2b.nq.gz
│   ├── c70be8a8e7e8effbbf0a80ff932687bda446c551.nq.gz
│   ├── c72bd91e594aa2ba4117448e8a473166693169de.nq.gz
│   ├── c795c2cb132b507172c0d4fefa9bb1fd8dff2e32.nq.gz
│   ├── d23a12739daf621da1639902a5606f266b4b984a.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── ded0126b755100564a313868b397b03694af0a3d.nq.gz
│   ├── dfebd5dc989813f54e89aef4bb0efedaf6a0480c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e93300695ecf3e52d8caa286894d985c0755b533.nq.gz
│   ├── ea598a48849ed77d818c73689cfae504181766df.nq.gz
│   ├── eb762f31a1a90b43dbc77f39742169caf069863f.nq.gz
│   ├── f09dfad2d0bae841f2e8c18cd66755973edd4fd5.nq.gz
│   ├── f5b27b405812f95d718651e1710590e23e160d77.nq.gz
│   └── fd34d7af4b40b9f2714851c3bec4ffa917f6b0fc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a949341b00639f1227fcd26b9ca65bf6027aa3fd.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 63 files
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

[psf/bpo-django-gae2django](https://github.com/psf/bpo-django-gae2django)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
