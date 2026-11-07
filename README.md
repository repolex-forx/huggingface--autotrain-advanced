# Repolex Knowledge Graph of huggingface/autotrain-advanced

RDF knowledge graph data for [huggingface/autotrain-advanced](https://github.com/huggingface/autotrain-advanced), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/autotrain-advanced
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 552dfe8c245067113ada4b5f918fb9af95d57dc4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 552dfe8c245067113ada4b5f918fb9af95d57dc4
│           └── chunk-001.nq.gz
└── blob
    ├── 00266eeeda6f88364bbb42a33d6f30db338cf339.nq.gz
    ├── 01aac4e30c12ed5fe6b6534b09e790ac55fc9e61.nq.gz
    ├── 02b80c7e1fdd1e09b445b058195a9722b3fbb978.nq.gz
    ├── 02cbc2b4cefdd07c8d1593a48d2b518757320443.nq.gz
    ├── 048a25c959ad6c3545a9daccacd9306e9b1dd567.nq.gz
    ├── 0530534ffacc63a76323bcbc0d4f171ae51e750a.nq.gz
    ├── 05c1fed9425237fc4cc7e9503a977e75b8c4a4cf.nq.gz
    ├── 06832309465ac7496c2d9a0bdbad289f670709e8.nq.gz
    ├── 08ba66ac00dfe403d9ac7ce2592dca1e23458ed3.nq.gz
    ├── 08ff97b04e7d5463ac84120c1bbe43a3b3aaaaa1.nq.gz
    ├── 092d0b2d013a57cf2f9ffaf9461ce1457aba14ee.nq.gz
    ├── 097ea7ac62e2720b47cad89b6128ebe38518d6de.nq.gz
    ├── 0a7aaef0d556296c3364c8a9f3567bd9ce37cd84.nq.gz
    ├── 0b251c08405a222fa04372106d8acdefca3ef76a.nq.gz
    ├── 0c2a991818d8ac2edddaf90eff7c790f76ab979f.nq.gz
    ├── 0d448c634d4e1bb6696399926eb2290db7d72140.nq.gz
    ├── 0d9ccfaaccc72e28da34bd4bccc8aaf99212ab1b.nq.gz
    ├── 0e46d80169849e1255fb68d873cdb651cb20e0f9.nq.gz
    ├── 0e7ea7305d6ce6014396830dc175a5eb79b875d8.nq.gz
    ├── 10d7e6c1afdbaf089c49b3e03b635bb82b9afa2c.nq.gz
    ├── 10d8c5f378537d386f03ae30a046491fa494bf78.nq.gz
    ├── 112a468982ec3a16168df9ef777568b44c08189a.nq.gz
    ├── 11e3eedf9849e1fc1b0573cf8684d4fb86d05c26.nq.gz
    ├── 11e7d87c13306945599d90c82ab222a61e5f3341.nq.gz
    ├── 1290631432784e0b059c9deaa79e360b682b5148.nq.gz
    ├── 15186873b06bce993bf80658c4c8ff035425b873.nq.gz
    ├── 15f5cb243815ffdbcdcd32d8bd618c8ce25f957b.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 162997ef92fe880d62b9401593786189bbad948d.nq.gz
    ├── 16ba8ad69f7d25f758c5d2912d8277f0439737f5.nq.gz
    ├── 170a7e7afeb12be3968dd1188794f4f784b102a2.nq.gz
    ├── 19cca756017bd622b2c222a6995280e9d2cbd925.nq.gz
    ├── 1a65b9007a93ddd86b5290d2cce75665717d6872.nq.gz
    ├── 1cf4221f034821ba05d55de9be8e0dbb36dcce62.nq.gz
    ├── 1d1f65811325bea94b2af799d559e33324bec7a6.nq.gz
    ├── 1db188015ffdacf3c9bc032dbeb6a7b270bd8331.nq.gz
    ├── 1f5edf1fd904837ea45e46cd617df36db04740f3.nq.gz
    ├── 215a5cbf6ef219d07246d286b5ec48f5aca9be9f.nq.gz
    ├── 2193ba048f5b176789eb763d93679cc831cdff69.nq.gz
    ├── 22926aae599d6d1191d40997d20847e0f56bc95d.nq.gz
    ├── 23182c26c5461d81da9c0678c82c2d240edea9a0.nq.gz
    ├── 24655ccfad7dfd8cb50488a24e59ff1823e49eff.nq.gz
    ├── 25926b7b493dc69ce6ced456e963c70d64a02cd8.nq.gz
    ├── 27e413a3fca19dbc389e37b7dac29ab0b7c656d1.nq.gz
    ├── 29d6bd773d3378026e07714633790aa43561e3f3.nq.gz
    ├── 29e07899e40d9b5eef1f0ca420e3c26c2e88138e.nq.gz
    ├── 2b3832a5403cb2231899411577984f3daed40b2e.nq.gz
    ├── 2d0965a0ded142e0cb741f44942840ae9ee1cc36.nq.gz
    ├── 2dc4c07b7820967779d884f4255e6e7b44a75540.nq.gz
    ├── 306f9dd7698b42ce76fe4ce4fb77d202b5754ee1.nq.gz
    ├── 310b01b31d136a8055fdc4e1d0b811e8ca00d2da.nq.gz
    ├── 32f41546eb1c17dc607c95d90143a5069d6b42ed.nq.gz
    ├── 3425d3e56a1a4a87e7c9597c4db5ef67d5ae0936.nq.gz
    ├── 35cb49d5e9f3b3de20a240537add90262683c715.nq.gz
    ├── 37313d498efa998d65d469b3dd6ea1ad5bf236ab.nq.gz
    ├── 377cf227a7de409409516e1eebaef891d7b137e2.nq.gz
    ├── 390e70927f320d5dec13dbdf85849e9435492c3c.nq.gz
    ├── 3d1330978955c52355d1b129566fb1b78cbe4835.nq.gz
    ├── 3fd63fbc4a226ff493fbd42be507675c2403bd41.nq.gz
    ├── 3fe19b8685680539a113771df0a7691228e5f32b.nq.gz
    ├── 42c3646949eabc791be4dc9f8c3201be4c77a634.nq.gz
    ├── 42ca7203bcd78681e353efd3b0aa57faa553d89d.nq.gz
    ├── 4397aad0795121e66989a07897b527f83889253a.nq.gz
    ├── 43c01a13e170604be56e3e951f280b7ac8fbdeef.nq.gz
    ├── 442398141a319e4d21535891b20c751074e240b8.nq.gz
    ├── 4474f8780e897d32cd17db5c27761bc98447c4ab.nq.gz
    ├── 46cedd0ab57396ad7f7e9e95c63e75d8a4b9de57.nq.gz
    ├── 484888d2fd96b80a1e6ec2cc8593ba07d0810793.nq.gz
    ├── 498816197c7e40358de3591725c21ed37973e8cb.nq.gz
    ├── 4b7b4d9c22d94dce3f47180d2a4d63b01183346a.nq.gz
    ├── 4b9e601f1e1397212bcc70298dad822777bf3a7d.nq.gz
    ├── 4ba295a963bbe97f36f622021d3795fdc0ba36a0.nq.gz
    ├── 4c9b4ef17f53a67431d7fd4d226c9eecaf16143b.nq.gz
    ├── 50350948edcde50580ce391b4b4bdf14e9f7d126.nq.gz
    ├── 503bfe2ae0047efbb4bb0984428255dbc62323fd.nq.gz
    ├── 52f8725e0af24614939c83ae2c05f86af11ad7c9.nq.gz
    ├── 55f6d6a6ffc1509429bece76615a2f8b37bb1198.nq.gz
    ├── 57cc626d44d249122c245ef3a623ca67f1f0877f.nq.gz
    ├── 591771a2685e14f85ac1ffa41595de10b4c9bc97.nq.gz
    ├── 5ab8f8f5694477e94844fc51f7ba8fed04889963.nq.gz
    ├── 5b2cf67af5a072856f4677e1546dba476606e952.nq.gz
    ├── 5ca6df4131a1459136c85c78e4073376b1a6ced4.nq.gz
    ├── 5d000889a83ef39395be497a02aa0be2f391eeb3.nq.gz
    ├── 5da820985f6aed9dc080fc7f7d99c09972798588.nq.gz
    ├── 5df712162b45eaba852843caa000b3d99a03f471.nq.gz
    ├── 5e41e25ea07eb2ebe1deecc75b25d343d8e87e56.nq.gz
    ├── 5f07f2e4e9665a2099bab2975203e99f9819f7c0.nq.gz
    ├── 5f7a93e28da55c07630a078924f0d00e832774f9.nq.gz
    ├── 601e5df7ecc03c82af80cc42d09e274f619e0b3d.nq.gz
    ├── 6062fbb345f55b59a014f13cacfdee60641ca11a.nq.gz
    ├── 61e1f8a68692d1994e805a823f519d51b5dcbd3b.nq.gz
    ├── 640f4154395dd045c2b62a38698c053dffd7aeaf.nq.gz
    ├── 64430f7a2a4a2c8aa8082d6095f63dc516e3cea3.nq.gz
    ├── 64f340dd870bc6a4ee3176e6c5ff5a5e9c84ff77.nq.gz
    ├── 66d94761ebcae7f20271995681c1174f1fcbf5d3.nq.gz
    ├── 68447d6929058f097e2cac746ba4c47b6b37d3e5.nq.gz
    ├── 6b67a6a4b273d7ecdb1e03e18574d4191848284f.nq.gz
    ├── 6b8b2421ab6b41d4ed571c7dbd79f984633e207c.nq.gz
    ├── 6d8f7e663949b7135ee3e3e9095be580844df67a.nq.gz
    ├── 6d9315f60ae94d8206cf3f62f9b0aac8f34b6f80.nq.gz
    ├── 6ec5901fe9df5fc0300189d34ea855e2fec04945.nq.gz
    ├── 6edfd5d6bc2da44699ad1417a1962b4ca905af00.nq.gz
    ├── 6ee487a724783f296e4be4d9945c4ab2d5894f94.nq.gz
    ├── 6f60f556e64b53b330d528c3059feb34475237e2.nq.gz
    ├── 713a5b2c590c1f5822d50d70669144bcfe8950f7.nq.gz
    ├── 76c56d8cb8eb05eeaf39eca0613e715933b29757.nq.gz
    ├── 7734b70e9c322385ef25ead50bd07dc4bdc6f17a.nq.gz
    ├── 7830d0fa03e9f718ccd7bd692f9aebb58248a3dd.nq.gz
    ├── 78aa04b781a31f1baf90cd4303f63f27717a009d.nq.gz
    ├── 793327353723e5f96b5f1fc27dcff324c9a94089.nq.gz
    ├── 79a1a6f4af41454681c1471790f53c230eeffc32.nq.gz
    ├── 7a4a3ea2424c09fbe48d455aed1eaa94d9124835.nq.gz
    ├── 7ad22295ed9f6c8d43382c62561f555ed4f4f556.nq.gz
    ├── 7af6f11dfb894d8a4f5590ee54d5e5acfb3a9de1.nq.gz
    ├── 7b814a426840520f5e99170c352ecd14dea028e5.nq.gz
    ├── 8095573be75823b9d218e12f0a7797f0504bf4c2.nq.gz
    ├── 8165b4faf81fc9302dc76d2055195c85027ff48e.nq.gz
    ├── 82f44133c3309f3278e27cafcef518c02615c085.nq.gz
    ├── 83585d9a4beea17e4649536166da92a6a3009385.nq.gz
    ├── 84078f01e43a19c0841b22a2ad6ca26380faace9.nq.gz
    ├── 84a141a33d88d1789be7562202e69781043fe542.nq.gz
    ├── 8563ab15b838fc930142080c86354003f847e49c.nq.gz
    ├── 86d5933f02ef8605db868a19e56e762bbdf6d414.nq.gz
    ├── 8b1b72ee8e5f878c7ed924dd91bca64972bccf38.nq.gz
    ├── 8c1b9c3a80236514d6a9e5f533308b70bf5cf987.nq.gz
    ├── 8d058a40c8891d0a2c154ce9dc274ffdbf5103e9.nq.gz
    ├── 8d29c1c74a51e4e3ace4291b86d4db11b002a8b2.nq.gz
    ├── 8d826a4bec89f907ae999b80bd83043eac0c4780.nq.gz
    ├── 8e0e53313eff00e2c9665c45cc298abb534664c0.nq.gz
    ├── 900b22c986e62021efb759818ba3deb9f2cb30da.nq.gz
    ├── 902500050005f9edbe3a8907ffbfaa20866a8bbb.nq.gz
    ├── 907c8411234f648c48f33c86079bd7971460366d.nq.gz
    ├── 942311cffcbeaf7bb091bf1d882c759a43df217d.nq.gz
    ├── 956c9bee340ccb07921eee7128fcb5a6b488a52c.nq.gz
    ├── 959c3ed50edad25e0a52c50021b55f78601cae1c.nq.gz
    ├── 9638342aea68a7c26f6efed566cc57d0689436ca.nq.gz
    ├── 970aa1247a2b225c1ce0c20e940bde4fac94bcf9.nq.gz
    ├── 97144ebc823f20f6bd2a4910f531b994ab39d988.nq.gz
    ├── 9793489cb357b81c1f2ebc4dee3da5878b0be355.nq.gz
    ├── 97ae844057ac135158461730c4524c833c8e594b.nq.gz
    ├── 97d892727a3a1baa7abe679dff972d3c1dc8f996.nq.gz
    ├── 9834b4d9598ae9eab17bb7750171bf8c2ed892d9.nq.gz
    ├── 99b92340ae2a135ff63c5c5a6476efda7fad3787.nq.gz
    ├── 99bb9801841e6d221dcde388319c81735aa4fc17.nq.gz
    ├── 99e6f198b8db3a863fea4360be92edd425ae1a8a.nq.gz
    ├── 9c920a1b640000153eb463dfb4d5f01dd72332c8.nq.gz
    ├── 9faadf205bcd50e8ca6da1a8faf06a6cbc6d7750.nq.gz
    ├── a19976c510604f0de71dd18b3eebc8d694f73752.nq.gz
    ├── a49c5ec070d7e9d13bf571a612145e89bdb46daa.nq.gz
    ├── a4b064e16bebd5e092ab641d46f0c30c91be39a8.nq.gz
    ├── a4db2e06dec91e5de6c0cb3fd88c0088ec8ecff9.nq.gz
    ├── a6858dee2f63637a9fa8d92ea95e0f070d572ab1.nq.gz
    ├── a6e02ed73d28a8cdfb30b8b16a6918717668e413.nq.gz
    ├── a6f4addbc53343dee8c5e36892fe35bd8cf1f061.nq.gz
    ├── a701c168998f13c5ec7715ce7f4080312e89b27a.nq.gz
    ├── a81267b807a1eea558cdd539eda7c47607e0f3a4.nq.gz
    ├── aa2b80ede6f4a1cd3d021b08e5a8f99e9aae66be.nq.gz
    ├── abd54854ed1f289ed6fb183eb3d4009304af9b21.nq.gz
    ├── ac2877320dfd4c001047456f01f0a773fe3892b9.nq.gz
    ├── ac5f75f1086b5ca7d4d114a536893e81405c0ee8.nq.gz
    ├── ad5b461c3046e6ba174aebe987f0a44abb3140ca.nq.gz
    ├── add2f0c07d987f2833a600b92761e7aa347e8299.nq.gz
    ├── aea55f840ad6bf4103359faabc7afb6b947980b9.nq.gz
    ├── b03758adad9e0faf286ba81d5c3c4613f80d08b3.nq.gz
    ├── b0b58f50251c4ab39477fa5a11349f865fbb7366.nq.gz
    ├── b1075888a57d9456e3a305051014c96d5cf617fd.nq.gz
    ├── b14303e741dcc51a6eb5877c39c8da3dfd45ec13.nq.gz
    ├── b2e36b09b760ddbae07583bf24d03a4a0f83ded5.nq.gz
    ├── b5f66a7db28fc728f6cb9aab26409a59f92db561.nq.gz
    ├── ba7f68af01f3ccf42fa0ff1fffa636dc767379a5.nq.gz
    ├── bcb034a70fc7dafa67c5930d4f5621b0949827c7.nq.gz
    ├── bd5d5e64642d103949d2a84f00df1912bbc4a973.nq.gz
    ├── bd6a7b46054b5b2f15fd3cc3513138989caf10b7.nq.gz
    ├── bdd2d764736106ce4a9aee22a5a596e81054ea07.nq.gz
    ├── bdf0ea196912c6b85f7ad44a86dc4c528533b2b8.nq.gz
    ├── bee20ce5f3ade670785639bc294c2a44dc5380ae.nq.gz
    ├── c03266e35180c7bce556ebdd016176e55c34aafa.nq.gz
    ├── c213972066725ed05292f6828859084acdd00387.nq.gz
    ├── c2d3236cb783b332875e2a6f9701ed23abafcce5.nq.gz
    ├── c3a02d2e9635fde439a1fd2b8efe9b713bdb76a1.nq.gz
    ├── c4492ff020c39b1da993d716ccb5423535d6de8f.nq.gz
    ├── c47b1eb7e85bfc03cc0e83be8182032fe4da86b5.nq.gz
    ├── c49148174ece1701ddb2111aa7310c190bf09b68.nq.gz
    ├── c7021cfc6259c983c5df5ffd9709f96231655f2e.nq.gz
    ├── c8fe1369f17664b9b6f9409758ba7d4b11674239.nq.gz
    ├── c9429f6242513f6c4f6d80d6c018d0d7b94fc00c.nq.gz
    ├── ca0e5302b22f7d41273f009bb50c43cf911b51f3.nq.gz
    ├── cb6041d49e6a209019e94788b9bfed39f2b42d59.nq.gz
    ├── cbc89e04a95f5d54758239f4a1c43c9987fe167a.nq.gz
    ├── ce19340c607716ccc67b5f999f66479fc37d2f0b.nq.gz
    ├── d20b16e5878bc26d740deafc0236ddb0f835df4e.nq.gz
    ├── d3deea7d8fb63a6f12da9b4d19faac3f7c979cb6.nq.gz
    ├── d517262fc02ca47477dcccc48a9daae98c0d893f.nq.gz
    ├── d52733d21b016fd367b5dfa98e38c384d5de87d8.nq.gz
    ├── d5d8a1c434e46ba23297979799efe4228f518f83.nq.gz
    ├── d716498d92cad5780a92e884b3ac5b804a1ef384.nq.gz
    ├── d74a6215d2c455367bb08931fb35806bac386d77.nq.gz
    └── d76086e56f33b0fd34f83195ad0dd9c6148a4552.nq.gz

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

[huggingface/autotrain-advanced](https://github.com/huggingface/autotrain-advanced)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
