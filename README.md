# Repolex Knowledge Graph of PrefectHQ/prometheus-prefect-exporter

RDF knowledge graph data for [PrefectHQ/prometheus-prefect-exporter](https://github.com/PrefectHQ/prometheus-prefect-exporter), parsed by [repolex](https://repolex.ai).

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
rlex download PrefectHQ/prometheus-prefect-exporter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1ce3beaa577b4a5edb998ab346f5f2c1268a9830
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1ce3beaa577b4a5edb998ab346f5f2c1268a9830
│           └── chunk-001.nq.gz
├── blob
│   ├── 0351128db2075f34ba0c6a488303b4958b33142e.nq.gz
│   ├── 0725357a80e62dfc5d9d200ca2ea5d0cb8454b0e.nq.gz
│   ├── 0ad3ef06b0b1b6df5ad286203980df49696d5063.nq.gz
│   ├── 0bc51309cf831602b0e926277d12287058aa7435.nq.gz
│   ├── 1336e50432a25a54a8995d800a960f3a787aa3ba.nq.gz
│   ├── 1f119e739a718ae520d04e1711a79d8589e92560.nq.gz
│   ├── 22650597162f0a08ea041cb8f0bde21dbe2fbeef.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 263fb6426ca46b1b8a61ce3f6c5e4f0047d77012.nq.gz
│   ├── 268ae5def7dbe048fd00f0d156eebdec4b31aae0.nq.gz
│   ├── 29d87f9abd186fdac727334e9d50c5225be8fc62.nq.gz
│   ├── 33e86d660f39cd92221b1bc7f15c90ae20e614c3.nq.gz
│   ├── 44c903f69a38c2fc423b537bc49aeeb113cfb0f9.nq.gz
│   ├── 45f68b738909247ca2526c67a490e7a0a17e2979.nq.gz
│   ├── 463db7d6d44fc4bb7bdec50bcd4f6f428ee7d216.nq.gz
│   ├── 46bb849a5338c62fc1fe48a49933fe2f2f75826e.nq.gz
│   ├── 4c977b175962bba3ca789001ba11aeb2fba92102.nq.gz
│   ├── 4e88c5f12286e12aaac824bc4c2890cd98d5ce50.nq.gz
│   ├── 539ba799408e3a54df511a417d62639787835e9f.nq.gz
│   ├── 551103c27929f00b9cff1695eec757bd2f2402ef.nq.gz
│   ├── 5745c3e23eecd0258959cbaaa414c506e2c9d961.nq.gz
│   ├── 5b5ea8843e6dc121537668e31cf1b5c39940580a.nq.gz
│   ├── 6247c55de067a6f13585ffb57373fb80d9db7637.nq.gz
│   ├── 699e189e39f6e95455bf43433e65c4e17654b18a.nq.gz
│   ├── 6d6c2395ace79254107d2fb8f26375257c867872.nq.gz
│   ├── 70958109605fea6d68363f4d43054459fe10fc45.nq.gz
│   ├── 728b537d94c9659b632f337897cd88c3a92ec621.nq.gz
│   ├── 84988d47fc39f2579df4559bf68a13699532d089.nq.gz
│   ├── 84d6d944cad7f98a42adc37ad5b8b174a4a186c8.nq.gz
│   ├── 8703709e03d0f19f505bbd09b4c3e789da6c1d52.nq.gz
│   ├── 88d19e86997d3663de809419b417f0d828661804.nq.gz
│   ├── 8d250bb231f14241a68e566a3c63c213f68075a3.nq.gz
│   ├── 8ef74030484e9cf8df69ff4e1f19734a734369a0.nq.gz
│   ├── 91ffbd22cbfe2910e89f6e156171d489bea15cfa.nq.gz
│   ├── a7d103d9572fbcc77041ef439d58d1a4a9b0ab75.nq.gz
│   ├── bedc2c573ae251235165b256ec38f5e5e6050fff.nq.gz
│   ├── c36e277722ae7569feec1c5e62e757858f0b1e8d.nq.gz
│   ├── da54a38cb32c7206f152d283560d692f63f9f09c.nq.gz
│   ├── dc2aca62a00a9bfcf9e33f84035487379f69e8d7.nq.gz
│   ├── e3a27c59847b2703d9900702971ac26119bec866.nq.gz
│   ├── e5a20c6f8c29d23b322e261788de5fba9fb40a58.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f325a054b95e51eb8b1e1a4ccafbfe0b628c3adf.nq.gz
│   ├── f3b36289c2356943dc89e35f6e27e09279c680f5.nq.gz
│   ├── f51305e825cddfd38e3217b26f6a307d3a50de47.nq.gz
│   ├── f94ad7dba50dbc52b3f6904a96fca2bf72015f9a.nq.gz
│   └── ffc888994e60bdaed306eb15f71423d615316ef7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1ce3beaa577b4a5edb998ab346f5f2c1268a9830.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[PrefectHQ/prometheus-prefect-exporter](https://github.com/PrefectHQ/prometheus-prefect-exporter)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
