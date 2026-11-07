# Repolex Knowledge Graph of ansible-collections/amazon.aws

RDF knowledge graph data for [ansible-collections/amazon.aws](https://github.com/ansible-collections/amazon.aws), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/amazon.aws
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── df3b9079f1a2d2a11151bb0840f94f9f13840f59
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── df3b9079f1a2d2a11151bb0840f94f9f13840f59
│           └── chunk-001.nq.gz
└── blob
    ├── 00451438c58ea51f93366c9ff9ae70810589b102.nq.gz
    ├── 00e84c65d87f3155d23e67aee408db6eadba7b02.nq.gz
    ├── 01bd81727ffc30ac8fb4e460914eaa6fc2f6eb59.nq.gz
    ├── 0231f2f8be86a34238a50f8b2bcb704537c4c5a3.nq.gz
    ├── 02da51094da45c45c32ae7ebbf98c7d51f1d79c8.nq.gz
    ├── 02da96a1bac8035d5e1f7635b1c4e3761475cdd7.nq.gz
    ├── 04109c2687bb1e9acaf8a5d5b0285ece52ec070c.nq.gz
    ├── 04cfe4ed1f9583953b0d6196fd3489cdc4a297e0.nq.gz
    ├── 04ea2eacc1501578d9ecfe9980ed5717775b804e.nq.gz
    ├── 04ed277c1d099e7879311147f5bd116ca26f6672.nq.gz
    ├── 0637f84d2d5469ea88ce3309e9227d8cba1d9ec5.nq.gz
    ├── 064df7754ba3071cf61e12c16817c60201ed24cb.nq.gz
    ├── 06515b8b186f7dfc12cc739f557e5092d549012a.nq.gz
    ├── 065ab2aacfeeb290b9bfa2b3579c19eecc304ca5.nq.gz
    ├── 06babe4a746a9ca524188e0fa35cad7555fce8d6.nq.gz
    ├── 072c7bbf6c0ecc1058a45d49e5ce06bb8e96f4e3.nq.gz
    ├── 07bbadbf4713cac6585f22641e6363bfdaddfaf2.nq.gz
    ├── 0841e3c93f426a62cd3744b8dcb2bdae31294338.nq.gz
    ├── 0a196e3e5b58dfd879c79276f94876136baddc8a.nq.gz
    ├── 0af08b50ec8bc334c893d6f7273e30e1973e457a.nq.gz
    ├── 0b66b79af02a5b6cb48ddcd03810c258fe50ec70.nq.gz
    ├── 0c947b17bac26a3f67e2f0d9c3301844878d1b06.nq.gz
    ├── 0c9582783e1bfb680231abc318ae132cc143d450.nq.gz
    ├── 0cc825e7255ef2abe3bc816cbb3bb5e22eed1475.nq.gz
    ├── 0d07b60ffe86db8c23104a4ccfd1a630b6612382.nq.gz
    ├── 0e019d20295c1b77382d792e36043e415e530123.nq.gz
    ├── 0e0d082c5351eb326eeed00da8ec2c0c57311b66.nq.gz
    ├── 0ea5ef6b1b05beb4b89a6610d8004fe086b947b9.nq.gz
    ├── 0f353181cb48095b2129838e36d06323557ccdd9.nq.gz
    ├── 0f8d07cc5be31d8d034e66a2af2c6e09946d2168.nq.gz
    ├── 102570efe44604e98294d1f7af9ef9057cacc11c.nq.gz
    ├── 10d679eb7a4c7664885f30c0f4486ba72a034788.nq.gz
    ├── 11433bbe1c766fd0fa4f05de9443b75351d1864f.nq.gz
    ├── 12064982860939bfdf5a548d0eea34a91af3fa38.nq.gz
    ├── 124e62f1d7c257a0c651724b54ed7a91bbbb449f.nq.gz
    ├── 1294607686bf67f4b01ae4a78d532cb6f2b4d3a7.nq.gz
    ├── 12bfcbffa504868947697d0da46053b185e378c9.nq.gz
    ├── 133695c603bfb4caa5b5b150b1d1b48bf0008feb.nq.gz
    ├── 13591240cd44a18b7ba0e643e602cbcdbb5bd234.nq.gz
    ├── 136c05e0d0290e2dc7eb89bceaa27b5f011e780a.nq.gz
    ├── 13ee7e985a747ffddedbad8774325ba94856ec50.nq.gz
    ├── 145fa084d8c80b0318aff827c1120d41d8da6b03.nq.gz
    ├── 14af115841b8e93cca8d984fe7d87bec6e341bfd.nq.gz
    ├── 14b56fd2e1a9472db212990dcfa3dfea858a467d.nq.gz
    ├── 14d1958ff94e9085640abd0ab2824f8c0061b93a.nq.gz
    ├── 15297c5dda48f68dbbd007a08f860b9632b7cc03.nq.gz
    ├── 157f315056e892956b4b0eb681faad40a14bd18f.nq.gz
    ├── 1685c9a09402a72e032be3b0c66da88462cccd6e.nq.gz
    ├── 174e74c89a573a3185b527b0279c7b6748f633a0.nq.gz
    ├── 179c39dddfd2c48ac3c7482f8a3be8043692953d.nq.gz
    ├── 17a35a35813be952f2df4a3db5a19e459c5b3a1d.nq.gz
    ├── 182b4e48fe5489ad5e27a47f2b1c0faf932a1fba.nq.gz
    ├── 18b4cf2cb4846d13a225622720af46da63e05ee4.nq.gz
    ├── 190ba4c8e94c9c9e01be4cbfc9a22269ea7b8ef1.nq.gz
    ├── 193ba3c8849fcd9a3cb1733d7d4352b06630871d.nq.gz
    ├── 1b86cd85c61037a28f72382facbd985662770755.nq.gz
    ├── 1cb7f3c38956a25d737d822acbcbb9009d27357b.nq.gz
    ├── 1d2f584da79dfe0773f2f57bf70cf69de29db6a5.nq.gz
    ├── 1d8de730d1454667738c591127e2883a3e8a3a34.nq.gz
    ├── 1d9bbe21375933400c07c4c3abd39831001b91c6.nq.gz
    ├── 1da33d82fe676ee61bae883fc3ee0798995f11b6.nq.gz
    ├── 1dc64bab8c2ce9619657a6eef0a4121f1b7f8766.nq.gz
    ├── 1dcbc1c69c5da27ae9718544c33530e6a828a64d.nq.gz
    ├── 1dda65457f6f4c4949fdff31480e44a5badcea45.nq.gz
    ├── 1de785f5acb46c991e4a20ea05149559c33e4483.nq.gz
    ├── 1e5e90a6c74cb9d9879391b59493085dff6ef45a.nq.gz
    ├── 1e961bf58e124541fbfa747ea1ec5342683238b9.nq.gz
    ├── 1faeed12cc264b3829b9af5ec9a916be93009844.nq.gz
    ├── 1fc6a371be4eac30e4809fcb50d58fb8bb2d2416.nq.gz
    ├── 2024857b9f7d2cc6e1171540f22daf10e63f2e2e.nq.gz
    ├── 204ac9b8f324a1bbe90ef74ea4bdce8ce8cbc762.nq.gz
    ├── 20548b9269e3930dc366e0ade737c4ae535b3ec2.nq.gz
    ├── 23ba96a75f7cc0debcd1d4f8554df5c76f57c4d1.nq.gz
    ├── 23d65c7ef4514be9029e7c1d73b885867d81c383.nq.gz
    ├── 23ee9b7971bf1010e674c3465e26e22574ca1389.nq.gz
    ├── 24150bdb065cb9e3cf50f8932761b6c3044e9994.nq.gz
    ├── 24741ef7ff5040b4b07526d06398f391f238c4a0.nq.gz
    ├── 25233941199a0057c2015086d761ed09e4046fe5.nq.gz
    ├── 2594f4c0db670f948316df128f8154fb287418e4.nq.gz
    ├── 267c09c872fb3c2408115ad1d3cfa714a77b8507.nq.gz
    ├── 269083ee507de2997fcb2607cf2bf7c145ab03ea.nq.gz
    ├── 273db0684da7c643b9c97511eecb006ff20cf904.nq.gz
    ├── 277f06ac6f4368edc2b706f0e839d55358845231.nq.gz
    ├── 279d316938ded7f065670432a8b6f215eccbc5cf.nq.gz
    ├── 27af770b3b9787fd6c81359f6c42f9bc627f9543.nq.gz
    ├── 28368e0d315544733d27be0f11190152e3ce0410.nq.gz
    ├── 28d00650d3b7157642e3d217d87b797247c5d447.nq.gz
    ├── 28e84af91be033201990feadd3c47fff131a6e1b.nq.gz
    ├── 29296f601a1b148f3e3f8dbe66ac84efcaaae01e.nq.gz
    ├── 29c581415ba1bce5c5a89c2d685dceb969774d21.nq.gz
    ├── 29f30b03ae30fa4d54e93252be63daf9aada8f70.nq.gz
    ├── 2a176c0ad0e564e572c5bc1b6e4c5c41135abf18.nq.gz
    ├── 2a43874bfaa372f8a7c67db8687219715a40b488.nq.gz
    ├── 2a75e9f2d1dc4cfca29423b8e26d49629d1bcf00.nq.gz
    ├── 2af094f081e8408ae3283e9434c5350049162fd0.nq.gz
    ├── 2b91620007487b3195ee88ef0a036a18bbc10682.nq.gz
    ├── 2be4bca533ab7ac0b18e27f5aa4a4f0e99deaf8b.nq.gz
    ├── 2cae49b6e5c0398f4c30ee18cac720e036262091.nq.gz
    ├── 2e374361487261f691bd9391c72dcb60de47245c.nq.gz
    ├── 2f0d591a43b10aac1ff597ca88ce0dcfdc249ea0.nq.gz
    ├── 2fb23cffc75981881e23817ed9495e215669f90f.nq.gz
    ├── 2fff51c0d1ee03f8bd5fcb40fd8f7ab0af213f0e.nq.gz
    ├── 3085400e0d32af50766a822a3de81648e6797f26.nq.gz
    ├── 31428bb2ef8ba90b30c15fe57c204fdb89fa741e.nq.gz
    ├── 33250e86ae7a2b509525f779c41b4051bac24619.nq.gz
    ├── 3381b2fc2997fac7e74f40531520670fdf8ec8b0.nq.gz
    ├── 339c3f517205a9e6c4a3467b7e1efabf0253392d.nq.gz
    ├── 33bfa8e0612681aea2168888659f2213e9d8162b.nq.gz
    ├── 350474e440ce5251db626bbcfb42a48afd9c5a1b.nq.gz
    ├── 350d8262c2c9f5fd85240c4da8fa2943f785479c.nq.gz
    ├── 3527bfd6768875d5f62f12fc40eb0c5b19e386b1.nq.gz
    ├── 354c029571fcb4e5fa03cd3ea080742be40739b7.nq.gz
    ├── 35632d5ddacde5f047b33f07c5ff6e66cf770a2e.nq.gz
    ├── 356b8baede481e8825c9dba10365f142114996a1.nq.gz
    ├── 36338ace40a7059fe5a55e89b92505539fca906c.nq.gz
    ├── 3694e52c9999c1096b03c2a6ee7e3df719d793b7.nq.gz
    ├── 36e3130f40fb69f70b06b3c1da16f10625288b3d.nq.gz
    ├── 36eb3e819cd27a0856016425831e09dccabfe0ae.nq.gz
    ├── 37a97fe275a3cc1d8132b3e98a748865aa6701c7.nq.gz
    ├── 37fa8f24740c2fdbb731fa46d1b66cdfd3efacc0.nq.gz
    ├── 38049d13f373a59a3bc4835aed5223b7e5543d72.nq.gz
    ├── 3842491c086191c4591a2ad6c73b2e6f7c6ddf0b.nq.gz
    ├── 385ebdfe1fd0ad06b35fdfdf00585b22568f85a4.nq.gz
    ├── 38a4c33b75ee79c3c6e0387a5ac754861edb67de.nq.gz
    ├── 390ceee3e5e53c34fa23e627adc6d422a87a2655.nq.gz
    ├── 393ad6cfbdbd079ff2bd3d600df5a1bbb7ff3fc2.nq.gz
    ├── 39c5657892861f1fea70877905e35916e7b67517.nq.gz
    ├── 3a22639966d95427cc549e13eeb28d3e6a9d2d3a.nq.gz
    ├── 3ae853dd884ff11b9208a5b27fe0bc0cf28465e6.nq.gz
    ├── 3b4e620a49eea963f4dfeee2ee11f1a8b5417eb3.nq.gz
    ├── 3bba6a061ca420b7b1254ece5a701bb4b7685149.nq.gz
    ├── 3ccdbf34218dfb3d6b94c683043a0126eb643856.nq.gz
    ├── 3d19a7c3a72b94aefc30a300199bb36befa97d1a.nq.gz
    ├── 3d7212002346f14a2d63bac5a98d45f68f7bd30d.nq.gz
    ├── 3dcaaaafc25f4b412f599b9222e0581db0383412.nq.gz
    ├── 3df42fc4dda5aeb9916958ab18339921e354f2e7.nq.gz
    ├── 3ee71ddf1db84789498ce4b66f369ebc7419a90c.nq.gz
    ├── 3f0cfef7e015016d70ac738ac8dc4035e941dfb4.nq.gz
    ├── 406d91556a9915826c7e450ed72dfbc6d476c7f7.nq.gz
    ├── 41d3296a96bf2a767bdf81156ef07cd736ddd502.nq.gz
    ├── 4257634b76e59c2f8c50dc6aa42f3e517f626627.nq.gz
    ├── 43252adb3c090083b662eb5e921355b9e515b673.nq.gz
    ├── 43456856f95d6b3fac77d288d6f5a32b7ef5b31f.nq.gz
    ├── 43d56355ef9b392a065a46d9ed97027ef53ba22e.nq.gz
    ├── 43ecff09bc2d742aaac48478f58cd8488e590d67.nq.gz
    ├── 44d762577f52ee576da1c877ab46669da3180717.nq.gz
    ├── 451e532f7703518dcf1feaf3417d89832ed7630b.nq.gz
    ├── 45aae68c93a75b480a72d831977dab6cde7aeef3.nq.gz
    ├── 45c97cc8abdd5d292fb8582bc410cdc0dd09b353.nq.gz
    ├── 47281307edf6bed847e62d34da40136dd187c427.nq.gz
    ├── 488689b7e603cf74121980d54092858947abc784.nq.gz
    ├── 49a7bfb296e14bb503d762ada5e2c6cc5164687e.nq.gz
    ├── 4ac9e84b7f10f75ab9636bf93aa9aa659aadaf21.nq.gz
    ├── 4aca1682c3ece41db77fff70dff661a271cd4aef.nq.gz
    ├── 4b396a8bbf390652ceb7d579b716cd4045f0e5a2.nq.gz
    ├── 4bba6eaf20f9fcf7a6c1ec9b0628113afdd18722.nq.gz
    ├── 4d5c81aa41b7d9279acb6ffe64b532bcb6ceee5d.nq.gz
    ├── 4d75bb7410aa1f6a234f0716dfde947e9357cc44.nq.gz
    ├── 4d9af23655a34d6afd80306b4d0537d30593e17c.nq.gz
    ├── 4e3868b2ee95d432b2545b68dc1537df74e157f5.nq.gz
    ├── 4e3a74030f44fcd9fda106591fcdfeffe03ecbac.nq.gz
    ├── 4e7279533b16ae2befd087fcdc1eb90709cdc1a7.nq.gz
    ├── 4e84a286dbb15322027fc6ff0cd06e4fcaac5778.nq.gz
    ├── 4ecfe4f06885dfa144a4b34348e0225d4f6995f0.nq.gz
    ├── 4ef4b2067d02bc467864b47795b10b7b8672c60e.nq.gz
    ├── 4f1adfdf0f159b3b1feea9d111ffb28e844871df.nq.gz
    ├── 4f3cb2b3d3cb74013937c1dbf29491c2d7434934.nq.gz
    ├── 5093e8582bcbda8f6f74a580768e5b40c24abc42.nq.gz
    ├── 522a8c9c76c397f38421fb1ab95c319cbfc86ab5.nq.gz
    ├── 52e6f43ce436366635c5ae4a209245381c843674.nq.gz
    ├── 549912c27272681c466a5d32996ac5219c87a460.nq.gz
    ├── 554131c574ce690db0342260509540cc232aacf8.nq.gz
    ├── 5572f406e2671d17961fe87abb8f85da79c66e38.nq.gz
    ├── 56a87e96ae7273335f2e5390cf2c56b34bcf6d7f.nq.gz
    ├── 57256d34abb32d8991862de2791a60048a686209.nq.gz
    ├── 57d02b76e18019a777e8d5d8f99cafec1f462537.nq.gz
    ├── 57da56d8140724026cd96041b23612bcb7e6c323.nq.gz
    ├── 581e5d55c2d0c70880b13ee1ee18094f0e41505b.nq.gz
    ├── 58399a5f539e6e4ff959de6b4b8f0f89f9b91d3a.nq.gz
    ├── 591100adab8cec099e0cbf96c5001e49748e6a24.nq.gz
    ├── 593d87d5011fb2b1596896d0fc9c830756ad8d1d.nq.gz
    ├── 599949b221c7a4c423df4eefdafd831c29272af4.nq.gz
    ├── 5a7837e60a394f6ce28140a5c3cf10ffef3fed32.nq.gz
    ├── 5a9bcd685ce6e72b577b98aab5716a27dc5e28bb.nq.gz
    ├── 5b7706ed9b458aae15d29797ee643937ce21e4bd.nq.gz
    ├── 5cb38c3cb7c268f38f89f997fd6745db2e9b2a3e.nq.gz
    ├── 5cc2caf5865311b9d72ab49eb98c5d80a153ef62.nq.gz
    ├── 5d56f502274f96310989c4a3b61710a51feb41f9.nq.gz
    ├── 5d705f397218b48f5093e020252d6b50adc2d568.nq.gz
    ├── 5e1cf107174b5c87db2f0da158eff630b5b25e0d.nq.gz
    ├── 5eb82e1a60fdeddd9a93f819650c263984c095ab.nq.gz
    ├── 5eea2f3729e42cbbdcba0a22c750396edec155f9.nq.gz
    ├── 5f0ffabae809f3547fad0062858c14adcee5b093.nq.gz
    ├── 5f526d4dc1ceaebd79067b9a2bc328288b80331c.nq.gz
    ├── 5ffb7bf8d4f028941c8f08d8193e670c6a6d974b.nq.gz
    ├── 6091dc7f13f24f52bfed2efc8dcd10b9ee281878.nq.gz
    ├── 60a606aa2894a407ae54517a9d8b66ed06eccbd9.nq.gz
    └── 60d6d41c79d6de85f405c403fd9480a8c127d22e.nq.gz

7 directories, 200 files
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

[ansible-collections/amazon.aws](https://github.com/ansible-collections/amazon.aws)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
