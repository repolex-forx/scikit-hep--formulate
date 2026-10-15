# Repolex Knowledge Graph of scikit-hep/formulate

RDF knowledge graph data for [scikit-hep/formulate](https://github.com/scikit-hep/formulate), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-hep/formulate
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 70e72bc04ab1b8c8fe7554e104008277f9001c2b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 70e72bc04ab1b8c8fe7554e104008277f9001c2b
│           └── chunk-001.nq.gz
├── blob
│   ├── 00bd193b259a00680d56855cef6617d8030f9b1e.nq.gz
│   ├── 0705166d84053d680964385fdb42431ab2c5932a.nq.gz
│   ├── 083a9a2ea486f8fb0a328ce7ffb41cce176ce449.nq.gz
│   ├── 1245d9c97d115a07f57177cc233f145b526b79a8.nq.gz
│   ├── 14c562876cf76162ec0735b398d43d9a79aefcda.nq.gz
│   ├── 1e27a123032c4ffb247f630ab22f4cbce4d93c68.nq.gz
│   ├── 1f533918f84a780c01137b03f8c8403051cea2f8.nq.gz
│   ├── 2379c8a49cd180666edc43c55a6418da9396dec1.nq.gz
│   ├── 28edb70c3b1fc4b7af98e9fc1fa86cb68e99593e.nq.gz
│   ├── 2aa95b6b401ec611d26de3b0f1650ba38982a0a4.nq.gz
│   ├── 2cee885869624c5a459c565fcf0108e811d61019.nq.gz
│   ├── 32c86c15820c52bd3545a5eae2ad9e80f5af8e83.nq.gz
│   ├── 34514231636d9a1e8bc8fcbfc42f7ddc825904b3.nq.gz
│   ├── 34e2c8dd3d82ebdd911ef3b9fb2e6602b95768b3.nq.gz
│   ├── 379a2131d34f15ecb28bf3f89275ef9422d3bf1c.nq.gz
│   ├── 37c383827181f5d270bb2e4188999d629f28299e.nq.gz
│   ├── 38d6a0d31cd4b649e02ed8dea8873e63b99580e0.nq.gz
│   ├── 3a9825a4babf64f4a3c956403d6f53b4aa3ca52b.nq.gz
│   ├── 3caaf9e7b379c3874b8c85d9feae7a27b39be17c.nq.gz
│   ├── 411d3b7db4a4bd0a0453f8d9925ecf9fea51a670.nq.gz
│   ├── 4510371251eb07ce3105cc031e7130e87960d982.nq.gz
│   ├── 4b0531a6a2b318bc8a4fdbced835392c1748c0fd.nq.gz
│   ├── 53cf18bec092b9933ba3d3424ecad6b34aec04e4.nq.gz
│   ├── 5625a735d510b0d59264a3777db06ecf975a6d7b.nq.gz
│   ├── 5cd92a6c0df75a0bab2eb1405a0116fab70193e9.nq.gz
│   ├── 5e91a0751633ca1933f25bf8dc33cf135608f6de.nq.gz
│   ├── 5f802da59273dc807fe27dd2036576d4991257f6.nq.gz
│   ├── 6007d28ff5ddb86247919fb39a87b1a0a291ffab.nq.gz
│   ├── 605095a737f1038184704ac5bae49edc827af564.nq.gz
│   ├── 6477802218cc36b557f8861cacf6d4211da08153.nq.gz
│   ├── 65572923db58bc97a67601ce24fd63021b55ea54.nq.gz
│   ├── 6cec3b4dba22e702cc3e22cd7a4d126204f9d4a1.nq.gz
│   ├── 6e5a23e008460573d98af616fa27c0a7dc644231.nq.gz
│   ├── 6eabf10ae5272fb77affa811627d8e853d455d13.nq.gz
│   ├── 6ec8ef5462e18dd1f8b46d56fada102f9d093879.nq.gz
│   ├── 72d7f1b10a6bdbefd622d7d1cb7b7bb6b5c5b2be.nq.gz
│   ├── 7a966d03ad4cdda505c78fe4a2da609a0998e133.nq.gz
│   ├── 834cc51357f77c5711e31c7b12ad6371011677ab.nq.gz
│   ├── 8bc48bc8e33aa28b64ae81c6f67fb1111c8aa91c.nq.gz
│   ├── 905e52b0fa2c99061d4b703bb7e28df7217d7a10.nq.gz
│   ├── 91ba5293b54a96fdfd692bb1a36aef76efd4e634.nq.gz
│   ├── 954237b9b9f2b248bb1397a15c055c0af1cad03e.nq.gz
│   ├── a211c14c51f90a2c3f79e51a12fb3ab97eb1fcd9.nq.gz
│   ├── a7b6660be752df535b672bab21072b2de3d5b6f6.nq.gz
│   ├── ae0a24a5dc7432b68f52894f073677ae8b5fcf75.nq.gz
│   ├── b10c0a068a134b97eb28422fe29cbbe230d3032e.nq.gz
│   ├── b8dacdb963c7b140a6cf203c6e0763a2f6afbc1d.nq.gz
│   ├── b8f993dac6576294a7a35bb0251939dbb54da18b.nq.gz
│   ├── c132dab853c8bd293dd75793f659d8f1b21f4705.nq.gz
│   ├── c30a10762de24289ddfc2eeb1738a4f1285ded19.nq.gz
│   ├── cf6915e786de128d2b69d1c668601604f1decae0.nq.gz
│   ├── d083aded88f1333cd9b45fc78ca57dcfc17e6e36.nq.gz
│   ├── d4102790e404c857dc6f5c5dc4902de851bf39da.nq.gz
│   ├── daffd4731f7d46343eebfb999b791861fa3a3d0c.nq.gz
│   ├── dc0bc9240d604bddbe773bdf93e7a3bcb5dd10e8.nq.gz
│   ├── dc5dc366d10d33071147148f7a7f277059620c99.nq.gz
│   ├── e16d2b3d61a754dce0e987eba39da9ea7d81abbd.nq.gz
│   ├── e3e06c5a8f9d71c8ac63bec91ff80aa75bb235c1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea58ef7f460fdabf93e651128b16c0cbddb0568b.nq.gz
│   ├── ead876d7e07b83c4955e88fdcb1d78bff251d264.nq.gz
│   └── f0d17e7cd749be3eecaf47eb5916d1098d2274d1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 70e72bc04ab1b8c8fe7554e104008277f9001c2b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 70 files
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

[scikit-hep/formulate](https://github.com/scikit-hep/formulate)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
