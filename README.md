# Repolex Knowledge Graph of databrickslabs/pytester

RDF knowledge graph data for [databrickslabs/pytester](https://github.com/databrickslabs/pytester), parsed by [repolex](https://repolex.ai).

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
rlex download databrickslabs/pytester
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cbcb0635de86060731fcde351b1de6298eb5fbe7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cbcb0635de86060731fcde351b1de6298eb5fbe7
│           └── chunk-001.nq.gz
├── blob
│   ├── 0c5cade7c0f2f8730f75e2ecc4770150c0f60b70.nq.gz
│   ├── 15fa27eb442237750b24112ec9e723fc7357e209.nq.gz
│   ├── 1918536fa1b1a824cc093a7df07e422bcc216099.nq.gz
│   ├── 1cff8a657e6791d8014956f08b996920bbca4020.nq.gz
│   ├── 22ed2eef37a37192835713ec90076853fce552bb.nq.gz
│   ├── 2de8a5a8edd8d07d837e5caaf7067de28bab5a4d.nq.gz
│   ├── 3450cedf036a6ed684e0b05b5c3ec150c3ed7ef0.nq.gz
│   ├── 363150baae62c0de41a6f4a0ba4f3f7f43cb2329.nq.gz
│   ├── 36f674f5001e26c83b644d3df6b7ee59633162f3.nq.gz
│   ├── 3d34929f82c8c046186b9547089fbda67e30f606.nq.gz
│   ├── 3ff30b4cfe138a283d71880fa935eb4dd7121db9.nq.gz
│   ├── 4204b2abdf6bd10ee90a53d13c84e2715d910637.nq.gz
│   ├── 42a0afa7bc1e8e674066b502495441de7001851b.nq.gz
│   ├── 44164e6e28490a33101a495c9b45a998e79b40fb.nq.gz
│   ├── 48139db9ac6f7684c44c36a40232478442d2b6a3.nq.gz
│   ├── 4d43478478f38be2b9c0b2edb356a91f2ac50f06.nq.gz
│   ├── 4f5e40256a2bc846c0a77bd75d90ac2ee5db34b6.nq.gz
│   ├── 5548861916c5e3705ef4b0a5afbb18ca7abe125a.nq.gz
│   ├── 580a57c63f1bf58775f577eb5ce4700e2cd31353.nq.gz
│   ├── 6a5ab856a4217409898f5cfedf119990069a5dc8.nq.gz
│   ├── 6ac5f21c515d447ad3916bdd3bd3d977e7ec0c05.nq.gz
│   ├── 6ec2a01aebe9e03428c0e7e244095e23db6cb7f4.nq.gz
│   ├── 71d057f7d6e06a384f41e1121fa67a7ad6181536.nq.gz
│   ├── 71d865a957e0425d71f795a25a6019e8694a04ed.nq.gz
│   ├── 7497e3dd8bcf599898b9f983f5cd2824d1d5a8bc.nq.gz
│   ├── 7b357196bd88a259bff4d6e49b83131a370424f4.nq.gz
│   ├── 7baaa98c7a59dc647f0bc20e552cef62d5822544.nq.gz
│   ├── 7fcf89cedc7980c07ac2a5c33b2f0bb365f1738d.nq.gz
│   ├── 802efcc1e4d4ee907b1d77361a0b7c674f101f7b.nq.gz
│   ├── 80bce21577214ab6c885877759ae2c68e43e3de9.nq.gz
│   ├── 8505a1b75bb6da8ca8f5c1fb1d49c1ec48aa413f.nq.gz
│   ├── 8577c2a854a23e11c6c8f2f93a195ab6312f9704.nq.gz
│   ├── 8583784a8c486098e673fac9e16bf758f689269f.nq.gz
│   ├── 86e82fdd88a6f6a450139ec6a1cc358726c9e54d.nq.gz
│   ├── 8b3749278de2a8176efd506a25f16c43c915f8a3.nq.gz
│   ├── 8d673e7ed143247776acba2a2a8bfdbf18f460d3.nq.gz
│   ├── 90c4472751df3a9f2d57fb9b215cbb8326a6db59.nq.gz
│   ├── 92b617ebd22ea139c2ec4029f9191c056464d71e.nq.gz
│   ├── 93d9a5a013c94bc52c50de13a97ecccd3bf941e2.nq.gz
│   ├── 9479ef4d7d00fec7fb5c13d3da10598b630a988b.nq.gz
│   ├── a1232acf02e032253ae2ce144eafa6304f3fb2e6.nq.gz
│   ├── a486009bf0720ac16fcb9da9cbd1fe08275ecd6d.nq.gz
│   ├── a5fd6c4b8c1069acdca38ef44c1461579debb834.nq.gz
│   ├── a643ecdecfd7a2397a9fee6753998c9ae3366b5a.nq.gz
│   ├── a8750966bcde8c2b33693417c2440ffd06869092.nq.gz
│   ├── a9602dec40ca13a0186f82e69d3a92d131fbaefd.nq.gz
│   ├── aadd0b47c0ee4a868bc2e9090bfa1921783cd307.nq.gz
│   ├── b3203b62de54ed87e4ce29eac3eb18c68970cdf5.nq.gz
│   ├── b990372fc3ee1a13bb527317a3686e6ab671212b.nq.gz
│   ├── bcf01e9409f59ecad393b801d47d714e82f75030.nq.gz
│   ├── c1b729b07cae66273c321eac124702fe02ce5796.nq.gz
│   ├── c3d927bb34ad6cbb7d37d7597f1f082603465e36.nq.gz
│   ├── c6a91b9fa456403b816693373689f40432a38d71.nq.gz
│   ├── c70ac2bb506019d2e6eb40cdee8ec53f6b1c4285.nq.gz
│   ├── c8cfe3959183f8e9a50f83f54cd723f2dc9c252d.nq.gz
│   ├── cca62bc1a777097c31baa85364cdf137de0d6a57.nq.gz
│   ├── cf497b83b4614c50f9d1565677998ef9e6dc0030.nq.gz
│   ├── cfefc3196883dca23ca3ca29a3ba60f2ecc12f78.nq.gz
│   ├── d64892f056236db82f6f6b73adeb445186336517.nq.gz
│   ├── d7ca52af03a4fbca6fae1015335e87bfcbabf2fd.nq.gz
│   ├── e04cd772b6e67fed0400675be232b01cb6f6190b.nq.gz
│   ├── e50827b0234f16a15daaf28b6013eb98a3a2ec6a.nq.gz
│   ├── e5187e2006b28c806bca54abb26be0ce6d2c2a7b.nq.gz
│   ├── e5cd39aac8609ad91ca88516f71ba4d2e9267c4d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a0d88371bd7c910fa9c72da914c08b34a782f3.nq.gz
│   ├── ed7d5fa3209b0da636bec8d0f6fbfa4cb7125677.nq.gz
│   ├── ed9d4d87b643f72ff4a7d8458a1d89f2693423b2.nq.gz
│   ├── f05642e93624980cdd0a719df5bc99032d8798d8.nq.gz
│   ├── f102a9cadfa89ce554b3b26d2b90bfba2e05273c.nq.gz
│   ├── f5ad303c1c55b90d30eb7039b97e02f8d9278625.nq.gz
│   └── f8e662ae40c2ce77ff2c5376e420459c65df6373.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cbcb0635de86060731fcde351b1de6298eb5fbe7.nq.gz
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

[databrickslabs/pytester](https://github.com/databrickslabs/pytester)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
