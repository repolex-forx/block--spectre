# Repolex Knowledge Graph of block/spectre

RDF knowledge graph data for [block/spectre](https://github.com/block/spectre), parsed by [repolex](https://repolex.ai).

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
rlex download block/spectre
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0b90c8569e4eab373d797501edece8e56a6885fb
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0b90c8569e4eab373d797501edece8e56a6885fb.nq.gz
│   └── repolex
│       └── 0b90c8569e4eab373d797501edece8e56a6885fb
│           └── chunk-001.nq.gz
├── blob
│   ├── 0162a9ddb5e71e6a3ee3b3ed4518640d5d95cc28.nq.gz
│   ├── 02fab7e8deb9657a0b0ac80994b0ea74ff4e2f15.nq.gz
│   ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
│   ├── 03b0d6bf68577061177fe29bba8eb4c3915d3b14.nq.gz
│   ├── 044adb1384c52bea572d2e59b790eeaef6b39f8d.nq.gz
│   ├── 05510f0a725cbe2a66fd41186358ebe514bfcddf.nq.gz
│   ├── 05d23e8d3a2b66336615b70058851db68641a989.nq.gz
│   ├── 06796f0e5c18b8842667dae9dabd4a83884c4ea3.nq.gz
│   ├── 0a293125e2cd88b69a82fd1c72f0fc43b76c3eb1.nq.gz
│   ├── 0ae74b696da0e5ccd40a986390d1e676a2628251.nq.gz
│   ├── 0ba9db25329d0b336e39ca8cde8470c5b7bc45eb.nq.gz
│   ├── 0c10228fd0e5cfaf0088b9d8f22ead7a5ccc51d0.nq.gz
│   ├── 0e59ade0130d1d7187a9dc8048c08d114c155125.nq.gz
│   ├── 0f32e67a0f94bd0c1cf1a2ea59d1bb1948b482b8.nq.gz
│   ├── 11d514b296de8625433054aae96fc3e647d3e75a.nq.gz
│   ├── 14414bbf773306707ae99a01c84209799d7ab85b.nq.gz
│   ├── 1462bdc23e3f4e0806a9e0933fa063dd76fa4931.nq.gz
│   ├── 14a6c8722ee58c39f46e74222025ed5c8e6fe2cc.nq.gz
│   ├── 15797accbfb2807381c8209ee7c19711b5093f11.nq.gz
│   ├── 159a2de7a814802abde9cefb3ba336a801641ee3.nq.gz
│   ├── 16fda7234a5d788515ebd34a0de0d802282d02e0.nq.gz
│   ├── 177cbf29509ac74868043103579f91b995f95bdd.nq.gz
│   ├── 178135c2b27855a27d4109630473696c869f5ed7.nq.gz
│   ├── 1a332a57c78a7b9ead49a759fa83e62d443932fd.nq.gz
│   ├── 1b503a29fe638ecdc74dbf0968efbe1499330717.nq.gz
│   ├── 1be918d9e52539db498d9d849b8b12758ff121c1.nq.gz
│   ├── 1c23be3ce407ee8d62a01aa53205fdff68b1dabb.nq.gz
│   ├── 1d9adb181eb7c8434adea294cf0cdf85f90865d4.nq.gz
│   ├── 1f6753f50d15ae0b880be50ad4b11de33dc9ea05.nq.gz
│   ├── 1f6bc6cd72deeb44d07303f8708eb4d92c463fe0.nq.gz
│   ├── 218682b8edc038ef5eb8f628319df5762fe7d123.nq.gz
│   ├── 22f28b651c996e90ff940af6b2f5d1cc1faffdb4.nq.gz
│   ├── 24fec3c8c41683a9ea230d2072495b2876581e20.nq.gz
│   ├── 25f0bc5ed80683a81f46e6bfd1cf8ea0b56c6807.nq.gz
│   ├── 27a2b6211e014c6ef69abab3712fab2f1bf0dbe0.nq.gz
│   ├── 2c233e91a93bdfe3182a03846a59790dc2bfa3e0.nq.gz
│   ├── 2cc6d39a61bcabe886ed3f3094956100252f8839.nq.gz
│   ├── 2d93ca5339dc45da5bad89a84d0ccd9d3b9a6d4e.nq.gz
│   ├── 31559b7d115e3c105b328cce9b9dcd9774025061.nq.gz
│   ├── 34e6abff2137186852770b80d77c8574b16b2a5e.nq.gz
│   ├── 35790bdaf1e0cc346fdc12c6e84f9065a2cef5f2.nq.gz
│   ├── 376229e035aa7f058686955b4fd25ccb2ad18c7e.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 394917902e45ff0197de39228276aece9d8ae478.nq.gz
│   ├── 39f1d6318b26724261d837b8a2ac9850e4ce44fc.nq.gz
│   ├── 3b905a9acfa3239cbaf27feb2f97edf2fb84e2f6.nq.gz
│   ├── 3eed84be0a0108d97edbe30e28789c8e3b7c11c1.nq.gz
│   ├── 41ff6894cecf633bd72388777183ac62c6cf986d.nq.gz
│   ├── 42d891bb34e91441f06ae3b8541eaac8ca85fdf8.nq.gz
│   ├── 432f25e505ea8f49bdc9cdaea33793d737f850c7.nq.gz
│   ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
│   ├── 49449e3e997d071031c0087d4dd511f9fb11fcd7.nq.gz
│   ├── 49f4d9131fdb35accb04795cc1cf695f45306ffb.nq.gz
│   ├── 4e0886328c448834d3dfea381f1ef65500fee2cf.nq.gz
│   ├── 4f023fe71e13978cd8595fa6f82c8a6047f8e927.nq.gz
│   ├── 50cfd79c8b7d7b1d36678fa22ceb7b9d8fccc09a.nq.gz
│   ├── 52ba26eb9d3d78f80b922a91154b38a9cc60ddcf.nq.gz
│   ├── 55f204b02e710d5068417efccffe94e284b93161.nq.gz
│   ├── 571bcb3d19bae33f41b60dda3ef6e83091c54e4d.nq.gz
│   ├── 5954736d982a6ddfc5a8364bbc16bd45e24bd96a.nq.gz
│   ├── 59fb696dbf281baffcc629ac21c63ff6b031cb70.nq.gz
│   ├── 5b91a9e15f71cd13101233d6e4060f050d9a4050.nq.gz
│   ├── 5cbd6de9406b28c23506a0cbf44f13906d1004c0.nq.gz
│   ├── 5f6694362e95f99afcd2da2511095db66c925281.nq.gz
│   ├── 5f901b89e8fbae80f2c17c520987ff56f9be7f2f.nq.gz
│   ├── 5fe2da7f6e803f1ad4d1b7696be8b2694b3ed260.nq.gz
│   ├── 6077b17c4e552561b8c594ecef965486687c8e62.nq.gz
│   ├── 60844159afab63bd4ba8bffbd649553ae382beba.nq.gz
│   ├── 647f65494b354734a2296ad6a07981a790bc1a9b.nq.gz
│   ├── 66ef65634003ddb0297f385dad8883416e58b489.nq.gz
│   ├── 69925469d68a5e4f1fddc18ffcd305ed8bfe8de6.nq.gz
│   ├── 6b6be332beb743a47d6e3a336e2db665ebe0c7d1.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6c025bc563895062e8e9558416c1926d60ee2245.nq.gz
│   ├── 6fb2a6fe4fb94ec37fb6de96f3833f7c0457bd64.nq.gz
│   ├── 6fe9579ddafa6614ce52bab8a8e4f57597376420.nq.gz
│   ├── 71d10c7ca777128bd94f1437f6164e3c178003a0.nq.gz
│   ├── 73ce1b6127c435b6d70d1dbe4ee433eea7d19d39.nq.gz
│   ├── 76bd7794d90a8d57f6c8f292d2f14068d00ee5df.nq.gz
│   ├── 7c7c54a5ebec866459b84fd0879aee530bbbd4aa.nq.gz
│   ├── 7d320bd14b4cbc734e80650a12cdd49a5cfe05ce.nq.gz
│   ├── 7e9ef493b8cde27c1604f6e7c5f6b52d8c68be58.nq.gz
│   ├── 7eeb4f1fe28ceb205023d98b24c10401106a9550.nq.gz
│   ├── 7f7539a490ad2b988fcbaf7050792fc8c6d53909.nq.gz
│   ├── 83344e236c0e524ccbf4d8c0c168b72424a91c73.nq.gz
│   ├── 84d3bcc257aa44656126fdc15fd973719451b229.nq.gz
│   ├── 862ee3c28647e7a58801a75236855c269c1448ae.nq.gz
│   ├── 86fd48a6890c4c405a197035e279f0190e582f38.nq.gz
│   ├── 880a2399e9a37f02be396810b24c637d4d586112.nq.gz
│   ├── 8ba493ea7e87b7c291c650390e422881f5ff9870.nq.gz
│   ├── 8f629106047f63b49ac13367bf620bf3e804c4f3.nq.gz
│   ├── 9001b6b275866ab6e000189c2ca8cbd0f1d46c22.nq.gz
│   ├── 91c9ba340de884602d4d088c7a7ffda17cec9977.nq.gz
│   ├── 924f50402a6d3023cdd9080b3d0f57609e4827b4.nq.gz
│   ├── 9302fab0dedf8a1f819c53d0e19d85340c4ddfcb.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 97bac2fdc0b195ad7cc94c27757f6a083acdabd9.nq.gz
│   ├── 997e9ce8c0af6006eb4cafbd8596c91021b7140c.nq.gz
│   ├── 99efe0fc424f0c0aee08aa753cf8b1d8f593bfaf.nq.gz
│   ├── 99fb435e404819f14f81036a0d9709a44f4422b4.nq.gz
│   ├── 9c6c17ac847ecff83d6a390290b8a0e3bea444e7.nq.gz
│   ├── 9fdeda604523ac745842dfb1df669f4b4216fdfc.nq.gz
│   ├── a21328e3269a26d1448bb3203aa5e5df4b4b5287.nq.gz
│   ├── a2fd8282aeeb6ce6770af15dbc337dbe29cf3b33.nq.gz
│   ├── a4d7a9276730afe34f28f191ad36bb9f42be146e.nq.gz
│   ├── a64eb71a7c3183f391cf633b17926da766d4a92b.nq.gz
│   ├── aa9184dfed3b73292a36a2ec3b0c62f09999a501.nq.gz
│   ├── aaa9e3169081f9a25b401eed29d98b2d8963a2fd.nq.gz
│   ├── ab158298d00b992809c7395fec600876a436dc76.nq.gz
│   ├── ac028941d943a950bc46449b36e0504c0a46ce63.nq.gz
│   ├── af94645bcc906dbb01c91e87811a5a9e5302e542.nq.gz
│   ├── b01b6a7ebba6559f329e3463dee441369b1a169d.nq.gz
│   ├── b14295993b6875de2a6015cc1eafac64882a7cfb.nq.gz
│   ├── b38752c62685eae418b003b68bb013c4b85a7ff9.nq.gz
│   ├── b3e92de7d03da9893409cbe4193e0fec6f2bcbe0.nq.gz
│   ├── b421c33b36b92a734350a854417ccc9d99497edd.nq.gz
│   ├── bb19354ddf0444638fd61ada99ff97c1a2853387.nq.gz
│   ├── bceb62d11547873a30883bce93f82a553995db2c.nq.gz
│   ├── bd54f426263477c7e41a1486f30fa916ce531c75.nq.gz
│   ├── c2828cdcd8e125775809d3d3f7b0306dc4041b44.nq.gz
│   ├── c3e8a62c9c5ff8a23be171c9140c7e569e186b5a.nq.gz
│   ├── c6dce7dc4786c6104c9c9c0cc95270ae6e9c1f2a.nq.gz
│   ├── c8998c58d974e4dc7047385c7b9c03e4021253b7.nq.gz
│   ├── c9a9c26f50a66c1ceef7b57508b857da12a3ef0c.nq.gz
│   ├── ca06463cd7aefd736b727b78677409d17001c944.nq.gz
│   ├── ca70289eb495a862e2ba2e492db87b1d5d2b2107.nq.gz
│   ├── cd2ddd121e29da1e35335fe42c52189468503c1e.nq.gz
│   ├── cd2e34e6b78af1f498218a9391f91ee4bb1ad2a9.nq.gz
│   ├── cea11754261cd4d99d2803fa6e19182ebba2e08b.nq.gz
│   ├── d362eae1cde82150100484029aaf0e4d363275be.nq.gz
│   ├── d4266ef32bce5d0b5a619c9d5e6ace01dac96cfe.nq.gz
│   ├── d6169730f1fb4d6065b854b20abaca861491c42a.nq.gz
│   ├── d7cb14b4293111c75376c4349a117656ce654079.nq.gz
│   ├── da0cd10e8f3c68a73209dd9d66ccfaff9277cc51.nq.gz
│   ├── dac42a7c127eb680b4c92cc98ce38fe31bea6341.nq.gz
│   ├── ddfb36e07ffff822038d2820fddd5357e2802073.nq.gz
│   ├── de0976b527f46bb08e3585ba48c0fd4cbdea6684.nq.gz
│   ├── e0b00b5f78b298d68a870f08197472949dbb6938.nq.gz
│   ├── e4560b3fc2310c50b1e197e5efb6bf990e7b461f.nq.gz
│   ├── e65a872297275f02c5b5ac02018ba4cfd286c7b7.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── e9937a375814d94a128d30633911ffe701e9c1f6.nq.gz
│   ├── eb7d58030d207cb4d40ade15033fdf1f2a2e8643.nq.gz
│   ├── ed3b4334f0e78b9315cc31dcfce7637620d9aa95.nq.gz
│   ├── ef9f5f2b22d4c73cffb772f70ea2aedab8b0f9a8.nq.gz
│   ├── f0c56faeb470796189d300ec5f28c1a6b900ddd8.nq.gz
│   ├── f4cd47fdf316ccf1ad6ba3cf05b03dd2152a04b3.nq.gz
│   ├── f4f7fa739fe1054b877c23f449324ae910313d57.nq.gz
│   ├── f830558ab38f9e8adbecbfe8223ce193fba83c99.nq.gz
│   ├── fa678976ee734857e9d96f4d64096126735602e5.nq.gz
│   ├── fa687867eb340a8a8e782ccacb60f0c8a5e832a5.nq.gz
│   ├── fd4c29e241b42e7b06dad514cd5e0cf1ec763ba7.nq.gz
│   └── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 0b90c8569e4eab373d797501edece8e56a6885fb.nq.gz
├── filetree
│   └── 0b90c8569e4eab373d797501edece8e56a6885fb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 163 files
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

[block/spectre](https://github.com/block/spectre)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
