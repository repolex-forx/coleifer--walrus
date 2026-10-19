# Repolex Knowledge Graph of coleifer/walrus

RDF knowledge graph data for [coleifer/walrus](https://github.com/coleifer/walrus), parsed by [repolex](https://repolex.ai).

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
rlex download coleifer/walrus
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a1e3b2d103ee1fa6a0e960eaaf204e2139017e8c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a1e3b2d103ee1fa6a0e960eaaf204e2139017e8c
│           └── chunk-001.nq.gz
├── blob
│   ├── 06f1c56e73d86f7100ccac403c026dc91f809e33.nq.gz
│   ├── 0a2b5d60a9c1bc6a800d4127a943d9c948ec63ff.nq.gz
│   ├── 0fa07e8ec3dab2826c16b9d499dea2eb30c24180.nq.gz
│   ├── 1009f38de9fb4f9b2825a83c592b607b4a456f11.nq.gz
│   ├── 1156dae80463fd710d80ea8604d1ba3887d4d7d6.nq.gz
│   ├── 182ddfdc9555cc89d3688bac778599a485f78dc9.nq.gz
│   ├── 1b0061a6b673ac5277e624624b6c9ff056c4c541.nq.gz
│   ├── 247ecda757f0cbdfaec36c1b8153969de953d554.nq.gz
│   ├── 268a3698b2e0a1f5790d2f687d74a2c4de005564.nq.gz
│   ├── 289a605ad343bb8620e4ec0ff3ebc3f2fc68668f.nq.gz
│   ├── 2a67aafa44f011e8bea08db5fc756e3626a896ff.nq.gz
│   ├── 2a806e3b79785b7ae317804fc9ef60527a11e3c5.nq.gz
│   ├── 30b989e8d797f9d265a1e8d9f6a9eafadccd13b8.nq.gz
│   ├── 31aa715733466860a3d43ba232dc01e0ffb53e48.nq.gz
│   ├── 3201a035daa23224603191aff245cf579a19d759.nq.gz
│   ├── 34eb3cf51b0856a1ad912ed4849a057ddfe6c5ba.nq.gz
│   ├── 3718b3d5494c0d1e8ac47df8e4bd51b3de4f7109.nq.gz
│   ├── 37682e06b99352ddb8defe3f7b4519e7d26d3bd9.nq.gz
│   ├── 3975dbe2a7f7de1e9eec0ef01ae3042681e95167.nq.gz
│   ├── 39804b578f753ef1d26b6cc2d9434bcb86f46478.nq.gz
│   ├── 3991d753d87d90f9f9f635241afe5df52157e7fe.nq.gz
│   ├── 4c2c2bc0551366dc247a8cbd0849d81710fa5e4c.nq.gz
│   ├── 4ca230216c329e83469a590409f980a4432720e4.nq.gz
│   ├── 5a92e9c7296f63a4542e7e6e1f5858194e6f31f4.nq.gz
│   ├── 5f00a8da4afc51b0639008d96862bec7faadb7ba.nq.gz
│   ├── 5fc9bb98733f2b4cb2969efffd84e48086e27405.nq.gz
│   ├── 62b2733d49968374f6d7df3a670a8d5faf93426a.nq.gz
│   ├── 647a84c1b8de654641301cfe2f9d5ad1e22fbd87.nq.gz
│   ├── 663e8d1fc107903d4f015d356939a19d37e610dd.nq.gz
│   ├── 67a9d8321a805a3f98ce3e8952295627205f158f.nq.gz
│   ├── 6c932ac8d541fff2994de523e92ba29ffa94fa61.nq.gz
│   ├── 6ebd5495bd333be35c0a80ab6d106a0f25985d75.nq.gz
│   ├── 737bbe9958722f5966ceb77822987b09547986ab.nq.gz
│   ├── 73979c15b446b480bcb0467cc286cd77ac825130.nq.gz
│   ├── 73f38dda9f91ccf1cac67d18d871120714ba1024.nq.gz
│   ├── 780f4a3d122aed6106055e8f3901f1da0eb2c54f.nq.gz
│   ├── 866d1e400f9eee776cb1af860160756fe8291e6a.nq.gz
│   ├── 94b8c19d5fdb9170304ce422dbf15aaef0bca22e.nq.gz
│   ├── 98abc36c2830ef8b210b245f0d3e3dada73afc6e.nq.gz
│   ├── 9c8a582885149cc633fe3d4f89d103236030cc61.nq.gz
│   ├── 9cc06baac8645b5bcf536a468f8210359a6bffc9.nq.gz
│   ├── ab42f84c53c2fe3209dd60914fabd00f4341afed.nq.gz
│   ├── acae2eafbc36ce3975b6bcf18e9b1cba8643a3bb.nq.gz
│   ├── ad718788c3d5c4453f1d2aad49441f69bbbb0e9a.nq.gz
│   ├── af1470838fcd0a11b100ea5ccbd349942b856b07.nq.gz
│   ├── b206b80376e4e349962ed966eed247e6818b6143.nq.gz
│   ├── b23bdc46a8b598c8d19b50bdc38fa32cb4bc7b25.nq.gz
│   ├── b37a007930881f795384b53d2d62d0ec501cf27e.nq.gz
│   ├── baf9ab14d291bd1bd41c88c912ef279a69af3075.nq.gz
│   ├── bbe0b80d98b33e42568da087056b46ce27e6af39.nq.gz
│   ├── bd8be80311bf4fdf57404becb59df579efa01940.nq.gz
│   ├── c01f41c8562646039ec9486d132d5e395b9cff9e.nq.gz
│   ├── c7230007919f9972ae4ebdc1a5edb4d9f2b5f501.nq.gz
│   ├── c752ab3ead2e7be324e5cafb5e1d53135c16af13.nq.gz
│   ├── cbf0ce34f5370f610f373aede1cbcfd7813dea78.nq.gz
│   ├── d4670708d8c838bba907d08700b2223d346b6cf1.nq.gz
│   ├── d62c5b1b4142e7adaba82c6f41689803bf01d3a4.nq.gz
│   ├── de506234d8bd9003561b637ec46d26be78bc893d.nq.gz
│   ├── e0cffe9162e4f630be4037e6e26b6f1185b3bc48.nq.gz
│   ├── e3852db3b1473eb8c0d68ff6e22a1fde87c8e9f1.nq.gz
│   ├── e68e1a156547feadd5338cdb2be71444d76b8be6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73267eeb5a6f628d366ff8f316196cc071fc55b.nq.gz
│   ├── ecbb7b70b2c312de6a4d68c7ab4a0a8aef8bdbd7.nq.gz
│   ├── eec0735c20699fd1c7c4312cc112c0bdc3037e7e.nq.gz
│   ├── f21d8c17c200c0577b3fab9e2675057acf478096.nq.gz
│   ├── f76d57e516aba6f44de564c422de52a269d255ab.nq.gz
│   ├── f971a9f637ffa149072a089670f3c02f41ed6325.nq.gz
│   ├── fa64513eefeb6951c1c794b6aca0e9ccecb7101b.nq.gz
│   ├── fb6a67c7c57de32daa7554f1e9dfcd5e882d10fb.nq.gz
│   ├── fbd028b2d99dba1b87f23f6de65238f80ce2be2f.nq.gz
│   └── fc423e67ea98918ca6467f5c7c0ff66235af4db5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a1e3b2d103ee1fa6a0e960eaaf204e2139017e8c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 80 files
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

[coleifer/walrus](https://github.com/coleifer/walrus)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
