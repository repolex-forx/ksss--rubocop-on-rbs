# Repolex Knowledge Graph of ksss/rubocop-on-rbs

RDF knowledge graph data for [ksss/rubocop-on-rbs](https://github.com/ksss/rubocop-on-rbs), parsed by [repolex](https://repolex.ai).

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
rlex download ksss/rubocop-on-rbs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e42b63f984ff4fff923a1e856a66763a55591029
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e42b63f984ff4fff923a1e856a66763a55591029
│           └── chunk-001.nq.gz
├── blob
│   ├── 02530c7c1604637f93ffd89afc98fe86a1a3b8e2.nq.gz
│   ├── 02ccb898f790d3e592262064992a190de385f14a.nq.gz
│   ├── 0431d9b736ac2d68fec0630046c4fd424faf12f4.nq.gz
│   ├── 071dab7ff0da2299c0a9d0697d82b3749d232fc8.nq.gz
│   ├── 086d7c97b12aee0abae28e4ba746971894ed9488.nq.gz
│   ├── 0e696f7e7e0d0b06d27dc6f7ca3808aaa855bf03.nq.gz
│   ├── 0ed22fd763a81c54fbca6d98a879891125fcc66c.nq.gz
│   ├── 12701a0d6adc1e6a59eacf63c27bcb554beffa9a.nq.gz
│   ├── 128d727c1802ebc086f3a235166f0a778c34a05c.nq.gz
│   ├── 12a92bcc47850b04e802a167a7c0f827d0112774.nq.gz
│   ├── 1597095d0adfa327610f3373b8f0b6f52c3c93de.nq.gz
│   ├── 1632920095aa93722e6a60c2185a73b73a705300.nq.gz
│   ├── 185a026813dc73989c15801d9acae4d9f458635f.nq.gz
│   ├── 18a99b81331db1914a1666d3b1e92e3a0e0be6f9.nq.gz
│   ├── 1ab278c3ff25fa50a794cc7377dc4d16ce8465bb.nq.gz
│   ├── 1ae9766b4442be606967bf3952e4aa9f1b6902f7.nq.gz
│   ├── 1c2504a78d5b7fc74d9aeb57576c0b190d6f8d53.nq.gz
│   ├── 1c591ebea92908498cc0b72b8cf59f70da54f8f2.nq.gz
│   ├── 1f19813a291acacf06dd78d9d8a8618082cc6ea3.nq.gz
│   ├── 1f3d2a5ab3fdbac7193d2ffd403ee43e01f9be30.nq.gz
│   ├── 1f80cd20b4acc702708c500b9dee62b9701be6ef.nq.gz
│   ├── 20513d66b7d6ed45c2e93aaba2e4ada9f1228877.nq.gz
│   ├── 2081f48bce6612248376b4663c10e50c99e89306.nq.gz
│   ├── 2243fcf6db4f36e3a74513196f67c6b68c486c8a.nq.gz
│   ├── 23911ab9a2542707ff151135ed8972e2d79ee861.nq.gz
│   ├── 251fe410e58c04ec61484b6d8848abf5698bff82.nq.gz
│   ├── 254343c464edce6b4cb7f3a06bb300f432b12455.nq.gz
│   ├── 2650aeeebc674e5fb4d7930567f806b49d977446.nq.gz
│   ├── 2a4a51193cdd7c44ea699b8642afdd5a8741d548.nq.gz
│   ├── 2b07c62728e49a1d65a9c3e57f16edd21561a58d.nq.gz
│   ├── 2c606ab459789d62f039f90e9bd2acfa25c30cae.nq.gz
│   ├── 2e49aafbf48f3d062732b027dcc706c582c1d943.nq.gz
│   ├── 30668fc037eb718f4576e30f049a3cba1c60541e.nq.gz
│   ├── 309a23f1ac8c5c2ff8a2f1f3090952bb7d194f64.nq.gz
│   ├── 30f8fed968937c4f38a1eda83366033fc008d111.nq.gz
│   ├── 32c9688a1b68dec870c649130f203e858b910ccc.nq.gz
│   ├── 33bbb899b9bf5a888448e22adedb2bf69e051675.nq.gz
│   ├── 370b8ee39b2b7888e4f9602243b09c82ba2e9491.nq.gz
│   ├── 3a1f9cad5ec13328dd5d0dbc6454109d28a9c352.nq.gz
│   ├── 3b5d42d591b2576c4c74ca995df45c3417e334e1.nq.gz
│   ├── 3ee5efeaef77509286dcab12502d55e7de1cac88.nq.gz
│   ├── 403f5c73b374f3802cd6a9a1374dec4f4e9b75cd.nq.gz
│   ├── 480ae52dea4e86918edb3d7f59760dc529861908.nq.gz
│   ├── 498f28d9c0eef024a6b8c96b817bb98c0e573eaf.nq.gz
│   ├── 4cda3448e654c601a39a8cc5a4ed3f88578cbf56.nq.gz
│   ├── 4e8389b0b93f4d8d0cba33fa1b7bce549418eccb.nq.gz
│   ├── 4ea7cc19bf59361f7b8834ca084fab04382c1f3c.nq.gz
│   ├── 4f2cba921bdbdcd0e9f2f1e383a932c188b4bbe7.nq.gz
│   ├── 509185b240deeca571be65d0ee454f43638552fe.nq.gz
│   ├── 50d2c68587e7ca6f56339d83dad4946b61415dae.nq.gz
│   ├── 52136bfc80019f7ba2042e80b88f09d5f2934e81.nq.gz
│   ├── 53ca9ed649b40f09c4e256cf7a82e3d1d1814d79.nq.gz
│   ├── 5529bb97419b2945ffb93b34356903f922069b35.nq.gz
│   ├── 562b0937812764fcc0cdee19976bdd0f841ef241.nq.gz
│   ├── 56e2cc98ef353230b347c2a8c787d35a3f3a5629.nq.gz
│   ├── 56f98330846d791e263d143073ec178d5354d65b.nq.gz
│   ├── 5a8c461f37c52848b73adf5e731a81ec94534f7c.nq.gz
│   ├── 5ae1655205d70b7a4c28f1df08340d7d8ebc7e2d.nq.gz
│   ├── 5c57aef1f3c6a9edf5902705c6abef6693ef1101.nq.gz
│   ├── 5f6235110cdff03e48d443f10ba5e651eca276a6.nq.gz
│   ├── 6244b7bdd7af5b15b23399bb5e0635bde37a5f27.nq.gz
│   ├── 6383b3b08a8b95730eb9a887f6e6b59385101f0b.nq.gz
│   ├── 667c15789fb7b96a25d3c093e7b0367c41d73384.nq.gz
│   ├── 6726cf9543143ba314ff61a6da04596bcabc73ab.nq.gz
│   ├── 69ec4c754faab8ad8dad425d50354593ae0a4578.nq.gz
│   ├── 6a30e4ca8add7de701d965253f3f89f593d4231d.nq.gz
│   ├── 6aa196e3a92cfc72b558888a85aa257539af5838.nq.gz
│   ├── 6ae8a4fec1a0949d8f317f37cd44e74973998080.nq.gz
│   ├── 7006d5b045e10aff976332fd0065f43575863baa.nq.gz
│   ├── 704429cfb1e21cf892f52533b18e8d86f1d2482b.nq.gz
│   ├── 7076fd8eed1ac56c1027cd4c2e60df7c496fe943.nq.gz
│   ├── 71139b54aafc11b254ba82a14cbf2a5aec26d651.nq.gz
│   ├── 71ba829e77506b99d9206955955962113a53ce19.nq.gz
│   ├── 721c81eeb09a35556db16b33a1003c86cb115a36.nq.gz
│   ├── 73cf32b0ddcaf7cf79acc5b81cf26b3c863b3de6.nq.gz
│   ├── 744cf1472e859169bbbbae4d275d7347665f36f2.nq.gz
│   ├── 762be28f466ed68fb4cf91ba9aaadc0877b270be.nq.gz
│   ├── 76912ca08df3f929fcdb737bae392e1358192c3f.nq.gz
│   ├── 7747788986b2b6478d348c22f6eba29fe6870810.nq.gz
│   ├── 77537c6371cc5ab998bb47cf53a3b982c9dda697.nq.gz
│   ├── 7915758cf7dee59e1a88834d33287612cf2767e5.nq.gz
│   ├── 799b14915ef5ab97164d0bb49e3b2d9185139739.nq.gz
│   ├── 7b9e32e909e2ab55418b3ec56d93c1a864914ef8.nq.gz
│   ├── 7d07c6bc9688f266effc76f028d9549f47679847.nq.gz
│   ├── 82aae4cd1d94b7eb3fe86d675313bd0003739acd.nq.gz
│   ├── 83dad22da6efda03ecb5c208c82649c622cbe8d6.nq.gz
│   ├── 83f7456931f80905ed08cdb01f6738b4663aea23.nq.gz
│   ├── 85fb89956fe89b7b496556462ca7fd951e1c8c47.nq.gz
│   ├── 86797585667b49f9617fb0a14063af3f83ac1b80.nq.gz
│   ├── 872cc003976a52e2c764a127bcdd23ece54888fb.nq.gz
│   ├── 8a7cf0c5645f2fcd829058b057f4c2411f984a2f.nq.gz
│   ├── 8ac3a83d40c24447549e8953b815f2be6e756c9d.nq.gz
│   ├── 8ca650b441bc03d0fdd35aa6ac06fb812b0c2db4.nq.gz
│   ├── 8d7841cfafab02ddfbbcead18f2f3c9b8dcd68b5.nq.gz
│   ├── 8e14ddfe1e2c9f71c07686ffca044b3c2611c1e8.nq.gz
│   ├── 8ef7035b0db0b9492c911f7a1845ff9159c4f372.nq.gz
│   ├── 8efa83dd5d8be72a2160a65e44b63262b6acb8fe.nq.gz
│   ├── 90461dd9ed8b333603b6fd5d6634e08a4bf304aa.nq.gz
│   ├── 909c1db5644eec2da5a6df7de36fc8a3c847b34e.nq.gz
│   ├── 911481c63af826745f7d549aba97e52e5ad572ee.nq.gz
│   ├── 9175b6d284d9ce1501225e819bd57fc0e186cded.nq.gz
│   ├── 930bf028f8f14a1782f494c1caa711468ec783d9.nq.gz
│   ├── 96253f955706c005627a2baa8d848cbfecc1565f.nq.gz
│   ├── 9747dc3649baad55949e45976cbc14af607859e3.nq.gz
│   ├── 9908a505a942292deb2d25778e3183da97315a05.nq.gz
│   ├── 9a1be5c1f5573ccd62ca31cbb730dcd7b1c036ef.nq.gz
│   ├── 9a2bbc7ab1a4cf43bfe91a33ab74c2bad4b4e9b1.nq.gz
│   ├── 9b466128b89299895474b1f590afff265199ea8c.nq.gz
│   ├── 9b5bdc3847cdde7dbba983e3a3e8e7f56f861939.nq.gz
│   ├── 9b81ac2470f4cf766ad9f16695c5d9307235f785.nq.gz
│   ├── 9da9606ccb01b960bb5de6e5fa1ac56e158dd277.nq.gz
│   ├── 9dbec8a6649dfb4f28c12dbb3c1a15a2383c6dd7.nq.gz
│   ├── 9e6f6c85fd9a0e9c5c1eaddd4491b8e46d32595e.nq.gz
│   ├── 9fe59c4a016c4ab3a96d9edf64094e122450662e.nq.gz
│   ├── a22ad21e22165f8f10e52d1d4edea9b0d28e9bc7.nq.gz
│   ├── a22f02ee5e92c97d29650fb94ca8fa499c6a8e4c.nq.gz
│   ├── a2cbe42b232bfeebeb0804f3bd62318d24ca2d7c.nq.gz
│   ├── a346b481c558feaaf5502687fb1064e310d3196f.nq.gz
│   ├── a8a0b528705592dd93233238ee148c0c507e2e0c.nq.gz
│   ├── a8ae70180448945598a512c4c2da563c565c2fcc.nq.gz
│   ├── aa2920612c88915d436d70f1056c650eeb577a5f.nq.gz
│   ├── ada4066d28bb4f6ab91ea9f4d7885607641632bf.nq.gz
│   ├── af76ff029c5495e7cb7cc3f61c012b17de16a164.nq.gz
│   ├── affcfee1eaf1854b0780cda370c74cd07fbefe59.nq.gz
│   ├── b0513b7d02d4ca9d4bd997afcf3265613d9f8b5a.nq.gz
│   ├── b102a23872e9f60cd488fef04150ced4189b87bc.nq.gz
│   ├── b1e2d2510c495357233ce12e6ad3bf16ac8171bc.nq.gz
│   ├── b50dd7517f16ba9f41d3b4c56cf8011c62be5eba.nq.gz
│   ├── b5929d2687844adfc24b444bc29e5ceaf3ac0caf.nq.gz
│   ├── b642719f6a58f40adaffbceadd414933ba6255ec.nq.gz
│   ├── b6875076d0507b163d60dfa189eae93b93aa4869.nq.gz
│   ├── b6a0dbd43bb03ea715b773811fb0be88084b35d4.nq.gz
│   ├── b6aff3fff023f42957241c7b46667ae5bbce17ca.nq.gz
│   ├── b8009be60a87cba12929c9d465aa0d12e3ec33ab.nq.gz
│   ├── b88767a9245a1d28769199ead5e6198c961db969.nq.gz
│   ├── b990f4b4ecfccf5f6f46bb3a12b1bf1781ec595e.nq.gz
│   ├── ba384ad6f947a776890b8be5ed52074c56f9fdbf.nq.gz
│   ├── bc756e2fa0b92c1aa15ba9ecd11a1fb0a23f1ad1.nq.gz
│   ├── bcaa769de925750b12c166461dae66836cbcb44a.nq.gz
│   ├── bd11ac385c386d52ce8d11459b6915585ff9b62d.nq.gz
│   ├── c0c2023c01140c4b9b62363f92fdd2235452671d.nq.gz
│   ├── c156d2148218c538ad4d7efe4af51c233e3b84be.nq.gz
│   ├── c159fe5983311a1827e578e2290698cf2ab92854.nq.gz
│   ├── c203cb4ac9f0306b8a1e6b1c80b0c1fd1e551f47.nq.gz
│   ├── c2660705872cd54a64b19a5c9fb726b2f4b9a257.nq.gz
│   ├── c68c4672f1ce8cbf34740dc6f07549b983065041.nq.gz
│   ├── c6e054377a857adab81781fa4667deed5c152c91.nq.gz
│   ├── c6e0c96569d77de93c57c5b0e8ab41ccd0f4bbb6.nq.gz
│   ├── c72b60c508c625622cdfd4fc178fe1158c2366b0.nq.gz
│   ├── ca30ca1fa9cc0e246b64892dbf8714056ef60588.nq.gz
│   ├── cae9f9512377411fee0d4062011c94ba63056710.nq.gz
│   ├── cb996270bedbe0f9d8290d628016a25ec94303bd.nq.gz
│   ├── cc1463f7a1b266b7c6e5a5bb42843b5d975d208d.nq.gz
│   ├── cceb2c8786cad525ab1217b9a824b2e9754f246a.nq.gz
│   ├── d0da18ea0b1af5d7765acf43a322c7d2cac87d28.nq.gz
│   ├── d1ef1ba72096e8115883a48da5d853cd259b2115.nq.gz
│   ├── d2c8914c7cd72608661dd1807b2652cba348c81c.nq.gz
│   ├── d7ffa5a4657d9d1c8d679a535b8a3d896e1c6087.nq.gz
│   ├── d8b3214d02e0244ec3f5664005246cdedc097673.nq.gz
│   ├── dbda3d6e735f8373a66ff68cc62e0060797b6e35.nq.gz
│   ├── dce67d860af47a4eb630117ce03624bae45dcf26.nq.gz
│   ├── dd73d75e3e8bf7042b87eb5ade1ea5f10aa894eb.nq.gz
│   ├── dea8c0babcf7ca7369121ac3f558ed3bee82d447.nq.gz
│   ├── e05f1d3ee5961b2c992401ec8640df09700f7ea6.nq.gz
│   ├── e10a75a58fb211f35a1fc674ce26ee2d6f9e6f9f.nq.gz
│   ├── e34ec750907b90d6c00e375a598e9d636dda66d0.nq.gz
│   ├── e6951912edc2124658e7e898fefc7fb24ce34914.nq.gz
│   ├── e709bf51f9751951242a2a1a69b91af473324f93.nq.gz
│   ├── e8b8f9bd014cf8e3725076b1a6fd90d99aa4af78.nq.gz
│   ├── eaa515bef41cf240332ee37b70f068c4dab929dd.nq.gz
│   ├── eba58eeae28d18ec9a5512f7c4b471e47ee29e97.nq.gz
│   ├── ecb9afc9c77e6b05533d00201156832bcc586a3a.nq.gz
│   ├── ecf8f2e7b04c8fade584d430ee9a1e39f36997af.nq.gz
│   ├── ef02a4a246620c7756b92523839eb880a0f2732b.nq.gz
│   ├── f3b812298f3893c744bf8a9c0de8dc6774f24497.nq.gz
│   ├── f3edc07c225180ded81cb68a1a45cbde322e479f.nq.gz
│   ├── f5fd4d646ee51291af2af77126cbd9f7c08c24be.nq.gz
│   ├── f6b33f3fc397eeb14571263b8ed44ea383bffa9a.nq.gz
│   ├── f7437686f4e927e64415742f4fe05b795509d809.nq.gz
│   ├── f84ea757d1933d6acbc8b6e5a91654256b2f2479.nq.gz
│   ├── f8a45135d4b18a3cc4b7450205a6def44d6b85a5.nq.gz
│   ├── f9bfbce4260e43b0df213604799de4e27dd3d2c0.nq.gz
│   ├── fa25017b18fae7c6db023bd2b72ec41da4e372e9.nq.gz
│   ├── fa2c5044cd1e27616f61e04cdad5bc9ec5dfb448.nq.gz
│   ├── fd72399c66331a3e6eb203c850137453f855125d.nq.gz
│   └── fec1ab6f32a2ff748a73ab2666f36e7dc7704a2b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e42b63f984ff4fff923a1e856a66763a55591029.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 194 files
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

[ksss/rubocop-on-rbs](https://github.com/ksss/rubocop-on-rbs)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
