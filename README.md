# Repolex Knowledge Graph of encode/httpcore

RDF knowledge graph data for [encode/httpcore](https://github.com/encode/httpcore), parsed by [repolex](https://repolex.ai).

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
lexq download encode/httpcore
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 98209758cc14e1a5f966fe1dfdc1064b94055d8c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 98209758cc14e1a5f966fe1dfdc1064b94055d8c.nq.gz
│   └── repolex
│       └── 98209758cc14e1a5f966fe1dfdc1064b94055d8c
│           └── chunk-001.nq.gz
├── blob
│   ├── 033acef60f3fe2d863b8143f71e0081111bb2a06.nq.gz
│   ├── 0ca215567432cd8e6c4bdfba43743ecb72e8e93f.nq.gz
│   ├── 0ca96ddfb580b19413797f41e79f7abcecdd9d79.nq.gz
│   ├── 0fe9b70de62e9a10fa1d80f9677da903ef10a6c5.nq.gz
│   ├── 18dfb2809ed9fe1f1a66e5c9e6940feb5afaffa8.nq.gz
│   ├── 1970531d5c376c493397c4c84aa1bc0c795d88db.nq.gz
│   ├── 1bdd99eb9ae503f5a5cc5543c73b5368d43e3d21.nq.gz
│   ├── 1c4a3228288f28c10b8603dc6d5d34c46a5fd4b1.nq.gz
│   ├── 1ed1e52d006ab6fe06f7bb5892397e458b7ad793.nq.gz
│   ├── 25146d0cf9abd7c1c53620875b8d30d48388a7aa.nq.gz
│   ├── 2ecc9e9c363e2f16c4f934cf41cf871826d6a495.nq.gz
│   ├── 2fc272049e3684877fa3a6ba1e86290aa2a39f47.nq.gz
│   ├── 311b2b56c53f678ab95fc0def708c675d521a807.nq.gz
│   ├── 361583bede6b2b84088b38054d5d8116ef9f1597.nq.gz
│   ├── 363f8be819d2576ea65365e625dd1596ea40429a.nq.gz
│   ├── 37c82e0253d0d168cf173aed3ce58952accb3937.nq.gz
│   ├── 3806da0f11c93d5b7d80f3384e23e9c8f57c60e4.nq.gz
│   ├── 38b961d10de88bebc98c758d0d1f14af1e7c0370.nq.gz
│   ├── 3a639f5e01355e1aa474cca90e071a37bf23cd8a.nq.gz
│   ├── 4018a09c6fb1e0ef1b03ab8d84b13ebef4031f7c.nq.gz
│   ├── 4567ba44b402b1f03f5744f88d9f2d49d608a485.nq.gz
│   ├── 49e14ccc8ddce6b1390b122f4a9cdc18cd1a41b4.nq.gz
│   ├── 49f0e698c97ad5623f376d8182675352e21c2c3c.nq.gz
│   ├── 5a5627d71ddedba610155864135273b776ea4088.nq.gz
│   ├── 5dc9a10b4cbd4236970c11e8116f11fd6bae3a40.nq.gz
│   ├── 5f1cd7c47829ce17dbcf651ab56b4ffdce04a485.nq.gz
│   ├── 6315762f6a7c0258f372544996f2ebdc28fb4ebf.nq.gz
│   ├── 63ef3f28e4ce810a043818a1c4c49183ff57c1e2.nq.gz
│   ├── 657ded0442292c6814d885c6c466d68f92168c34.nq.gz
│   ├── 66a7c7b548fbda277fbe7d517705e157f8876dbd.nq.gz
│   ├── 695359bd634e3a0393ee0455c5843197ad737a99.nq.gz
│   ├── 6f53f5f2a025e01e9949e2530bd9ca6928859251.nq.gz
│   ├── 7118a3644112e0b2a4f4b469fd9aa276596c85a5.nq.gz
│   ├── 7919a54cee55b5b5f02a28f78e6fa3d0d1148f7e.nq.gz
│   ├── 7a24a4181bc0e75ec08476602407ae22fff4133b.nq.gz
│   ├── 7dd6e419d58cacfbf0caf1012029dcf542f938b1.nq.gz
│   ├── 84a984b80df7ddf6ff02b47b01f215d9c027c544.nq.gz
│   ├── 87f0c0740c74bfee5b535067b170ef932f843ef0.nq.gz
│   ├── 880330c6f25de57ad2c54d587b530546575c38b6.nq.gz
│   ├── 88dc7f01e132933728cbcf45c88ce82e85ddf65f.nq.gz
│   ├── 89ec9faee8c4481e31d3fe2977feea5f7cd910d1.nq.gz
│   ├── 8a4a5af598b7d4b24013fb0919e4c1dd35325a19.nq.gz
│   ├── 8a65f13347d6621289a166d08123cbc8e1ad0157.nq.gz
│   ├── 8db85875142a871a71d36f5f5db271e064b0684e.nq.gz
│   ├── 907594a40ba97476a14dbb841d332082d7b6cdb3.nq.gz
│   ├── 94f2febf02a1f8781e98b331bcc8f589c4eb6da3.nq.gz
│   ├── 966672dd27acc6fbf5c470d36ca8ace6990870d7.nq.gz
│   ├── 96e973d0ce223f6bed9be9e6a6a2f3c01622c611.nq.gz
│   ├── 970d53d5321ca3fb30579b69f1c1e3d7d70b1608.nq.gz
│   ├── 9a92dc4a440bdf6f259ec1083c89c817eb7b631b.nq.gz
│   ├── 9b6edca03d4d4b34f355fd53e49d4b4c699c972c.nq.gz
│   ├── 9ccfa53e597a29ee387f9d16f3af4f695ac0d33a.nq.gz
│   ├── 9f4200bad6940ac161797a9fad7715cfe8cbc3ee.nq.gz
│   ├── a0572d5311ae901023ebcbbd441d11c53537996d.nq.gz
│   ├── a140095e1b8de022f321a41c0125e0e5febc0749.nq.gz
│   ├── b363f55a0b071de6c5f377726be82dc2110e373c.nq.gz
│   ├── b42581dff8aabf4c2ef80ffda26296e1b368d693.nq.gz
│   ├── b43d7f01ac385cbaf4204b6a6a5df3e72070787d.nq.gz
│   ├── b476d76d9a7ff45de8d18ec22d33d6af2982f92e.nq.gz
│   ├── b4ec664881c23138c28b6cc1029a89b96f1465f2.nq.gz
│   ├── b6ee0c7e33378cbc928a2523693fb278a93df5ce.nq.gz
│   ├── bc28d44f55bdc4b872951a74780469a3999d9ab4.nq.gz
│   ├── c3ad08f14544d976a2520a74578ed41feb6fda71.nq.gz
│   ├── c44ff93cb2f572afc6e679308024b744b65c3b0a.nq.gz
│   ├── c6cfff210b7eed92edcf62beb1547d9cf460f252.nq.gz
│   ├── c99c5a67945b8a3a3544d481e979c791ab45fe23.nq.gz
│   ├── cb461a9810974e958c6c22e3eb432aad1290b825.nq.gz
│   ├── cc9d92066e1680576846e46ccdf645a2b1dd5718.nq.gz
│   ├── cf55c8b10eb543872550be863206fe2f760d0d8d.nq.gz
│   ├── cfc909184eb50b53abd809875e7f74722694fa7e.nq.gz
│   ├── d07802b01d34d64155cd894423856723cbc083f2.nq.gz
│   ├── dbd0beeb4da32d8c0175d412fa442eae8f837723.nq.gz
│   ├── ddcc189001c50c37c6a03810dc21d955df919f10.nq.gz
│   ├── e0f0a65c84097d580e7462ba27357f94d556ed1f.nq.gz
│   ├── e25fcc03c0303e54ce1e71af4e3fc1e53c711863.nq.gz
│   ├── e3327e696d5fbe71fafb1160bf6c9520b6dfe326.nq.gz
│   ├── e43b0596f1abf2e992cdcbfc5396be5543e1d543.nq.gz
│   ├── e673d4cc1b1dd7e7ecdbde91fd6ada386c3de03f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6d6d709852b137a862cfe2b3af42dc790fa705d.nq.gz
│   ├── e871360d1642bc3ac222718fa735b9daee6dd0fa.nq.gz
│   ├── ebd3a97480c720d418acb1285a7b75da19b62c8c.nq.gz
│   ├── ecca88f7dc93b78f2aa26f16cf29d17a8a83ae27.nq.gz
│   ├── ee303e5cf1310060da42f94322849c460f442d49.nq.gz
│   ├── f2fa28f4c271f92d501b0c7c39feaa337b6e11d1.nq.gz
│   ├── f7f32ad12bb044c3c2992089f52c9ccd0a3dfbbe.nq.gz
│   ├── fbb6bfdbf5a32b2d8eccfdd97450253363b113ff.nq.gz
│   └── fc02e475a5bc938f06b033e3ce0230284581543f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 98209758cc14e1a5f966fe1dfdc1064b94055d8c.nq.gz
├── filetree
│   └── 98209758cc14e1a5f966fe1dfdc1064b94055d8c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 98 files
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

[encode/httpcore](https://github.com/encode/httpcore)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
