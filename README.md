# Repolex Knowledge Graph of ray-project/serve_workloads

RDF knowledge graph data for [ray-project/serve_workloads](https://github.com/ray-project/serve_workloads), parsed by [repolex](https://repolex.ai).

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
rlex download ray-project/serve_workloads
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9594a6db977c9009e6adf6f06ae284cfa03e04ea
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9594a6db977c9009e6adf6f06ae284cfa03e04ea
│           └── chunk-001.nq.gz
├── blob
│   ├── 0328808e0faf559a0dcd56f058cc3362c9e6b2d3.nq.gz
│   ├── 05ff671defd42245299248ac247b6d5e4bcdd2dc.nq.gz
│   ├── 0878500fe6d5f8aabd07bb17026b1c80ab1bb0db.nq.gz
│   ├── 0b427ae13d124b82a2d9b46bccd9d0e75360969c.nq.gz
│   ├── 1313a8b22a2da2b507140ad6c7d179e06aeff94a.nq.gz
│   ├── 133293df739c63614fb85feec8a1e5318688a3d9.nq.gz
│   ├── 1493e615b6fb2aead0f89a81e2fcc00620dddd5b.nq.gz
│   ├── 14b2d032140582cfe43be76f93eb3a4769e6de7f.nq.gz
│   ├── 17cd2639a4dc21f3094b970665132317c260c504.nq.gz
│   ├── 18d3d74c6648f6fe55805923beba997c00a310d4.nq.gz
│   ├── 1908e4666b4300c147c66d91f2b1f186652ef809.nq.gz
│   ├── 21aeeb086674430b8a21b445edf464e188af70f7.nq.gz
│   ├── 2583b43b36a03506b147f3e18884d834671f3a68.nq.gz
│   ├── 35697c9fe3eaef38c500e5fb0f8418365b59a2df.nq.gz
│   ├── 3696ba4426d9a984ca0ea2e3b0db96ebc26cfcae.nq.gz
│   ├── 3f2538a1842ab1300749702edd82fcc04f6b075f.nq.gz
│   ├── 400a32e6a130f55985adbdf507cd37c481d69aa6.nq.gz
│   ├── 40bef1b705607bbbecf5e9c4c8d87e385fb51e62.nq.gz
│   ├── 45dbfbfe5d6e71dc739e1b338ce4040a0adafc92.nq.gz
│   ├── 4c80326e88bf1822d322c066d04244384dac3fbb.nq.gz
│   ├── 51b3d0628efc68437c28991cdb2f06012939f68a.nq.gz
│   ├── 531595a446945adca84ac0a29f3082bda2fbce70.nq.gz
│   ├── 54aef95dc0a5d8fca7513bf58e26541381c4e8d4.nq.gz
│   ├── 5a75f7355346ef1e46b97d49d9f6efc62c548f47.nq.gz
│   ├── 5ad1ed65d7962131e98d89391aa377ede2e115fa.nq.gz
│   ├── 5b78c965a03ef01f3bed9f89e74814da6dfb26ad.nq.gz
│   ├── 5c57d628cc1dafa48bd0323b8113e5864e493af0.nq.gz
│   ├── 630fb82914aff1d1c8fd6c1bde87af43aae058dd.nq.gz
│   ├── 6395390704432944fd73c24f5ceb95949fc15bb1.nq.gz
│   ├── 686f4b046a542a5edc94e1624881a24cf6dd9c93.nq.gz
│   ├── 7185bd731e995e87d1e8c193f92cc61103da55f2.nq.gz
│   ├── 7235cf6f6824308d6697efa79529fbf030e6a319.nq.gz
│   ├── 72eee99da44f8303d970689c97758620c2818b19.nq.gz
│   ├── 751b33b51514c03e6bc605239234c2c42341df98.nq.gz
│   ├── 755a396d62932dc1810bc52ae59918e1e2b3c730.nq.gz
│   ├── 76db5c6306ca494994e35404afaeac8882774e7f.nq.gz
│   ├── 77026fd0f21077b03b427b1f7685a3e377509ce0.nq.gz
│   ├── 7a3f22a402a645f24d3c8baf86838f6da23e8951.nq.gz
│   ├── 7c2382ecd1057eb344ea65be2171ccb73ad31538.nq.gz
│   ├── 810be96bf8545ff835a41099682f102a02a90877.nq.gz
│   ├── 82c35757ab7c32c804d8a9d0794db5c0b426a359.nq.gz
│   ├── 8c6c8a95aa540f0c44ee4578b19f49d4a80fa9a7.nq.gz
│   ├── 8e6c193fb0cdb989a80d10213121b121fa1d5f1e.nq.gz
│   ├── 8feb2424c6ae7e2982db9ce15cdd264686ee74fd.nq.gz
│   ├── 9a80525a9627126e47358656ff4af3294747de18.nq.gz
│   ├── 9ba3985f9df938f6e0a980de7eb11a6b7e770ece.nq.gz
│   ├── a119e3f4db7f3521c10905a959769086e0b84bfc.nq.gz
│   ├── a65eeb449bfd7cdf0fe535ab9db1305e021955f5.nq.gz
│   ├── b1b2852cdc5fa1ebd1948a72e3f7d004215db9fe.nq.gz
│   ├── b2516d87a9592ff1b002ed3da307094b3f7a61fc.nq.gz
│   ├── b7cae19fca895dabd310e11228bdbf1489ff36af.nq.gz
│   ├── c0e4adf60d19671b8766914cbad7b07865bf168e.nq.gz
│   ├── c273deb215eb449e32fbf14b6e7220cb4310dbf0.nq.gz
│   ├── c843b8035990f0706edd44952e22dd20465b107b.nq.gz
│   ├── c96b6798cfa37ae9d3af7a4948211f3417c930d5.nq.gz
│   ├── d3855ce6f3b91b4ad94b0bb18bf02fb75f1c1bbf.nq.gz
│   ├── d5c53d2549bc11937991548d8e86851454583b96.nq.gz
│   ├── d8f257d5c3d886ef5b0ab8d4fd7bb9b6d9b206b3.nq.gz
│   ├── dbd67abed72a24842e320987ae94f813556b065c.nq.gz
│   ├── dc02a070798095a329398dd846eb1d38016eb688.nq.gz
│   ├── dc2642addee50d83e6b81dc33c06edff12cbcb46.nq.gz
│   ├── dc5dadf64a9e9471daff7503d73f378bbcd02f07.nq.gz
│   ├── dd6fa0b9683aee8aec169fdec64f1aadd27b87ef.nq.gz
│   ├── e139c2070c6ee005bd9756976f8f616fa9921930.nq.gz
│   ├── e4f5bf2ae68d157bae84a2fcc959293d3a79c0dd.nq.gz
│   ├── e63bbe7385aa9f9bbc8ee3d78575c66c63d92eb7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9e8f0daaad80250b14aa793024ec301adf48a45.nq.gz
│   ├── eaf54e947e77be8d33af874770f55e0f13f4ecfb.nq.gz
│   ├── eed40bffdde6809174fa98bca04cc8abe484796a.nq.gz
│   ├── f0c83ea50c696d8593dd359b02a6c9a8ea0d4f91.nq.gz
│   ├── f33b7b44a5f90ba2b3f053b8c799cbe68da2d5cd.nq.gz
│   ├── f3592d3abf7c7d58e3ca8d9c48c5af65ddf227fb.nq.gz
│   └── f548f51d33baee52812736bc793ccca1fe5a6304.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9594a6db977c9009e6adf6f06ae284cfa03e04ea.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 81 files
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

[ray-project/serve_workloads](https://github.com/ray-project/serve_workloads)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
