# Repolex Knowledge Graph of modelcontextprotocol/swift-sdk

RDF knowledge graph data for [modelcontextprotocol/swift-sdk](https://github.com/modelcontextprotocol/swift-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/swift-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a0ae212ebf6eab5f754c3129608bc5557637e605
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a0ae212ebf6eab5f754c3129608bc5557637e605
│           └── chunk-001.nq.gz
├── blob
│   ├── 0071c04274031b13961e8d1e24f40633b657dcf0.nq.gz
│   ├── 0269251576afe7615142f740ee808d38af2b8ea4.nq.gz
│   ├── 0384307bd193b4e4486ce35a36490b7d41348fd6.nq.gz
│   ├── 060b51f8eb437b3a936d94bce00f01a4f17810c5.nq.gz
│   ├── 060cd1336cd07323dcaab26dc81f726ee37e2d03.nq.gz
│   ├── 07a5e3c945ed0f2ea3c577cf2e8d10209b11bd9e.nq.gz
│   ├── 07f94e7b550ebe8751982a3ef13f8c338dab75d5.nq.gz
│   ├── 08ea967c2e50483f35398d916db244d2e78402f9.nq.gz
│   ├── 0abf28e60f15930242c6526caae298c799990185.nq.gz
│   ├── 0bed5c49e691979778d245fd784cadd33ac8154f.nq.gz
│   ├── 0c278f1caef0f85f8425a88b429f6def4b1ace8d.nq.gz
│   ├── 0ecafbcf45f9148fdb36faebf9e11ec41c82b6bf.nq.gz
│   ├── 1706440e5fd34fa211b76e1b6ae639bae0bcc6ee.nq.gz
│   ├── 1bf1670a4136bafd7accac0224f4b80258fe5bf3.nq.gz
│   ├── 1c7728c9c8480bb25cb7376976958c41fa6589e7.nq.gz
│   ├── 2071f90476453b1516e572a436f128c7b2171bbe.nq.gz
│   ├── 215fe3a47928553c808648219833c28274d1115f.nq.gz
│   ├── 271b615099d09ee10294495fb123fc05d6eeee59.nq.gz
│   ├── 273715abe61180310dd181de71afe526d85d9f6b.nq.gz
│   ├── 28043b9f82a8799893372f1cf48d61e5b0808e4d.nq.gz
│   ├── 2d0abd0482cd8260ded742a64013817958ecedd4.nq.gz
│   ├── 2f8249cee2bb6c71120b714463cfe80b59cd4a74.nq.gz
│   ├── 332a898e7cc954c635eef9ca624437ee75f1d2d0.nq.gz
│   ├── 38b19e45e6c42915ceb53ef758c33902bae5b992.nq.gz
│   ├── 3aad91f5db084c36445c72e71422de04b27181f6.nq.gz
│   ├── 3c6160022565db4ef9e40b1d44db72860329bda9.nq.gz
│   ├── 3eea124045b4f436d02bf75cbef5c89c811da420.nq.gz
│   ├── 451545427f5fa3d8eb4e93f7260f10259e29aeeb.nq.gz
│   ├── 45522fac20da1064f3ab2e3381ae7b280fd46d5d.nq.gz
│   ├── 478ba60192b66921462773bd21dcc60baffd020d.nq.gz
│   ├── 47e89b427c99c42e44dc72067737bbfff6261f1f.nq.gz
│   ├── 4a93985763241755401a10678395303de4e720ba.nq.gz
│   ├── 4bdd187342a47c54f17863c39c77ba62a754e8a5.nq.gz
│   ├── 4c08d66981d73802a37eba9bc50fc1e556af9bd0.nq.gz
│   ├── 4e4350fd8852b1c2f6ce8a397ac22221b4ac9c02.nq.gz
│   ├── 50292420096eb98f07f3945dc30325fe8b17a2af.nq.gz
│   ├── 51c7aaed9b2f457f1eeae60ebab2c980353b8e68.nq.gz
│   ├── 51f3c6fa7f514690544db7f9149cfb04f49928e9.nq.gz
│   ├── 5694f7ef0dc10b9e12a3653ffe79f6936c75e3f0.nq.gz
│   ├── 5979e9ada57c1b4886da1f897937d6cca5122d95.nq.gz
│   ├── 5b8fbbdc3efe7be64a415db1429e6eac6b4d8109.nq.gz
│   ├── 5fdf2e4919fd80194063730d66f57533a346c5d5.nq.gz
│   ├── 60b4baefcea2e2e23f16fa6249432a26d36f60a6.nq.gz
│   ├── 6267421ce17edc14062a08ab68f27e2717aba18f.nq.gz
│   ├── 62d745713b45c6b90af390f51f7cdec27bac6b6c.nq.gz
│   ├── 6812461c52fe49c3f219fb0b1d3fa66a56419ca2.nq.gz
│   ├── 6a7ccead748c94382e3d5ecfdbdbaf7b3f84a91b.nq.gz
│   ├── 6d8b1f0bf746546d668f31aa8cd064563a34f2bc.nq.gz
│   ├── 6e1fab06bb55a250ad539c10c7261ec0967f6125.nq.gz
│   ├── 6edba56f4481525c9e5eae8f7ce388fd6711c925.nq.gz
│   ├── 7127a6b96eac080b9947b2cff0a25db2be6a6bcc.nq.gz
│   ├── 732835b876baa475a7b9f225712c3ff2231ae6ba.nq.gz
│   ├── 73cde0f1b662d52c0d139af22ffcfd9dfe7be2f6.nq.gz
│   ├── 745b4a304483c66a4d61471d7682d0e6825bd260.nq.gz
│   ├── 7bdec5dd14e0e1a378e2f340295f6ff7e5a0ec02.nq.gz
│   ├── 7c4d00f3c6a5edcecd08e72261907e4d3f1ac75e.nq.gz
│   ├── 85c610e4bc836842bffe8dfaa0b28a972bd248cb.nq.gz
│   ├── 86747e29086ac7867e66be8ecdc8d9664e2b4995.nq.gz
│   ├── 86a6e5ea08ed1a3b23746eb77fe11d85bd4b70b2.nq.gz
│   ├── 8795ed7ac951f950e8f4c7b15031559eb11b91cd.nq.gz
│   ├── 8a2882a45f33ccafecbf567e7ee88242e429eb76.nq.gz
│   ├── 8caf1c4d1dafc97ee860285ba7fe09df05093a43.nq.gz
│   ├── 8e1c89b4861362d2ffc5572b3781edd2b70d0657.nq.gz
│   ├── 9234dfc4424370261eef02a193d556bf26c077f6.nq.gz
│   ├── 958719908467e77e034b1b5666efc00c0ccdb810.nq.gz
│   ├── 960259354807326362631c9162db237e29ba42ba.nq.gz
│   ├── 9c02c90cbfb6dec32dd5560cd9981944c60e344a.nq.gz
│   ├── 9d4412ef4c38591c95f3856f2bad30c44ac2161d.nq.gz
│   ├── a1c015f62f85d36a8325b9f440ba22268f0022a7.nq.gz
│   ├── a7b616671bbfe1094624989214df7ee54cbb16cb.nq.gz
│   ├── a8635cef981a25c995e8a971daeda03958061229.nq.gz
│   ├── a89cd0f931623d3db71ce859b092358e5780e679.nq.gz
│   ├── abe9576ce48c91e56462b8c27506a184f4690e53.nq.gz
│   ├── acfdcad8ba8259fbca240968d094ddcfc65e92b0.nq.gz
│   ├── b28026f9d318ecc068f431b85289e6d7cc4a0f7c.nq.gz
│   ├── b2e5be3bc02ce5940be6c142eff663c713ee8f6c.nq.gz
│   ├── b6e0a83b64d513e621094ee16d66a6ba6bba917e.nq.gz
│   ├── b7196f07da54c8d119adec0990576a797d6bfbfd.nq.gz
│   ├── b91825df068ddb6437c9a9c0b225aefaa6ceea50.nq.gz
│   ├── b962bb6fad443519414d056d6d1bb52391a8180c.nq.gz
│   ├── bd56191c4b7f2b5873ac4d0a7e9172a66b282b70.nq.gz
│   ├── bd8c38f7eeddae621fa0d64b83f1e1d3375e3845.nq.gz
│   ├── be9704c63e132edd3f8f2180db4d63b42e9169cc.nq.gz
│   ├── bf08519f098375dcdd989d26847f5b9ec712992b.nq.gz
│   ├── c7a4d4859fab9fc58762164d56cd37b707cd0b8f.nq.gz
│   ├── cb1b8be49ea386bf77b2a14fc6deabdd76d7fb97.nq.gz
│   ├── cb918521e993c03c79be96b08d73db62bb47f519.nq.gz
│   ├── cd8e73ac3797dbdd06420ee7b484631c4cafa827.nq.gz
│   ├── d21ebacff66748f4732be537db8d895ef199d628.nq.gz
│   ├── d8228e770274e3d57734f51fb3f48e55e72c0903.nq.gz
│   ├── d91fb499366ab9713a7be19cdd4100b894b7e737.nq.gz
│   ├── ddc180cf373c1c9c394792cb056ac884f9a08714.nq.gz
│   ├── df2ab66e27e6018c3c3570a74361cdf4ab58500a.nq.gz
│   ├── e395fbe09d4c009d82fed1e870f64cf21bc54788.nq.gz
│   ├── e526ad4e16cdf41de4196d8b00dfc13f41989940.nq.gz
│   ├── e53bb7297fe49a54bbf1bd0c4170f3898093d990.nq.gz
│   ├── f8465813c39906c78ac945d40d404da95ea2e36f.nq.gz
│   ├── fb512a032e9ffddbdd36da7e23cf212e5886fa02.nq.gz
│   ├── fdbb79a7acfb13e8a4b13b6a50a041697061ca6c.nq.gz
│   └── fddc3420ad3ed438ada7263282d73c06643f45d2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a0ae212ebf6eab5f754c3129608bc5557637e605.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 108 files
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

[modelcontextprotocol/swift-sdk](https://github.com/modelcontextprotocol/swift-sdk)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
