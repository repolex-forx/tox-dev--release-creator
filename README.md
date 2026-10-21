# Repolex Knowledge Graph of tox-dev/release-creator

RDF knowledge graph data for [tox-dev/release-creator](https://github.com/tox-dev/release-creator), parsed by [repolex](https://repolex.ai).

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
rlex download tox-dev/release-creator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b3d8b06f3a2fc8d76e9499964879b0974b936d6c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b3d8b06f3a2fc8d76e9499964879b0974b936d6c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0498cee70abdcbe089aa55906d9aa0c008b8d564.nq.gz
│   ├── 0583ff616c7aa4ab09eb9ce1bb263f2816e22ab5.nq.gz
│   ├── 07551e26768f758e1e9990ee958ca375a764e88e.nq.gz
│   ├── 0f09723ec688c1ae52c863073b68b22ec52a66b9.nq.gz
│   ├── 10667674a000637eb85fd2e891b81bc3b4826f03.nq.gz
│   ├── 12a7e6aa7b240f059587704299076ae0f1f151c7.nq.gz
│   ├── 13fb82d505246c3eea2c8e568767e44322c4795f.nq.gz
│   ├── 162c669f9973a55e74e0a74bb7f06df24d0423c2.nq.gz
│   ├── 17d9df0202ef5b4a8ceb229c4fb7380489b54e55.nq.gz
│   ├── 268a8240837fc70e501de9bd672cf93d1d0a4231.nq.gz
│   ├── 275da37fc2a02066a2ebc2c143a0f17e5001b0f6.nq.gz
│   ├── 27c8371449e52faab7fcc3172e5aed86b5f8aa2c.nq.gz
│   ├── 364982344fbd94d55705e1f27a9a87abaa255333.nq.gz
│   ├── 37860275a1a433c6632fdb0d3b19d47389fd8c19.nq.gz
│   ├── 3ca1f7ccfa1c7a52d28c5bd39ecc884f39f708a9.nq.gz
│   ├── 412daaea1b980c1afa75b9c0a96dace7f84b8997.nq.gz
│   ├── 4e9e908497ec2dfe17fa365ea7c57eb5663f579a.nq.gz
│   ├── 599e444d66fc6876b978d2770e35802a714e9f85.nq.gz
│   ├── 5d8e9e96d0e5e99a55c79aea3b8844689da0cba4.nq.gz
│   ├── 5e625d12548d5f0c248e2877da8e029620ba1eeb.nq.gz
│   ├── 655013a51e88e16c3c97a1a75d6bcf53fd5a0b90.nq.gz
│   ├── 69d9eda1dd7f9971d00927bb01e297c17d6b1db6.nq.gz
│   ├── 70a0ee59580d2c63754d03e04bc42579d794e3ac.nq.gz
│   ├── 7b107cea1147cb05b97b6c9426e5b6c2b09dc090.nq.gz
│   ├── 7c4829c466e6c9b4848901266c60beb7ec593e98.nq.gz
│   ├── 859bf89b141247d8213486299be5e123f7b5b524.nq.gz
│   ├── 88af3902823433dda980d769910172784b96bf5c.nq.gz
│   ├── 89806f25f94ee4938ae68117ed96eff7f8717177.nq.gz
│   ├── 9887fa86ae8c16f2b2bf6c9adcbaa7bcd283d2a9.nq.gz
│   ├── 9b254ebd1bcbeb42efdce44c6187b15c53a4ccbb.nq.gz
│   ├── 9d464ec7c8c5ebc45c2e5a403254b46d189ecef1.nq.gz
│   ├── a263012b9fa8ca1f2b54fb9008e180e73415ae98.nq.gz
│   ├── ae8a24df731753980728ea95b89a325128cf606f.nq.gz
│   ├── b8574f68a8550b23bcba933778672ed1a70d0ab6.nq.gz
│   ├── bcbe26b069321a893f7b3d9c62dca176e32f0c6c.nq.gz
│   ├── bfef2eeb0e3aabd4fd08a831cbbcefc56249f69b.nq.gz
│   ├── c00742d23882e93548a01c60d23c7d106944203a.nq.gz
│   ├── c0ea0daa0ae644ac7ce85ed776a70f40a8b07f41.nq.gz
│   ├── caf21e8138fcf0a3bf3394844881f8691b1b4207.nq.gz
│   ├── cb30f0bbcf263001e152db4e0fb834c2c1389c3b.nq.gz
│   ├── cbba5c45427d8ef1ddace00af496785e9a98404d.nq.gz
│   ├── cf027ecc5a0f762369f2974d756f54bc9c8969a4.nq.gz
│   ├── d6455eb45db7b671380f4ca05d89845aeb5e83dc.nq.gz
│   ├── dde3abed88171f9d729feae060d86b75adbcaca0.nq.gz
│   ├── e1cbce8e0cafc7379854cfc67510e25efdcaa953.nq.gz
│   ├── e3e2652efad40798921087fd098968ec8ebb9b80.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ef8ebcf64b5c1e5913abf21e851ae7c7ea2c4cb8.nq.gz
│   ├── f5220a23b2193e82fb2a4cd46a194cb43fb5889d.nq.gz
│   ├── f60b4f7324eedbf00e51d40664af50d66ce09c9f.nq.gz
│   ├── fd53a95e900890e3e06b698dfa33e1cdfc83a8f3.nq.gz
│   └── fda6ee79ad7c8758668895cb77838121c035c306.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b3d8b06f3a2fc8d76e9499964879b0974b936d6c.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 59 files
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

[tox-dev/release-creator](https://github.com/tox-dev/release-creator)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
