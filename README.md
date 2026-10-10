# Repolex Knowledge Graph of aio-libs/aiohappyeyeballs

RDF knowledge graph data for [aio-libs/aiohappyeyeballs](https://github.com/aio-libs/aiohappyeyeballs), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiohappyeyeballs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5dc56b90fa56c1126cb019b06452af234a370f88
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5dc56b90fa56c1126cb019b06452af234a370f88
│           └── chunk-001.nq.gz
├── blob
│   ├── 0200e15c1ec4a4547d02f3b3c1402323d8cc9b2e.nq.gz
│   ├── 06aeb0128b1fadcc1b4636bb62dcbb4b75d7f5f2.nq.gz
│   ├── 12f1282150da49109117846332d802e100a74763.nq.gz
│   ├── 1807b8477b7b51823ae218a6bad9379d950efb5b.nq.gz
│   ├── 1d9eee732e497afef4f62be986ef5365bea2aaa3.nq.gz
│   ├── 22b6eba7dfbfc5be2ac97678eb2b8ab2db531048.nq.gz
│   ├── 2d77a1a929dcd0f657bb06e94961e8bb72caffc1.nq.gz
│   ├── 342f40a140ce695f8725b1176b39ba4e823e04dc.nq.gz
│   ├── 43e9ea36f71af2f933398c40252f56cc27fbe4fa.nq.gz
│   ├── 450add9c23a831a23c130bbd30960413018c6fda.nq.gz
│   ├── 4644945a7f52bf5746f09d2490f1beb4b04e74ac.nq.gz
│   ├── 465a19a2f396986b366af19d48ce20b7d6e7e6b7.nq.gz
│   ├── 4ac2dff0eff0dcf75beb33c96b58d0536f868737.nq.gz
│   ├── 5152a8cb2c072722fba569c593523682cb71b54b.nq.gz
│   ├── 56865bef2ff2b48eef458bad4dbf1bbb8c9be16f.nq.gz
│   ├── 56ed82b20faadeb06a57631bcaa96e74c8a3ad11.nq.gz
│   ├── 689414b72f1d54041e654e5b015bcda604e70d98.nq.gz
│   ├── 6e1a37fa62cadf07588c0edb4bb863516fad0867.nq.gz
│   ├── 73b322e057e38969f7e83c755f7acbd3ebb05e7c.nq.gz
│   ├── 78459ec150eafb223a7e64fe8ce0c8aae6958f37.nq.gz
│   ├── 7b81b25290da8c3ab76aadc28c86feb8c323c239.nq.gz
│   ├── 8037cfaae6394fed5b8bc5c96299d603ebfbf5c9.nq.gz
│   ├── 80f09afdd6d5f4cca4d9552653867e2de8e2d6a5.nq.gz
│   ├── 83d6c10b49bed1acae437c15b5366a43890951b6.nq.gz
│   ├── 889a1ed7a718b4c34bfe1aebcabdb59621b49fb3.nq.gz
│   ├── 8d3cf286b9191d3848d25943fe1a8d6354a7f783.nq.gz
│   ├── 8fd29beb8cabeaf6caa1a01483ae01e4dc73145c.nq.gz
│   ├── 954237b9b9f2b248bb1397a15c055c0af1cad03e.nq.gz
│   ├── 9544ea3988752df0aad1a0441326d51bb3569988.nq.gz
│   ├── a1cbd99538532c23b9ef7b42285a51fee8167eeb.nq.gz
│   ├── a46d9bbde42c7b0caea62f3eaaa4ce5fea8dbb8b.nq.gz
│   ├── a4c01ccb2ce32e1115259ef912f7cb6d1a2d0140.nq.gz
│   ├── a9db83877a0a46e2f247dd7ab8ba03f4ec7cefd6.nq.gz
│   ├── b08702f3a296d55dcd6c408b03d7a347e8c30dca.nq.gz
│   ├── b79e1ecf5ed829490e61676b092c56f115e86dd6.nq.gz
│   ├── bb745dc0a81460327d6cc19e5bd38cc44f296fe5.nq.gz
│   ├── bc0a695e90808529fa1c42eba585da4ce975b9f6.nq.gz
│   ├── c1c91be5d0848a4bd743c26167bbf352bbb16d0e.nq.gz
│   ├── c381d108ccc3a576f0cb8d16ad45126a37e6d2ef.nq.gz
│   ├── d4377aabf8674fc734684644855222ea8643c21d.nq.gz
│   ├── d4a2c4405ec2e962c521a13af91bf5f7098a62a8.nq.gz
│   ├── d7b322d104e52579d92dbb5a624dcdb31bd3c72b.nq.gz
│   ├── db42d684e875c830104fddd500b18dd4938ad2a6.nq.gz
│   ├── ddbb24b2af7ca9392125f1823d7d0a7d9db85f31.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eaac4ccc7f237962ee74c1ed0c8c476f49b3d914.nq.gz
│   ├── f26bcf4d2de6eb136e31006ca3ab447d5e488adf.nq.gz
│   ├── f2e6d2208bfdc2787b8b51b9c202247d52996ac0.nq.gz
│   ├── f41038c768b0efa7928be0090db60bab3606a97a.nq.gz
│   ├── fd68ce7758e5aa24bdcb43c5564cb8413c477b00.nq.gz
│   └── ff32fc1e10f54a188bd74398926c82266ca7684a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5dc56b90fa56c1126cb019b06452af234a370f88.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[aio-libs/aiohappyeyeballs](https://github.com/aio-libs/aiohappyeyeballs)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
