# Repolex Knowledge Graph of celery/cyme

RDF knowledge graph data for [celery/cyme](https://github.com/celery/cyme), parsed by [repolex](https://repolex.ai).

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
rlex download celery/cyme
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c49047318c56f6674bd6d6ea6673b48be4eb7886
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c49047318c56f6674bd6d6ea6673b48be4eb7886
│           └── chunk-001.nq.gz
├── blob
│   ├── 027281c78f34d0dcacfc08cc73a8b67cf101fd73.nq.gz
│   ├── 027490b84711a2382bf639e1cd4660d87d94a215.nq.gz
│   ├── 02d8727cd9acbde8e9acc5c5938365589fe0ea73.nq.gz
│   ├── 067099a8e2b4f4927939057209037c845df1f80d.nq.gz
│   ├── 08b9d42bc301a3899f310a864a5845a32331aab7.nq.gz
│   ├── 09d8d3a73e3f27f1f3bf86e975b2c991487f0bd8.nq.gz
│   ├── 0af95142d7ece34a43eef40d16ae81e8545cc7ce.nq.gz
│   ├── 0c700bcd08f0961fae979b3fec35cbb82ccc999c.nq.gz
│   ├── 0ca33090f64096af955e35517e6cca99629a4332.nq.gz
│   ├── 0d653aabcedd7b7c95a48a46878f8c40367d165a.nq.gz
│   ├── 0dec8b2a0f497e4bb63b0a3f69c8b67e9ba7f2d2.nq.gz
│   ├── 1a5db5a6c8c09a67badfced3dcbd91f633ba2119.nq.gz
│   ├── 1b01decf9d5aedb4d9019af78aab5e1480159cc9.nq.gz
│   ├── 1c92d67f67de89aa20ab2717fd633c25a42bd3f2.nq.gz
│   ├── 1d365d5471a08696f36746aeb0bb2feabf7086d6.nq.gz
│   ├── 1ea219cf7ed2ccd6b038808badb22c427f83b5d4.nq.gz
│   ├── 214dfef3b6844b0703cc775d334ff31b38517501.nq.gz
│   ├── 220d6fa648c2b455cdf281443e29a7d5ce2ffa59.nq.gz
│   ├── 262e3d3ee122a314aba94b4dd4b9f54513eaaaf6.nq.gz
│   ├── 273cd7e6f1d3289fec2ac5b55661f138f37f59a2.nq.gz
│   ├── 28347cd8212ef0a4a91e2f258ef7c4efb416dd21.nq.gz
│   ├── 2bc72dbcf3b59ba775a90ef654df836107f70a12.nq.gz
│   ├── 2d38f9f2e65c0185f88a4340af68abe6c6e734d4.nq.gz
│   ├── 305a1fddd62378d2ef19c9d51b0a14c2781c32ea.nq.gz
│   ├── 3a89c7ac7893658ba2def07d606f6c8fb29e6b21.nq.gz
│   ├── 3f5b4e61b26f25e38bef75c644987b3c0cb92c4b.nq.gz
│   ├── 408760422a61bec6ef7e449db6ee3780c07f7cd5.nq.gz
│   ├── 45ed2b6aa466b4a5b76a410fe1cf168ea93dbe15.nq.gz
│   ├── 470c23d14b05ddc04215317eb6db8d44fc9e0ade.nq.gz
│   ├── 4c9ec9bea7ef783d1b330370445c75c7ad41d948.nq.gz
│   ├── 4eff5848f4f9d13c61d67a14e673ea566d5c07a8.nq.gz
│   ├── 4f3c9193f4a343a1438fc482baaf5257e43bbbec.nq.gz
│   ├── 50a8e2eea678a47edb072f344c720590d8cbc6a8.nq.gz
│   ├── 5135b3a08b711be16c3aa0d5e4d032e226150f9e.nq.gz
│   ├── 51c1f138767d4d9f71a9a24d8386461aadcb5b0b.nq.gz
│   ├── 530cd221dcec84410901d4435e5b6f680a38762a.nq.gz
│   ├── 53672dbf69a1108a85a1bd6e8e53f87cbf604dee.nq.gz
│   ├── 557163c44a142715bfc1597cd7ec08e9c9ef9419.nq.gz
│   ├── 5b7c268756b3d43b933eb39c44324eebe0c6bd03.nq.gz
│   ├── 62c53a1196a130cdd9f21252324b6f3097cf688a.nq.gz
│   ├── 632f8697f28a9142a2524d3545efd391bc99c966.nq.gz
│   ├── 638d20059c0797955fe3b1e882bd80139595cce6.nq.gz
│   ├── 655c460ceda21d7fc89ec1674b5aece8ab1f98bd.nq.gz
│   ├── 6695b02082bca633e061aad845a09eacc2ad3514.nq.gz
│   ├── 71d3bbea717d7978dddb0fe439c723572e90a6fb.nq.gz
│   ├── 72e269f98e5c02790b549c1a6e94d8d7f8849619.nq.gz
│   ├── 76541584dd5edfd3befcfaa53a3ee6bbfcc69bb2.nq.gz
│   ├── 79b84ca68a409f1f75dcce5b35af7210cd053495.nq.gz
│   ├── 7a1a08941a171811092d94a01301bdec3da19b36.nq.gz
│   ├── 7c3e1375e1d94d85e90ea52a6c26f27f53dfd55e.nq.gz
│   ├── 809096dfbb69d4e14fa241c0fb0cd32943aa3448.nq.gz
│   ├── 8560faf9c80b01b651e6bcd41702b3fd34e26141.nq.gz
│   ├── 85b790601538d919a023810d95ae8d0f9a8127fe.nq.gz
│   ├── 865b18dc3f0fd4203f8102cbc2aa9b41a7e46c62.nq.gz
│   ├── 88737bc7b91b41ae6faba179e80f6b94d5d73932.nq.gz
│   ├── 89bfc449c7a0b5f86c7eb29688e49f67194f5558.nq.gz
│   ├── 8a05d62132bb5900868e834bd683a0b1ec968a64.nq.gz
│   ├── 92cacd285355271487b7e379dba6ca60f9a554a4.nq.gz
│   ├── 98af398e65710805885b21e82155ad097f0ab857.nq.gz
│   ├── 9a16bdda42fb342b15ccc1e64a3327e7dde9e2fe.nq.gz
│   ├── 9a32ff446685acc0b80179ed18aa940b52115be9.nq.gz
│   ├── 9aaf3658ccc0be20bd551043fb171aa015ac2e7d.nq.gz
│   ├── 9ad052cc5b28950b4fbe02d41b0270604118b3b2.nq.gz
│   ├── 9d6fc78a3f32c6a4eb3f45e0ced75d80f757081c.nq.gz
│   ├── 9e6023a8e8f99e17e23de1852619ee0bef2c59fb.nq.gz
│   ├── 9ed95efcfb0c881dbbe50a3ac1c5429f1ec84794.nq.gz
│   ├── a03a8badd9f5bb9d56488a021f053f17f1395ab6.nq.gz
│   ├── a15fc2b3590a13f9d2066d723fa4af08a80d025e.nq.gz
│   ├── a34a62b3f9860356f63590b23247cd60492583bf.nq.gz
│   ├── a4d7baa016d651773c87eae000656088042298ca.nq.gz
│   ├── a53dbba3e8c3abdf7ee0722c389b9883e16d75ca.nq.gz
│   ├── a55ce64c4a17a3804af7e22b15c436d75cacb89f.nq.gz
│   ├── aca74723974bd4b17b09dd7457e659050f251956.nq.gz
│   ├── ad221c8fc848246d7828c4676c265012a64364c1.nq.gz
│   ├── af63e584c89de59ada5645aef07a68ec430f2f7d.nq.gz
│   ├── b1b929602135243412fa5f38bc713d1228af0eac.nq.gz
│   ├── b24d1f819467692d7b40d4c56787c9556ab80391.nq.gz
│   ├── b69b1b9a8b474756cb665ff703646d89b8e9eab9.nq.gz
│   ├── b6da2d9f8f756777d7d407beda2b893796a42d83.nq.gz
│   ├── bef3f1fe322ae29c6a3271a13c5c41d5c9341f27.nq.gz
│   ├── cb58a86d0b8269e4f8f4b2344881b6538dc1c89b.nq.gz
│   ├── cb68942964ad653660d5d95336295ba55287d639.nq.gz
│   ├── d28fa178ccab90f0b36aec3627c267e61731e5d7.nq.gz
│   ├── d43344b4bf066cacefcbc35fa5cfa352a275c697.nq.gz
│   ├── d475615eaa7d1aa48df994168e61054153234b20.nq.gz
│   ├── d4aaeb296c0fab4e6708684383137f5d7feaa5b7.nq.gz
│   ├── d506b8db63dc5064a39fcc6ef5ebe57d1603afd7.nq.gz
│   ├── d5392743b9e6efee03dd6a37108ec4c57c5d2c4f.nq.gz
│   ├── d56ba12f866123c29b343f749b10408ff93c6072.nq.gz
│   ├── e1e09bf7f19dbde34c79de6306417c96a58c3797.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9dc7ca038c576a82ee66bb74e01026c42bac55b.nq.gz
│   ├── e9e9084b19625bdfdbf12c4f792e44987023f109.nq.gz
│   ├── eacd205cd0df9204d68efe2e31328fe38dc573f3.nq.gz
│   ├── ed5c3a69ad4e35b0dc2641e230d73d5990b5ae53.nq.gz
│   ├── ee4eccbc7266a9e981740f94bc20393c3f438d31.nq.gz
│   ├── f15bde729eb7dd44c28e915e18fcf7afd005981b.nq.gz
│   ├── f28d208930f74e3377965c780953a54dca54975a.nq.gz
│   ├── f3ae315bc274e564fa01e1c14f3b8999042a136f.nq.gz
│   ├── f3cc454e4376f259c2ad41654083f79f54de9ff8.nq.gz
│   ├── f47684e5925cda7bf1b0b996d85719244f12dea8.nq.gz
│   ├── f868043f09a5fe90adb9eff7927a628c2e038847.nq.gz
│   ├── f8eaefcb82a21341fff34e3a9a35fc9a22ae0af7.nq.gz
│   ├── fb27832388cfe7d0b8a7273f848f4a320b28ba82.nq.gz
│   ├── fc5e79d653aa01fe9f954be8a1dfa67c47bf7fae.nq.gz
│   └── fd3dbb67ec9da06c02a0d51025d88e75c9af00e9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c49047318c56f6674bd6d6ea6673b48be4eb7886.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 114 files
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

[celery/cyme](https://github.com/celery/cyme)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
