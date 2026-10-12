# Repolex Knowledge Graph of graphql-python/graphene-django

RDF knowledge graph data for [graphql-python/graphene-django](https://github.com/graphql-python/graphene-django), parsed by [repolex](https://repolex.ai).

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
rlex download graphql-python/graphene-django
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0e6ef22a87dfaa3c22fce62ddcd7d91d6fe1a830
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0e6ef22a87dfaa3c22fce62ddcd7d91d6fe1a830
│           └── chunk-001.nq.gz
├── blob
│   ├── 009211294b92ac60b59045fd020ebfa8d9caabdb.nq.gz
│   ├── 0332b3c5e69862a4bfaa6a6c374111d906d7076b.nq.gz
│   ├── 03ad64d7b2fb782ede581b056f257ec12747cbd4.nq.gz
│   ├── 03da594c052c3a6d80f821eafdd246030d1eab63.nq.gz
│   ├── 042682fb87689ca2ef374842b3ed64d094035149.nq.gz
│   ├── 0491bcd30af175a1ffab38ca5020d21328f5ab57.nq.gz
│   ├── 058a58723475ce88583388ec6a3e88f9482ea4f9.nq.gz
│   ├── 066eec444d6e179e4b9145853567ef7ea1fdf9a4.nq.gz
│   ├── 098b11979bdecf8b9d6e15e687402ce354efec7b.nq.gz
│   ├── 09dcf69cc6c6ab2390a84f54fba9ddb5793c16c7.nq.gz
│   ├── 0d477b3309e925ad34dab7c883317dccd62919e7.nq.gz
│   ├── 0d74093af3e7a16e6216408c2dd3aafebe2e3a84.nq.gz
│   ├── 0e92701e8ff662599c31178f66cd8ecfb850a538.nq.gz
│   ├── 0f5b79a0b440d0dbaf008c1dbfcbfe57b9a86ed9.nq.gz
│   ├── 10d568f8dcf31c503d9cbbc11f78041a7ab01a22.nq.gz
│   ├── 12237df9595f0f485844d0d19c5caeaebb9999ee.nq.gz
│   ├── 17546c6b42a539d00bf21b060b3e46b2d7a34c6b.nq.gz
│   ├── 1b3235218fa08595dfd20ff3a5beb64430d98b68.nq.gz
│   ├── 1be08b1f799439ef7aecd0c5984062efb4a1ae7c.nq.gz
│   ├── 1de52f1899fa52c339214c0e38cb19074fb35e92.nq.gz
│   ├── 1e65da0a50f903b67a5f5becc0894b5a996aa4ec.nq.gz
│   ├── 1e97226257d3b6a428b4508756298358eb75f83e.nq.gz
│   ├── 1ec6598813fb43061409c3236cf80a9aca452059.nq.gz
│   ├── 1ede730c81697f3ee960f03bc1150c931e5c3f38.nq.gz
│   ├── 1f5e5842080ac8097514113c86dd3e1cf57f12a9.nq.gz
│   ├── 20b816e28cc80a2529af3e6239502fe60480290f.nq.gz
│   ├── 213bd8b745b0f3a34a807a3fe3b40e84bcd5d65e.nq.gz
│   ├── 22927d67c1abd87cfa0750caf8b6555e77b4587e.nq.gz
│   ├── 230b2fd2c10706d61216ba833bd47da7378fd731.nq.gz
│   ├── 2380632d819366c73271aff732e53bf231672bd3.nq.gz
│   ├── 23d71e87be8f5d55d6e1026f7f7dac7e1e9fdbac.nq.gz
│   ├── 2472c32d952fb255017d5574e516a54d4c9720b3.nq.gz
│   ├── 25972b88873808c523b5ba2eb64e244c74c426b0.nq.gz
│   ├── 26d84aa48fdef761f7aed8e4d21fe6a49d9e73ff.nq.gz
│   ├── 276ae37605bd89de16e68200bf553ed4461a4c54.nq.gz
│   ├── 2ca1de941ad03be6bf41ae14ae9af54428b72bb7.nq.gz
│   ├── 2f9a1c32ef0e6b251b6a9e3bc0e916f922b598ea.nq.gz
│   ├── 30b9af4ce072c2c6e9ad43dfc28daffb321c69f9.nq.gz
│   ├── 32238e52b6a36ccd98d9919248f3df9e7c8db5c3.nq.gz
│   ├── 3484ccb4923ef31b4f52f52206bd70d382b3530a.nq.gz
│   ├── 3682573d8828aa96ee845d1c8a8814c22ccfe16e.nq.gz
│   ├── 3702ce5cf9852fd7f949425e84de03e2111793b2.nq.gz
│   ├── 3957f01da6fafb827fd0e8f235aeafd92b2a9416.nq.gz
│   ├── 3ad01434b5c4ed8ee196e0c94c1345917f49b6e3.nq.gz
│   ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
│   ├── 3cf0d9adf057f83b2509cfdabded08a17774654c.nq.gz
│   ├── 3e078da74ec71d5bc030ea9f76289c3835fcc629.nq.gz
│   ├── 3e941b8a76090b388b6a295e13b2f3646b1e85f7.nq.gz
│   ├── 3fa8ba457283dc0999b9574918b7e04549a772f2.nq.gz
│   ├── 3fdb992a317d0a290ad034d2f92aebe5354a0881.nq.gz
│   ├── 425dce592c2a2437b924828874d396b658558712.nq.gz
│   ├── 467804dabcb097fbf7dce0dc14d080e5a2c5b235.nq.gz
│   ├── 46b8fc351d5ff89b02569d2115287ecb36deaea4.nq.gz
│   ├── 4ae2962c459f1a4dbba4c98a3f42fc8dcfbd0478.nq.gz
│   ├── 4b0f9d1a2a1ffa2a3d1ea9090ad2932bc4017503.nq.gz
│   ├── 4b5689e9b234d173f2672924ad0031b87a638b37.nq.gz
│   ├── 4d538ba741ec585955e7faa71eed5f0aa8439804.nq.gz
│   ├── 509a84c78c4e16b815c23576e6031f601922e6a3.nq.gz
│   ├── 51695c5d0019f646bbe5718518abf7aeed6df806.nq.gz
│   ├── 521e434d9d092e92e5aeb5aabe61385e43829041.nq.gz
│   ├── 52a9f2418d43c3e9e437d5c2ae886359595b6bd2.nq.gz
│   ├── 5560ba2ba80c3e305986467a1f89de3d322659b4.nq.gz
│   ├── 56fe51df5e1310c1448fbb68cb506d1b39974eab.nq.gz
│   ├── 5cba193729e63e13526ef28e58036c33cf105d80.nq.gz
│   ├── 5d88785dee7e1efdd43d0c9262a0fa1273c07ba1.nq.gz
│   ├── 5f84a171638d18ec2b5c8e1ba2b629351d418379.nq.gz
│   ├── 5f9e7a06ae2c673a31aaae3a18300ded7c678a0e.nq.gz
│   ├── 60996b43e61832d8c32a8d66657c4af249315f2f.nq.gz
│   ├── 60f00ef0ef347811e7b0c0921b7fda097acd9fcc.nq.gz
│   ├── 62759347bb9b3668ba5c5d98100d42791fe85edc.nq.gz
│   ├── 633c83f3b782628d4f629f4cc237ea7bd9348d90.nq.gz
│   ├── 64fa8507e0456735d7143a305c7e87a699f57489.nq.gz
│   ├── 653849ca4c2ae17760bbf3faa5388d75d68f46dc.nq.gz
│   ├── 68247a200192b0e608af0c1d6132e6a42b92f205.nq.gz
│   ├── 686f5ec0de4cd88a98bfbd67d7d04451be2cc053.nq.gz
│   ├── 68ffa663505791d10ae956bc4b31717c9c97b281.nq.gz
│   ├── 6c334f8d775c572e6a28bc7128e56127d633612b.nq.gz
│   ├── 6cc87340ddbbaf29474a83a3665867808324151d.nq.gz
│   ├── 6e02745de7d2329d32eafcf2a7d328ed4fdb5da5.nq.gz
│   ├── 6e04a7b0c8f2f1966dcc9d68009bfc9b559d0cd6.nq.gz
│   ├── 6fc0a1816d732b5baa45ecd452ed61e98bd2c8cd.nq.gz
│   ├── 700ae6fd3e2072a6ad61b84c3c2960fd961c3eef.nq.gz
│   ├── 71373420ef874289bbfde686e983ed03317e2dad.nq.gz
│   ├── 737c42227146993ffd556f1b1c0016a446813551.nq.gz
│   ├── 74f58b20a00749307e87acd78f4c5a318700cf45.nq.gz
│   ├── 757ef389c9548179ec938dbdad01d8df5be036dd.nq.gz
│   ├── 76f903aeac6f83d640220025010d819f9db70841.nq.gz
│   ├── 7e0d0c52031737511ab2c7bc983e21864d2608b8.nq.gz
│   ├── 7eb907ac859ed799266bbfc4dd9a580d5ff82328.nq.gz
│   ├── 7f40d519e242dab2e89a1ff92e6d23bcdc01ff05.nq.gz
│   ├── 801708ec8dee5ad53c2dd5440e48c4cdb8123cab.nq.gz
│   ├── 8595def2ccb45326ddaf02f240de1a652cde1b2e.nq.gz
│   ├── 85ea14520581b91b35989b734b6565f3dbe03821.nq.gz
│   ├── 88b7922aa51a604d44763a2fb644630a06618f25.nq.gz
│   ├── 8b85d456cfa77d6a8ecd9248251733fd41dcc2f5.nq.gz
│   ├── 8c39928fafe51ed44ceeed77f0fc5732add3853a.nq.gz
│   ├── 8c4e5e4baef11b5bbc78f2022e5fecc1f59e2f83.nq.gz
│   ├── 8c6a6e86c844034c1671bfffe699ca1d8839aaa0.nq.gz
│   ├── 8d8a34d6f93a1373da3c62be2dc4648b03ddb140.nq.gz
│   ├── 8ea69da28c9ae3e79c2113e977f69c85aca50016.nq.gz
│   ├── 900feeb3cfc2346c7905997da4b229c6256715f9.nq.gz
│   ├── 92a871fa1d13ccd082ab546b862d616b5465189c.nq.gz
│   ├── 941f3797a33e1e9b5c234fecd72cd9424443c750.nq.gz
│   ├── 954b0a809b7d289bebfe502b88854bf94f6acb56.nq.gz
│   ├── 95576a091756716f2ec4639c295d257d47994c33.nq.gz
│   ├── 95d339c3bc00135df563d43caabef62e33e946c9.nq.gz
│   ├── 95e353445090e9c64648ead143a5a7eb0fd9f7c1.nq.gz
│   ├── 99daca0dc8fe61ec89642dbb7f955f862a0f9500.nq.gz
│   ├── 9e9f457283ad221b22682f8c41ef383ce89edbc3.nq.gz
│   ├── 9f0c283a166e078dae075d133f2c8d2d1d88671d.nq.gz
│   ├── 9ffcc5cf3d070517afd5e8ac3d569468f41c5e4f.nq.gz
│   ├── a2fccda3a434a8f2f079749a6bf0507db0d358e2.nq.gz
│   ├── a39b155ac3ee946fb97efafe6ecbb42f571cd7ad.nq.gz
│   ├── a4097b183900c4626167d3f8b825cbe762559d25.nq.gz
│   ├── a4ecaae3f3d651ab429d71831a4fcedfd974309c.nq.gz
│   ├── a5ec5de2119d7a70c46827d7a54c8fb8256133f0.nq.gz
│   ├── a64ee36a79733d64ee3a32beaf269913b375291f.nq.gz
│   ├── a6c91a2baeb28cf782066d55f9eafad17f33f713.nq.gz
│   ├── a7443c07fd2218723d190bb747ef76559f910672.nq.gz
│   ├── a81a96c7dc92f5e0dc5b27b8bc180dcbcded976d.nq.gz
│   ├── ac08d478fb9cf1ca061d002da1ab1e497abddf3a.nq.gz
│   ├── b120b789598c18bee7f4c34804460c657cf2b1c2.nq.gz
│   ├── b155385d517c7782ca724e76a2c13facee57a480.nq.gz
│   ├── b1631c3c299c81dfaa92c1a26e16db03ea3bfb5a.nq.gz
│   ├── b4a4b7012583d3f6c27e73c5ba0c7b91b4eb3112.nq.gz
│   ├── b55d5dabc2d61217e27b33e4b57d5d8f261cb40b.nq.gz
│   ├── b8de8f9edbe7f5498af2e8fada262f295aa859d1.nq.gz
│   ├── b91475d7d61ff1682dfb2579c66181a8b91e6ca8.nq.gz
│   ├── b9356c8586cbc74bc82cd484a0b931afcc934b32.nq.gz
│   ├── b9c8df465f988436735ec557ffbe6aaace2694b9.nq.gz
│   ├── bf0ea367f68d0fb2a035f5c9eca61b4cc9368d31.nq.gz
│   ├── bfac78b19d8d4bc095b6e648ae9f38f572fbb100.nq.gz
│   ├── c0cb13ae78d61dcdb560049e649746b56bfdf2fc.nq.gz
│   ├── c2faddbd556141f81d77ecc42561975868c83e15.nq.gz
│   ├── c415147782372332a2d9ff00604c4a0495768339.nq.gz
│   ├── c661846c21b21cac6a53cd8dab0e3210a3972ae1.nq.gz
│   ├── cdf4c35463f1ee8abdcabe08683b4563a6ae237c.nq.gz
│   ├── d08d07b11215fd3c4e55282cb4d672ea4aeb49a4.nq.gz
│   ├── d0930e4af442172c64a4e1931c0733f6b0950a67.nq.gz
│   ├── d190a9b9420f4247e098cfd4ddd3127ddaf59197.nq.gz
│   ├── d209e0373e8bf742e790636581e3130fd5dde5d4.nq.gz
│   ├── d31c3eb9a26d7c36828bcb146414c3bdd951360a.nq.gz
│   ├── d3d33c25c3de1c772954f483451b78c922445ae7.nq.gz
│   ├── d52e370142921f5fb63a9b29580579aaf0e721c1.nq.gz
│   ├── da337003189096618834d7c65f3896633f01b1db.nq.gz
│   ├── dacdb3041845fd10925d299c401c5314094e94a8.nq.gz
│   ├── db91409c204d99813ccca3fda79d2ee3217c7c6c.nq.gz
│   ├── de0d72d18f3fe06d0847b62f524ade541ea82c08.nq.gz
│   ├── df97a570763061d9e1ef91d9a4b2da9af9aa4956.nq.gz
│   ├── e08660ccc5a5c41bf95adfce16d2d7f6d5ddbc99.nq.gz
│   ├── e0de1e3ed3503681a2681d9e94739b6b69381d39.nq.gz
│   ├── e310fe478ac0ccd61f542a47b85e37f716599fc0.nq.gz
│   ├── e4d7ea9ea9a0e6b757b0f688edaf69f525bd4fe6.nq.gz
│   ├── e4dbc0651c0d9fab2e365dc3bbc0584d32e3551e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e72b383d7deddae68f7355ff81709c7c1663db6e.nq.gz
│   ├── e81c8b2bb22cd9bab307013a76d16bad69963cf0.nq.gz
│   ├── e823a2e301f06ecaa6888a5ce79558e0d14d8d28.nq.gz
│   ├── ec4f2bd8646dd6343db43264b2532cf7adc310ec.nq.gz
│   ├── eeef4823fd4fe00e8dacb905ed1a9f99e471baa1.nq.gz
│   ├── f07f6f6d43875150cd6d56e4b4f7febb0c5c4754.nq.gz
│   ├── f1e4dde9311cd608580b762b42d5a8176cc0e297.nq.gz
│   ├── f1f1267808d348a6c550a1523c978af3c04fed42.nq.gz
│   ├── f38bb697bb7581fd91a3cba6000d1935ae79ae34.nq.gz
│   ├── f414a4c1710d106d12b884f0661a0faf8e0b7122.nq.gz
│   ├── f43063fe4d210197355301c0b6d5504741f75da7.nq.gz
│   ├── f6e955e07f345730751aaaa22883eb640010e48d.nq.gz
│   ├── f6ed031e8405232912aa8a29ec1bed948f59bf35.nq.gz
│   └── fb76b03958f3050f592e9bd5acb035387ef22013.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0e6ef22a87dfaa3c22fce62ddcd7d91d6fe1a830.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 177 files
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

[graphql-python/graphene-django](https://github.com/graphql-python/graphene-django)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
