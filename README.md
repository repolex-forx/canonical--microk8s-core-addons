# Repolex Knowledge Graph of canonical/microk8s-core-addons

RDF knowledge graph data for [canonical/microk8s-core-addons](https://github.com/canonical/microk8s-core-addons), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/microk8s-core-addons
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0f192230dc3df263eb95b6be4c3f00a6ea037879
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0f192230dc3df263eb95b6be4c3f00a6ea037879
│           └── chunk-001.nq.gz
├── blob
│   ├── 02d98cb445c3b18bb40285a92e9922d4875006d0.nq.gz
│   ├── 039bf8ae7b3de05bfdcd5d43b4e53c94a97b40bd.nq.gz
│   ├── 0526e74f7665028e03a82f9acbad309eff7a305f.nq.gz
│   ├── 09d25e4a0c176e653fa8a16c6666956ec3a3d6d0.nq.gz
│   ├── 117406ea269851da42a05cb80c4ec97f16711876.nq.gz
│   ├── 13f38d2680ee51c8c76322e28dd22886ecc46888.nq.gz
│   ├── 17775b23e01ca0699ef3826a6d119c7c9e3a1a34.nq.gz
│   ├── 1980db647a9f4dbc856b99be53ed0d52a86ceb35.nq.gz
│   ├── 1b420840d5da362df4864ee7e35233db6959b5a8.nq.gz
│   ├── 1d8b99918bd33d9b336192e4ce0cc7b1c5effaba.nq.gz
│   ├── 218114da3eee15b09e12001281af46ad4881e773.nq.gz
│   ├── 23b620ee3f7b10bad5aa28f79fdd6f05e010283f.nq.gz
│   ├── 25e3a86d3fef57a38798216207d883e6d13a97c9.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2e85d04e5e1567b6c25584656848dcf78109dece.nq.gz
│   ├── 324848554f3de2b7dc46f9f8ff59e26c72ef80a4.nq.gz
│   ├── 386ad824b87c5bb4b5b8e48e1e8f34b901580403.nq.gz
│   ├── 38c084f2750a4a0a3b8cb11dfa56f36f4f0a7e97.nq.gz
│   ├── 38edc392aa4cdefd5a91900a164bf86e8ed72a40.nq.gz
│   ├── 3ab3eb4b0d53b053b870d579df7962a44fa9d74c.nq.gz
│   ├── 43d309d7b53e2767299a68670d8a3b9d1180d07f.nq.gz
│   ├── 49c4e00160b0ae01334c2457d392e09d94020349.nq.gz
│   ├── 4a87695d9cf3c19f9640321a1856776a448113a4.nq.gz
│   ├── 4c4052cc969c361c0fc4063b7e3d5d53eb4f3fc9.nq.gz
│   ├── 4cc9a759e01adef9ff5551705c42e85cc67d80a0.nq.gz
│   ├── 4e5b9ce07ee49870c7122a92f336aff51773497c.nq.gz
│   ├── 4f667fbb17d695dccc18816cd3893f03d552b657.nq.gz
│   ├── 4fc74395e97003079db54b9b185d476847ed66a4.nq.gz
│   ├── 528106aa5d0caca7b4843dbdbe3e61bad6ad8b83.nq.gz
│   ├── 54161b4132cd385cc838568a13d9413a10c49e7d.nq.gz
│   ├── 5452d2a90a7a12a447ca8bf96c0b1a684bd4e4ea.nq.gz
│   ├── 563af7fb5415fa7ab5a6d73d51ac07f33750d9e9.nq.gz
│   ├── 565120839a4ec61ad18157b57e7dfc68a8a4e5a7.nq.gz
│   ├── 58acba09b6c5ef39185a51fc4baf68d35b8b12d2.nq.gz
│   ├── 5a1ca577bbcc0a695b36465b53bc872cb51af2ce.nq.gz
│   ├── 5a2f68b466d41e314334714276c839337ced4d95.nq.gz
│   ├── 5acaa0a16d128a4f237138f01d7ef769dc3305b1.nq.gz
│   ├── 5af40ff8c1e190b3af0b7f6ac8e63b99dd3662d6.nq.gz
│   ├── 5b77df0c63af9558e9d81e924c652488cc71110e.nq.gz
│   ├── 5e7d8263df39e9f6d9152a924a708ac112a9d293.nq.gz
│   ├── 63591d2debc331e1855084ae0b1ea3a1a9baf046.nq.gz
│   ├── 66772f16d379f825a4304fcc1cefda4576a996d2.nq.gz
│   ├── 6be1d3b7b085115f4e3edde15df5b5fc71b1bf3e.nq.gz
│   ├── 6e0154f3cdaeca46d868c097f3f03c881aa03c36.nq.gz
│   ├── 6e0b83ceda75995b26279b8df6789ce0dbe6fbd1.nq.gz
│   ├── 6e5c86c8e395c31859125dd1efb2c13cd00cb126.nq.gz
│   ├── 7076f7481e44d93d02a2e99dfebbc0f3d1334e15.nq.gz
│   ├── 77ed594a4fc1215caae0b06b38112a92788c2908.nq.gz
│   ├── 790c64ad22d7a440485ace3944778bffd5e5efa2.nq.gz
│   ├── 7b9278a5481c03d2fcbb247a0f521a7f8abc137b.nq.gz
│   ├── 7f337e751978a03792c8f8610a90368953b10475.nq.gz
│   ├── 84c310a8743d78ace4984c8c18961e38455d1a92.nq.gz
│   ├── 84cd07247096943a1cb22ea4c46784e46c35608d.nq.gz
│   ├── 85b4fcb93ac47cfb755805fba2fa4cb618855c0e.nq.gz
│   ├── 86359118147a603ed00770a1259b70b4bece6206.nq.gz
│   ├── 8791ae97a7eae226209da168667bbe8ff61e7c29.nq.gz
│   ├── 8c1015c837be91b16506fec2165f6426f959d4fd.nq.gz
│   ├── 8dde3eb9fdb612afd3d826202dd3f49417de7627.nq.gz
│   ├── 8ea8cab27037ba2bc3e4806933d9ecbf61ba015a.nq.gz
│   ├── 8f87927aee6fdb3b1a1dbfae913b031e6bffbcc4.nq.gz
│   ├── 9525126871d7ccd6807570812ec6a71c784ecdc5.nq.gz
│   ├── 95bc050fa0dffb8f1654eac8c6d1f6f3dc46e4c9.nq.gz
│   ├── 962d942efa5d9826beb45f6bae03e6fd0bd99972.nq.gz
│   ├── 999633ad2f5280d80367a31df15b23ff26dc9501.nq.gz
│   ├── 9addd500851aa3a07246929d5b748ef022425a13.nq.gz
│   ├── 9ba59a73dc4c15ade521a290da01eb7ae55fb1af.nq.gz
│   ├── 9f6d7a38c83ae7204a47763bf2e3c6c61891d19a.nq.gz
│   ├── 9fd522d3399ab4d0e6969dff46668d667a63f10e.nq.gz
│   ├── a26bef471555a813fb8abfb4cd3bf6d2fcc3884b.nq.gz
│   ├── a31d09bf31f6a126a8a7f9f6249e99c890b460d7.nq.gz
│   ├── a9953cb64c4f1cd4fab6cb03f03d71370c561df5.nq.gz
│   ├── a9adc17376d2751d604a5af7012929d7471ea6c6.nq.gz
│   ├── aa0505e39d92cc75e221c50862c7bffafbe21b46.nq.gz
│   ├── ab262d34d23658ce696c638f50bcc6f3a5aac131.nq.gz
│   ├── abaae13a9708a40ed074aaf90a03c8b0c9494c37.nq.gz
│   ├── ad21360909bd5315c642d90a8a69f5e2184853bf.nq.gz
│   ├── ad2baf3e8a04594542ae5259a45d4993c20ac2e9.nq.gz
│   ├── b15f90156374a15963134cb8a1bb8fa7901590ab.nq.gz
│   ├── b28f51b80bcf34fc32eb3a39894c0ae67bda518e.nq.gz
│   ├── b2df571e19b07f02300aaf3a08940b8d7a7c307a.nq.gz
│   ├── b602baede445aba990165a6941acee50e13c22aa.nq.gz
│   ├── b66758027f72c14c03b64999ab41e41a2b6aff7d.nq.gz
│   ├── b6e47617de110dea7ca47e087ff1347cc2646eda.nq.gz
│   ├── b7839455a64a067a15886474164b6d4476c49133.nq.gz
│   ├── b8a1116d8a47944f8c408ffe6131276773a3f582.nq.gz
│   ├── b8c2c8789b277f9696eaec06ce4e57738fe1ff9a.nq.gz
│   ├── b8c8abdfe00fba9c8ea0e7df254532219eb22e54.nq.gz
│   ├── ba14375ede5888a1342a047af2f8157c152e3699.nq.gz
│   ├── bcd72749d603ff10db651befe5e33da9e6a10acb.nq.gz
│   ├── bda56f2f92f9b6ed1b2f9921dc0d195600b48187.nq.gz
│   ├── c2831c9be7a4b56f914f02789641e0dc50b81e2c.nq.gz
│   ├── c3d7263dcbb306f749fb64975d69cf9cdbbf99e0.nq.gz
│   ├── c553ba517b6791c24e9e6bfb8223a67cc09e25e6.nq.gz
│   ├── c6370c0e89a893433f120e67fee7b169e8296a75.nq.gz
│   ├── c76078ecf89286714763fa2a87a7f186d541b8f7.nq.gz
│   ├── cb2ea801d67bb23204da7872fc8d099e477ad760.nq.gz
│   ├── cbada97743e5d082a35915d8ce9541e2a2adb042.nq.gz
│   ├── cbd6a72e6160a1fa87caa00730db449edeb428a9.nq.gz
│   ├── cc7a6b95485ad6ff2d242889fb5adbf4e83beeb1.nq.gz
│   ├── ce3a82f99d56c91237a72e8993d5fa4072b303aa.nq.gz
│   ├── d2d38d786ba5ad085769d0594075e3237f3941a0.nq.gz
│   ├── d4258c01ff6b38aa0a56ab831f28cc2751be9393.nq.gz
│   ├── d57a1208f3c7e0d97bd5cc08dd1a7d37f635763a.nq.gz
│   ├── d57b32deb9e07ce9f655d1ce74fbd264c5e9a2cf.nq.gz
│   ├── d7cfe34767396881a2492f53c4a6f6fe7bef947d.nq.gz
│   ├── d7f537333901b547ead0c7965e37088e7fbc36eb.nq.gz
│   ├── da530974aaffe52a31531c2ad61a3bb466e980c5.nq.gz
│   ├── dbeb10788b6ca42acdabf8a8f4b71bb224131bed.nq.gz
│   ├── dd61b549081fe63743dba62a21185b0d0ba47c14.nq.gz
│   ├── de08e6f82b70117fd15db96ad4dda8f5a5798a7c.nq.gz
│   ├── dffa541138552dbcc01e35fccb2e73e4318e12e5.nq.gz
│   ├── e1e076aade898f961d9a3a7f70bbca440ef8ad24.nq.gz
│   ├── e727675cda32a433d78dc1577e0e9bbcc394f09d.nq.gz
│   ├── e95140dff2677eb5259dce2b8377eab597e349ca.nq.gz
│   ├── ea1cec3cbea279be1a49a35faab2f43f9d8f44a8.nq.gz
│   ├── ef6d33f9b041f23987c5ad8656adf7ce23aa0e21.nq.gz
│   ├── f076646ba65607412bf99de4b34d876b7481bf60.nq.gz
│   ├── f314f675cbb48d840f331b03ad2f297f0daae999.nq.gz
│   ├── f5c088fb7801f9d7fdc0f4fc3d9e55a417046d0e.nq.gz
│   ├── f9fb4e65a629e8fee9131ec9a2f84087c21710f0.nq.gz
│   ├── fa3163dcf837109fde3e9590a2440c228a6f4920.nq.gz
│   ├── fcf3edc040fcd5134d4b8aef646d7029b5cfcbe7.nq.gz
│   ├── fe0533bf7c4cfc99f37e35e898719f18529a2431.nq.gz
│   └── ff949e18772a3bcbb5a477cca920a086357d5dba.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0f192230dc3df263eb95b6be4c3f00a6ea037879.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 132 files
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

[canonical/microk8s-core-addons](https://github.com/canonical/microk8s-core-addons)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
