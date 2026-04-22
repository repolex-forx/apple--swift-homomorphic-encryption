# Repolex Knowledge Graph of apple/swift-homomorphic-encryption

RDF knowledge graph data for [apple/swift-homomorphic-encryption](https://github.com/apple/swift-homomorphic-encryption), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-homomorphic-encryption
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6fb73e701a4e6b59564e7abae3774084b0fb49cc
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 6fb73e701a4e6b59564e7abae3774084b0fb49cc.nq.gz
│   └── repolex
│       └── 6fb73e701a4e6b59564e7abae3774084b0fb49cc
│           └── chunk-001.nq.gz
├── blob
│   ├── 00211359c7ceb9593c98852fafadea5fb55ca3c6.nq.gz
│   ├── 022ff308a30050445cedfae268971c8d7ee5e360.nq.gz
│   ├── 02bb7300b5b17a45cb7e0d9447ca0c6589f44035.nq.gz
│   ├── 04f8e12e3b6d72acc36a007e4205e8ea7ddc68fc.nq.gz
│   ├── 0597a83aef886c9e2774a1bbaefe52219159b889.nq.gz
│   ├── 0674e3b8fc1c8b8445b1d8c75f9d387627101af3.nq.gz
│   ├── 0816460b0319a8e2c717ba9d527d7175f12aaf68.nq.gz
│   ├── 094178e5ca8a7e6f587b63ce82af48f9163b568e.nq.gz
│   ├── 095a0964525ec0f112332a51a8e4fdbf8d54ea5b.nq.gz
│   ├── 0a3f359ef258d395181f15761ea5f321de619b80.nq.gz
│   ├── 0dfedb4fa7c052e81acc9fc2d93e193f1d21483b.nq.gz
│   ├── 0e89c8fbf8f7c824f54f9a21468d99c7f08a4451.nq.gz
│   ├── 0ea27e892b31c2ab2c5c558398e01c72ad6f02a8.nq.gz
│   ├── 0fa5641301ff89b225164c537551122f1970b330.nq.gz
│   ├── 10b995e9b3db65f2427c87b9fc70ca3236367710.nq.gz
│   ├── 10fa9300f8858a1fef1ab9c38fe0c3675f0a95d9.nq.gz
│   ├── 121072f262fe4be088ad68a78f36a4f654403aee.nq.gz
│   ├── 125aba678cd56739fbea015e17d6a2d711dd1ac5.nq.gz
│   ├── 126bf13e748625970f9cc9ccb0cf7702cb21632c.nq.gz
│   ├── 163133147fbee22eacf361f790f3509c825f2459.nq.gz
│   ├── 1783826439a5e741626a904ae424693744212d2f.nq.gz
│   ├── 1a2fd790d93646e789767f804523488df8c16c87.nq.gz
│   ├── 1ab3125537964682f418ede8df3ba87a575bc24d.nq.gz
│   ├── 1acbcb0ba3bc55103f9a95b90cb8293d15a88f5f.nq.gz
│   ├── 1b7bff3027dce9db70cf3ba6ffe0bbbcbd0da211.nq.gz
│   ├── 1c297b71af0512b3728e1df90638cb901138432f.nq.gz
│   ├── 1cd851903b7216b59d2d1a93b3548ba133a87b9a.nq.gz
│   ├── 1d8a14c94c6e0c10b29515bfb6c9b6ea127c0faa.nq.gz
│   ├── 1fe62643e3feb3d60bee631087d9289f47a8d616.nq.gz
│   ├── 2169c8840770b484ade31a483832aac59ba2ef2e.nq.gz
│   ├── 22ea88d557ae7f04bcb8eabc817059b328724fd6.nq.gz
│   ├── 23aafd6e7f20f86b9c1c66e82cb8e11c12f8d669.nq.gz
│   ├── 23ecafda5b5aab94820467d993c5781717f8ac6a.nq.gz
│   ├── 2524ca2422ba8e3978c26081fc8374546d550c95.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26863606103e882481dbefa516c62b831f4922e1.nq.gz
│   ├── 29081ea8259e349c55fbd9eb3f5f30efc33b37c8.nq.gz
│   ├── 2923b33371e8739c8938f8426923d72610319d76.nq.gz
│   ├── 2dc02bc4a826c88125efc954de39c3c58beb29d6.nq.gz
│   ├── 2e110a52e0118dc391c9c3ffbd772b57f11530ef.nq.gz
│   ├── 2eaaafcc49fe55803d8939616ae940dd7b094fd2.nq.gz
│   ├── 2ecd4c25274fb5c1d3805ee8cc973c21eb0ff1ab.nq.gz
│   ├── 3068c9dcc2bd0409ea6cf260deff97b954c59f44.nq.gz
│   ├── 306d47c303977f3d258ba042a6d75234e7e2764f.nq.gz
│   ├── 3116c5784794601ca6a8290e97de4a224c8f407b.nq.gz
│   ├── 32c8d82f0d9b86d125ad402617b411eeecfe412c.nq.gz
│   ├── 32cc3b92804564006a751d0c8e509b3c1bb511db.nq.gz
│   ├── 334fd9961c0f5a384f4f0fb68d71ccafafad547f.nq.gz
│   ├── 3521ed5809fd1a26509ee2baa2e45eb0577c4274.nq.gz
│   ├── 37122f98fcc2258f6a5dba0004e32065547eed63.nq.gz
│   ├── 37cb8d0ea50a58f56a803c8d052784dc8431a582.nq.gz
│   ├── 394f914265e732a593a95da34915486c7daac396.nq.gz
│   ├── 3a965ea8e6cbc7fd28c22cc549d4cfa88ed4ad48.nq.gz
│   ├── 3b92f0d71cc9b8ffe1a85846a245b7d49e8c858a.nq.gz
│   ├── 3ff446611f50dcdeeae5db846ff0aaa271c61d5b.nq.gz
│   ├── 45a142ec9c2a02d28ca7476ae2cf5c0c658a00b1.nq.gz
│   ├── 45b7d5972b90919f462be52bd7b2c5c3e80816a0.nq.gz
│   ├── 4875ba5e5e5d29e2f26533157c3c3feb3a7e7184.nq.gz
│   ├── 4a8b7a2df622952f0e2ee40be08548114e39a2cb.nq.gz
│   ├── 4ddde1803c16c896f345f9b121dc479a3a20bb74.nq.gz
│   ├── 4e585ef599a473800e22e7d506576a3f6394fd09.nq.gz
│   ├── 50658fa15d0cd326f98eef5b2f20d52e9bccc4fb.nq.gz
│   ├── 52498adc60c07dac50580065661f766d5906bad7.nq.gz
│   ├── 527f0845b1415f0b48e56bdb87d820523f22c7e6.nq.gz
│   ├── 52cfe496dba5dc00bb7158facf3f66b053a7f95e.nq.gz
│   ├── 567f87ebd04fe0be4dfca9aac19e7686f791f322.nq.gz
│   ├── 5756e3a372955e8c8e49132ed142e2b1aa94ad02.nq.gz
│   ├── 57ca59ca478abe45126e9a81c738da0f4edbb8f4.nq.gz
│   ├── 5885c547cc98fb2e585a46ef97fbde1da7de2e24.nq.gz
│   ├── 589e51cd7f69eb8cfd6aceb8bec8bfeb550ae4bc.nq.gz
│   ├── 5a3dd1ad03d110ae45843d80bfe9097a1ef450d9.nq.gz
│   ├── 5b4efb50dd7fafc2bd0a2dd3b7051283b5a87d56.nq.gz
│   ├── 5bc3f8117653adf442ba905461f9c7bb61938d3e.nq.gz
│   ├── 5d677717dac83d9f142f777d96b5d4ddbf661752.nq.gz
│   ├── 5dce25c6e103dfee96f10f15fb6285db49c1da7b.nq.gz
│   ├── 5f76b2f5f51e03d12cd46cc54c11441b7f0256aa.nq.gz
│   ├── 600fa84e5eca4876606564c18e9d7135cc581357.nq.gz
│   ├── 605b9b35eeacdc4748e320be93e67ff1112c1d89.nq.gz
│   ├── 60a6f0163ef5485b921f420fd4bb87d3bc62d851.nq.gz
│   ├── 60e1b04d3b3aa76ea515dbeb8fcb8a64ff7966c6.nq.gz
│   ├── 6111e6c6db2f03a35f93b21898a8baa62d08f0a7.nq.gz
│   ├── 63a77f42b75fd6d7a6e0bdb156b6d34ee5d3e765.nq.gz
│   ├── 651d7c8c99d6baa2689c3ac5e46de9fba7dba796.nq.gz
│   ├── 657a7b6d849d4e55c4e036eac19a290ce677d8f3.nq.gz
│   ├── 67a03320feaea29bba7e92af327745006e29440f.nq.gz
│   ├── 6821417c619807a899f675a5c89f4e2fa2347b21.nq.gz
│   ├── 69592850f968261682b0beda998959f593677866.nq.gz
│   ├── 6ae2b60530ec09c836bb0f7a434fa514fee340db.nq.gz
│   ├── 6bb49d8b6f88d308c1b84462f9fb696715f64889.nq.gz
│   ├── 71802057f4a1091e97b0edc61fe480409cf6a0af.nq.gz
│   ├── 7324031733e9897493e74ebaf613ad3f6738b542.nq.gz
│   ├── 739c33262811e7469bb56be9396b0e8803c7c045.nq.gz
│   ├── 739e63d92347a80f2f181c7143b5237e2a7f0aad.nq.gz
│   ├── 742aae11c1942eca9e94cbd66223ca86dae99079.nq.gz
│   ├── 75aec3ea4baf32956a28309b853833e98a4eafbb.nq.gz
│   ├── 75af4c413f2c16e4b87acd23938b8b390edc1850.nq.gz
│   ├── 76c78ec44685d33e14202b56c9cb5d4750120a9c.nq.gz
│   ├── 76f72773c3ca4fa38e37cafe491b0ab8d7256e38.nq.gz
│   ├── 795fc2e43c91ac1febb622804ee42caa3ae37e55.nq.gz
│   ├── 7de7914bcb16e73ff749de2c4ae1f61a78d42114.nq.gz
│   ├── 7e4a597cfbde1068bc3d84f9dad461484c5f7454.nq.gz
│   ├── 80fb9297cc72325f0cd647f0972fd2d00935934a.nq.gz
│   ├── 81c7e88e21a21a0b5979da15dfaa49d8fff68316.nq.gz
│   ├── 82ce6360236a0939967958026926bcdeb97825fb.nq.gz
│   ├── 83a2a99edbf9d53253bc2d8cbb2dff045aa8b151.nq.gz
│   ├── 843c5a6c88c278864813dff03843d9bce0721215.nq.gz
│   ├── 852b1f5c355da5fabb0a86ad1534f7e92fe5bca4.nq.gz
│   ├── 85d59cc6008b6c8190400345ca536109c326a5a3.nq.gz
│   ├── 865e733c29c4065d2d357477744549dc9303a70a.nq.gz
│   ├── 8a87d2d66357e0c2c8ce4c8dd597ed491138186d.nq.gz
│   ├── 8ea2baad86d490d04857c4239a9c53551eabdab6.nq.gz
│   ├── 8fec214b15aa0a22e8073bacd465558535a4b7f3.nq.gz
│   ├── 91e63815ae54f0fc77a5496304c35b45d74ac430.nq.gz
│   ├── 9210b516e73a4ecaf76fd9435d225d2232631dc3.nq.gz
│   ├── 98b1ca4f54e5f95cd753dc9362103356624660f7.nq.gz
│   ├── 9a22d35e548cd17b678303cdb77f225d42d06db7.nq.gz
│   ├── 9cf41c6f9c21211b5b5dab58967d3bf57c7818f9.nq.gz
│   ├── 9f8166eddbab3323612ba16b63ac3fcaa2751198.nq.gz
│   ├── a1bc3cc2ab0563cb5fcde0ce60fc9ceedf359208.nq.gz
│   ├── a2af850ee2ec3d51271e39d47eb124beec756af7.nq.gz
│   ├── a2b55397016e6672ed5c16788a734a939d7f7a26.nq.gz
│   ├── a36935687eedd8e32ada89810de18212ef59b807.nq.gz
│   ├── a3c8a88f07435ae480eeff68ac67ff003de1bb5d.nq.gz
│   ├── a3fe23dfc3fa9f12f412e033e69c84dc81e12c86.nq.gz
│   ├── a4244206f669bfcd095e964ee47b0d269d21caee.nq.gz
│   ├── a5f31217cee351ee15c5e54812a036368719ff57.nq.gz
│   ├── a7920f3c517d389eff546c328fcdae773a544e4a.nq.gz
│   ├── a8cbdb237c1baab368f6eabb85f625f984f4e949.nq.gz
│   ├── a93fa569325266e6174a11aff21d78d909189a50.nq.gz
│   ├── a9b7a9ef2a2c75612ce619016a9db4b14d4e14e1.nq.gz
│   ├── ab6624b1a8bb175dcf6672e11a045074b8e9ddf8.nq.gz
│   ├── ab9a0c8af3a7df44adf292f1392ab937479edb38.nq.gz
│   ├── acfa891f101742ce3e40e0837a4804ff81a9edec.nq.gz
│   ├── adf463aceca714aecf5331d7594e83b32a12a515.nq.gz
│   ├── ae3fafd7a78d3ca6b9c7da3fc8e9f462d1bfba7b.nq.gz
│   ├── b4b0ba5b69ecab51ba5912a39d7e6daca35214eb.nq.gz
│   ├── b50cffb6f716741e34ca08cb5c5efa2f1b9be379.nq.gz
│   ├── b586d3f12270e55ddd33601ede3e82b02a244efd.nq.gz
│   ├── b8ac3f2f09b0a7dff8c0966b47fd4ad06feffef9.nq.gz
│   ├── b8fbdd4392223ee766b0db5903153a7703bb0f84.nq.gz
│   ├── b8fc8ba2bad5cd15f59e25540236d32c9ccfe401.nq.gz
│   ├── b967b692b1157c339999ba3eca2cc59e909de49d.nq.gz
│   ├── bb61c2e44aff46c641566a88ba8a98a10dd8dcfe.nq.gz
│   ├── bc14c598bff1a1c22370e62daf9b247a371a53fa.nq.gz
│   ├── bcc65d34c87a71f7beba7fb1f1b08fb1d456ad7d.nq.gz
│   ├── be3260a251a6cc9df248a520e49a6ade9ff7b9bf.nq.gz
│   ├── be4dd0d70353ca3766324fafab269274bfd68be3.nq.gz
│   ├── be69f3ea4feb1d8793037fca9d10233f11746ea8.nq.gz
│   ├── bfc70765e84bc6b52b4f44c8340263980fa6b722.nq.gz
│   ├── c0c71f0333bdd8180e2db41564b2dcf80be68b57.nq.gz
│   ├── c2097aa2e742c68f6a28b1a3e0803d610b3065ef.nq.gz
│   ├── c24b87621e284d3bcca24fabadc6c77e6e400658.nq.gz
│   ├── c86c4428056402e4817ea4a0c6e41a2e2e1ac70a.nq.gz
│   ├── cb1582b6f79127003b5ef4c434dc0620aa2bf888.nq.gz
│   ├── cbdccb9beba84b39784aa6647b1a82878fff61c9.nq.gz
│   ├── cc22a4c34775d27788fcd8202102d6cfb40e8ca7.nq.gz
│   ├── ceb78c492b55130b8f98d9ac5b4053cf9867010d.nq.gz
│   ├── cf43da1c2b54db6416761803576cef12fe8aac13.nq.gz
│   ├── cf5a80a33563f990029aa62d97d0c7fc5d5a75e1.nq.gz
│   ├── d138ff195780edbcb6a4a19a704b7a6aaf000a92.nq.gz
│   ├── d22f0c3b0732718eafd12854d201db4dddee36ee.nq.gz
│   ├── d24600a95290c2afc05bb0df1cc41e1362e7cc85.nq.gz
│   ├── d4cac71164f195624ff35bc802fbd5029cdedbca.nq.gz
│   ├── d5439997b06b2a0aff176a17fc833a83b8e91d4e.nq.gz
│   ├── d55f15420321fa929c375cccab527f33f70cf6d0.nq.gz
│   ├── d7eb0ba2c590e5daf71a447cfb5abe6db98582df.nq.gz
│   ├── d7f397844d345bd532dfe77043f5dee7fe565ad1.nq.gz
│   ├── db8e69910fdb347dddc59bab4f7e2e0378a52ec0.nq.gz
│   ├── dc27cfb1a6227eeac204a5abfb17b7ee6dc8e98f.nq.gz
│   ├── de70b6ec4df0ae56b4fab5f238f4ec8c7ced4c6f.nq.gz
│   ├── e03faad6b8508da075ab65028e4c36b20ca3055b.nq.gz
│   ├── e25531c6c47e0f1dd1f43759310cef3758a4d92a.nq.gz
│   ├── e37d4e3946fc596c839ccebf9344a5bb7759d825.nq.gz
│   ├── e414216852460d40a11d746b3c94d1e7c1f4e4d9.nq.gz
│   ├── e5887f7eac1d0017ba2f6a6ca37eb5998cee3316.nq.gz
│   ├── e717d61b816549030b260226e244fb05119dadc6.nq.gz
│   ├── eae9f18e59d45832d2b05a1627c286360195f70c.nq.gz
│   ├── eb2c90670f2e14b68d5b2681d422e51b4f9417a8.nq.gz
│   ├── ebd3684cf13bc3c8848da3c2b3d755f3a46da0d5.nq.gz
│   ├── ed61ab16fdbb1b855680ac0c905863eb03a948f9.nq.gz
│   ├── ee40dca3ac32d1a41c9d0936f61a9f22dc0ded2c.nq.gz
│   ├── ee67592db8f1035c67428ecc68a50ea4822cacd7.nq.gz
│   ├── f06c6fbdbdbaa13da91a6ed3e4507a44502d5af3.nq.gz
│   ├── f20bb7e15f9454bfb7cc95f36fea2d42996be312.nq.gz
│   ├── f55a78d2ea472995a9d520c5469ceab137a87c2c.nq.gz
│   ├── f7848c559db5e93969cc57af76da4af4c6e0d77f.nq.gz
│   ├── f84a820a25939f6494c13538f99309742329907f.nq.gz
│   ├── f863975d74dcc7b238cd58c4ea3b851237ca0703.nq.gz
│   ├── f94c19f712bb278808ac8137f4510f88bea47023.nq.gz
│   ├── fa00086d54f2e40e093f600d5ec7a02c6d0ea281.nq.gz
│   ├── fb92e6fb58c4417630de720cbc1175a5b37f4df7.nq.gz
│   └── fbc2903e4ecf0ec3f57f5545ee8bb9686209b6e9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6fb73e701a4e6b59564e7abae3774084b0fb49cc.nq.gz
├── issue
│   └── issue.nq.gz
└── pr
    └── pr.nq.gz

13 directories, 200 files
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

[apple/swift-homomorphic-encryption](https://github.com/apple/swift-homomorphic-encryption)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
