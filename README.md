# Repolex Knowledge Graph of UKPLab/gumbel-softmax-layer-skipping-2024

RDF knowledge graph data for [UKPLab/gumbel-softmax-layer-skipping-2024](https://github.com/UKPLab/gumbel-softmax-layer-skipping-2024), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/gumbel-softmax-layer-skipping-2024
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3f5eb5ce48c730452ffd04a6cffba2bea1317c01
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3f5eb5ce48c730452ffd04a6cffba2bea1317c01
│           └── chunk-001.nq.gz
├── blob
│   ├── 0216e13b95d15f74ba02ccbd4da3450bc075b6ad.nq.gz
│   ├── 02600688c8a5ae8bb06300bec4dadcf2a8c45068.nq.gz
│   ├── 0a11d8c3db5b65ecdc7f6aa850280d60485b29b6.nq.gz
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 0e88b780b81493bb79a8ff32382234e9d7dc1ca2.nq.gz
│   ├── 11df7edf60d09f1016049026636fca176440043b.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 17fb3f39015643148c77b16837adef04ba28b766.nq.gz
│   ├── 22b0ca00173bd8b40c8982c615a3a04a697d6484.nq.gz
│   ├── 2d8270ca8345d22a70bb9f44fdd5b5a01d30caa1.nq.gz
│   ├── 38a44d42c954bdffb0e41bc03012195fcd1a193c.nq.gz
│   ├── 39a4cd5ebc3ffcabe6a8176393f1ab2c81ff22c0.nq.gz
│   ├── 3b867b4fe6d14737d8a604ffac1246fe34e572ac.nq.gz
│   ├── 3eaf93584b664bf197debfaf08bda1ebf4a8a123.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 530fdcf7d9ee0a4b397be00edbc3eadce937f388.nq.gz
│   ├── 6d688fc531db77e0e3fba3b27841e6bdd783f35a.nq.gz
│   ├── 6d6a7c7034c1951a92dbe0686ef469db0ee9cdaf.nq.gz
│   ├── 725f2b0d5f7a5ec9551108f7bcd7e5c166af7af1.nq.gz
│   ├── 73de09f2377aa76df9cd3b62e2cdc6cb307e5879.nq.gz
│   ├── 7604f45a683b270163ff679264a47bece332d1d2.nq.gz
│   ├── 818b7daced3dc807ae43ee9b74afceab7c083ab8.nq.gz
│   ├── 89d7e202aed9b4ae81346b09ad0b654626ddaeeb.nq.gz
│   ├── 89f79d04b69ed907c42ae436aa16e9cfa7cfd9bf.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 8c55ac66c8352ffb20418458cfc2de7cb944d7e7.nq.gz
│   ├── 8ee45c38dcd2c8d9c7d38968aa130714cd9346fc.nq.gz
│   ├── 90b4d4851ac8558c557c65b6a21d3bea7868d0db.nq.gz
│   ├── 94a0ec8b1b1e4226fa0f4bd9e853902fff7f6769.nq.gz
│   ├── 9a3de6b6b4d8cd7a985eedd156d083bba802bc51.nq.gz
│   ├── 9ccc7363dcc9155dec920e64a9820737d3fff0e3.nq.gz
│   ├── a3cccf4f5f43a9944025b4c915f2b09517912684.nq.gz
│   ├── a49a573971b044d07bef8f4f36ad509c594781fe.nq.gz
│   ├── a6a1e393b8b24b9583b87450fbe790c0d99a643b.nq.gz
│   ├── b23130a41ddee0ff4bddc20102e323acae62fbe7.nq.gz
│   ├── c7a6f0e937138db3799cb4f0c012c0828896b486.nq.gz
│   ├── c85cf49ce45851f69da2137990684cec39b24e6e.nq.gz
│   ├── c85ef567d96bae2ccaaa188dac9bbadc7203f668.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── da7981cac211efb880ebf36b5879a9202ac668a6.nq.gz
│   ├── dd6e4ac6adb5926b846c3087c9c9a3b93b873987.nq.gz
│   ├── e2cd8d9108cb3dc994b47150efae0ff76478aaec.nq.gz
│   ├── ecec710e8fe2c5fda90441dc3e864b89b41f3ee2.nq.gz
│   ├── ef2f11b8821bd42e82b5cb64455ee42753a55f78.nq.gz
│   ├── efbd28ae9bdf3857642ea7f1e0e6ddafebad9318.nq.gz
│   └── fee3ee797958a200addca90bf5789a0d948732a9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3f5eb5ce48c730452ffd04a6cffba2bea1317c01.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 53 files
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

[UKPLab/gumbel-softmax-layer-skipping-2024](https://github.com/UKPLab/gumbel-softmax-layer-skipping-2024)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
