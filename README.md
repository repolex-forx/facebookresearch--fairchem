# Repolex Knowledge Graph of facebookresearch/fairchem

RDF knowledge graph data for [facebookresearch/fairchem](https://github.com/facebookresearch/fairchem), parsed by [repolex](https://repolex.ai).

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
rlex download facebookresearch/fairchem
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d4e10d0f4e87593922fda1d1ffb7dd28e504cadd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d4e10d0f4e87593922fda1d1ffb7dd28e504cadd
│           └── chunk-001.nq.gz
└── blob
    ├── 003deefd7372962825130b9d125d99de6bfbc522.nq.gz
    ├── 016b4b2b35a4f14a60779ad4b48816369a1ca561.nq.gz
    ├── 01c2607933417b2f458715efa3775c3fd6fde1de.nq.gz
    ├── 01ed13e3f1c78bfcdf09077adc30aa3ab4a64685.nq.gz
    ├── 01f60074ed887c62a7ca686c5bcf069a59baac7b.nq.gz
    ├── 0270c72bcdcc4f4901873a24af6b31c2c43c5363.nq.gz
    ├── 02885535aaf2ccdf3606ab63b8a1315938a5e2db.nq.gz
    ├── 039fb0d4f9a073f731a291483e112c62e3fb7a8c.nq.gz
    ├── 03a7ab304043ed5630b7f2e61e32dfebe16230ce.nq.gz
    ├── 03d095f494eb829c5b0e25e84c0410d203cdc35c.nq.gz
    ├── 04792b3b93a8c26fb6848bf6e5c87f0241effc39.nq.gz
    ├── 051bc711d61bbdd7fe3f709053ccf3a103b8fe62.nq.gz
    ├── 056ca45cfc428af3d132a1112e6e38000d3748ad.nq.gz
    ├── 056d5d9cbb27680cc42e2389ea7bc71a5d4e96ab.nq.gz
    ├── 057112e2b4351794adbb14948a68fbf987fa3c1c.nq.gz
    ├── 05711d4b73be70e20e07e86bae0f41eab18b05e3.nq.gz
    ├── 0592e26a75e3fc702dbec74049f48c14a0df9df8.nq.gz
    ├── 0631d89ef605893917f0028854ba71b361f182eb.nq.gz
    ├── 069fe6feb2e820812414e54929c80979a85fac74.nq.gz
    ├── 06aba8887f3240692d2e81f32e5463dee157429a.nq.gz
    ├── 070988e1974d6d1a3c4ea9df5aa268218c5d76d0.nq.gz
    ├── 084ff2fe308770c6c1b4e832d25df296c96b7b48.nq.gz
    ├── 087ce972e14a708cda9f4674a1cfe901c17c90b7.nq.gz
    ├── 08cd366c80d1e3e5b876742e5a493b8bc097bc38.nq.gz
    ├── 08e0c68eb10ab3b8e162715475318b9df1cc4dea.nq.gz
    ├── 09bb653ad96aad81e2295a87ec3922eebd3324be.nq.gz
    ├── 0a4ab6daa6c940c0b988f01d982bf7a0427b98d5.nq.gz
    ├── 0a5cde019474b976d6d54ff92188b93d3b7258c5.nq.gz
    ├── 0a9e98b494a273a58986516e246529d114a4c452.nq.gz
    ├── 0b044486ec74f465d6cbfe8ccc2c17c58d3a035a.nq.gz
    ├── 0b2cea3dfb1e26f97caa96e2a5903636794ab475.nq.gz
    ├── 0b51a4f99129e16901e06de81778163e41fd21d2.nq.gz
    ├── 0b56cd94446a88bbd71a67bc418fd99167d5476c.nq.gz
    ├── 0bcef420e0ff306dd55c197634715df2217f65ab.nq.gz
    ├── 0bcf7788a857f14f0fd4b5411ab8ac19176e8719.nq.gz
    ├── 0c33af8ac4a202447dc398caf8acbfa17d8993b5.nq.gz
    ├── 0c94714134f083134b4b35b4e4d13024c230e8fd.nq.gz
    ├── 0d2a46e1ff9cb615c2055fe6facee9f7dcfc96d6.nq.gz
    ├── 0db48739acf89608caca21ef6e06c6acc0c40848.nq.gz
    ├── 0dd34c38a7c034fb7d996e43ba820b8abea57102.nq.gz
    ├── 0de1374d16e468a6ed9b1ff813467c92912488dc.nq.gz
    ├── 0de4a689a79281c598b70c17761016f10c6e180d.nq.gz
    ├── 0e082498ccdad532030c687efde3c9cc3520bdda.nq.gz
    ├── 0e96cdec8882d1c8f51ba80f56525d4583416a1e.nq.gz
    ├── 10a6b2af4feab8158504a00258f12f662e482a81.nq.gz
    ├── 1127e4cd3735e5ee6196a26e0fddc2282d726748.nq.gz
    ├── 113f8d230127023c2e9b3ccfa8aaccce07be6c62.nq.gz
    ├── 12bd7157eb27c7e91466ca20beca79210f8190b4.nq.gz
    ├── 13272eab173dc147a03ab7614483676b11fa28a5.nq.gz
    ├── 13308282be176ba99829b76343b65887887a03eb.nq.gz
    ├── 13aafd89a1a07e5ffcd6082845e67f432ab3599d.nq.gz
    ├── 13b34af5faac5182a513bd66a76405053d0a4190.nq.gz
    ├── 13d8ac5cab46adc767cdbd07a67c316aac212db9.nq.gz
    ├── 14458ed9491d6f79fabe6e770fb3defdb85de1c0.nq.gz
    ├── 1489ecc6b62befe5c15a23b19e6b94a9d0900037.nq.gz
    ├── 14cd675fadd29e6162e7bf93367154462af3bf17.nq.gz
    ├── 153682f6a9ff3889a59cab1a3d30dd663c7df6c6.nq.gz
    ├── 155a38b981a8fbcb7cf89273d8af461cf1e2f048.nq.gz
    ├── 155ae002d376efcc7363d3bb7dd550feaf6d232c.nq.gz
    ├── 15819cd89d8e6e661764f6fe631aa82b23fd06d8.nq.gz
    ├── 15ac4387d559f11e5c0f6c13822fe2bc30ed823f.nq.gz
    ├── 160f46c28972038fbb654971c2e659755b264838.nq.gz
    ├── 168d7330fd5348528cb763c4ab3ec5920dd60c9b.nq.gz
    ├── 173ceae59a42e8ae9eded14410a709a362ed365d.nq.gz
    ├── 17ab91a100c0f0f5885c7f1d128dbe369f61ee7a.nq.gz
    ├── 1870e12a7823caf666e2fc5c5c14dd6d35f431b0.nq.gz
    ├── 18a7d55b1fe8ad9de903454a412c1f4ea507d172.nq.gz
    ├── 18bbd0d4a2bf263403631146577f6272111e61ac.nq.gz
    ├── 19bce8ec532bf13950ad8d85106cf05b4658763a.nq.gz
    ├── 1b2762e598b85b50ff0cb0ae3730131f46315e08.nq.gz
    ├── 1bae6117908482305e5f136c774a6bad8a5004de.nq.gz
    ├── 1ce5dcd72f3a2b487dc9d8b8587d1df92e1062c4.nq.gz
    ├── 1e10000de5a791c8ceab6f3f294b045aad281d4b.nq.gz
    ├── 1f58c77c943df82abbd1eca8c2ec87b3fc8a4b43.nq.gz
    ├── 1fed157cb89970008e1bf3add78c5187d759e6ad.nq.gz
    ├── 20a6d34bec25522adc5eccbb45bff91d4221cdc6.nq.gz
    ├── 20b5451e897256c534ab7e0a1cc14b332e3e7763.nq.gz
    ├── 210e4e7a96cb0430dbd0f1e98330609a7c8dd04a.nq.gz
    ├── 2200805c47a5e5022c3942817d93843b5ff82e5d.nq.gz
    ├── 2231520bd78c4e6cbe6608a014a5dd63e1906554.nq.gz
    ├── 2238a3fe527a02930debaf7ba0646a7b8b745f06.nq.gz
    ├── 227c56cc2b4df3cdaf80a4a45750a6a9173dc043.nq.gz
    ├── 2383f488ffcaca3c2c13dd8f424df090f3b484eb.nq.gz
    ├── 24c80269ee968e905833bcad0ce959e644ebf4d8.nq.gz
    ├── 251516ae91fa95134f29332a89472da5dd9b9c53.nq.gz
    ├── 25714603f3d323ee4370dab704b01fb70c630afb.nq.gz
    ├── 2596b34eb8ef06bdb918cdf6bd7256ca802c3570.nq.gz
    ├── 25d93fa0438bc7f2906aec4a7e78d64aa047f5ca.nq.gz
    ├── 2632f3691670e6ca94200604ab50d7deea4ac609.nq.gz
    ├── 26a66dbd46f0bae20ec19c9f4dcadb42cb4645fd.nq.gz
    ├── 2743095c044976c245b6ff112976befdc5a56d96.nq.gz
    ├── 2772dc4462492be1275c823d3b2439042c45a58f.nq.gz
    ├── 280103ca33c7471f7a797d8ac5aeb87999dba877.nq.gz
    ├── 2842d3b1d4d32c7db8889b429e54f98bc5431ddf.nq.gz
    ├── 28c95b1209c2ba1b91717595a146f94ad1d2284c.nq.gz
    ├── 2980488a48cd642aec6b3d70d4e60d16504cf03c.nq.gz
    ├── 2aaec5a549824e4eb896bcfa73350b5d8dfee9ad.nq.gz
    ├── 2b6842297c02b084d45f233e9d458c3a8a548269.nq.gz
    ├── 2b8bca8f16823c880f3c0cadaa2273a556a0860f.nq.gz
    ├── 2bcd79370d180e81b253d64936eda2eef8d0d6e4.nq.gz
    ├── 2be773edd6021bd70ad2afd53ee0973ebc91b0fe.nq.gz
    ├── 2c22e1b9823d64e8ee611f1bbc0de10fd3f091b5.nq.gz
    ├── 2cb8dec0a2250d6afac94ce93906865ec6c85b4d.nq.gz
    ├── 2d6b06b95318e87df1dc4aa7b56234c5b9bd1677.nq.gz
    ├── 2e5dfcb3d4fbe80259ba80f0c207b75345d5a191.nq.gz
    ├── 2f8f15e6f8058bace1b05a08ce0ef65fd9f9f599.nq.gz
    ├── 31ad98bccbef6ce182e784ad3b38ec4411e2ac07.nq.gz
    ├── 324ebb6a6bb8a409e4de58eca2d19d648abbbd17.nq.gz
    ├── 325f491207a4967e6c2392c7f28bcb57a393f2ed.nq.gz
    ├── 32cfe66640238a77849657169e7b5db082390f50.nq.gz
    ├── 32fe19ad4e1b53dbba2faac8e961633f4995f89a.nq.gz
    ├── 33114bc69cea4fe50f7a457d25f22874a7119e4a.nq.gz
    ├── 336ffe3e168e64f87a6c150bc17f3df47a259dbb.nq.gz
    ├── 33b0e79991b6fe97acbf5cebbc714ca8d5dbe546.nq.gz
    ├── 33f7efd1933bcf82c0f3e70ff3fdd4b829fa56fa.nq.gz
    ├── 3416ee4169b42d52b7243b172c5209adec3abe29.nq.gz
    ├── 349a9734dd5b92640410da97e7890f955311aa99.nq.gz
    ├── 34ced909f5a789c92343be04397676faba81424d.nq.gz
    ├── 34e9d8547545db4b5706fc35983058b6adc7d19a.nq.gz
    ├── 36147f602eb684b23e3559c3ee7bcdbfce5b4edb.nq.gz
    ├── 3674085b6000f8f245ea0bf613198904ce5a2e1a.nq.gz
    ├── 37058815c0a467f2146c1e90e3e08fad84ea4ea5.nq.gz
    ├── 37333bc56135390c4fc2cafba22f2b65aa63f268.nq.gz
    ├── 37889fb4db3c9ef66ce4b453b500e601bfdb4ad4.nq.gz
    ├── 37db87a8e3c0b955ff9b4f19feb8331f07342354.nq.gz
    ├── 38396b89543fd0e0dcfb276489c7ce2996684769.nq.gz
    ├── 388ff218a6218f236485f08845001d854d705fbc.nq.gz
    ├── 38cb5c466f58ebe56dfa3a1b59b854b0a8cfaa2c.nq.gz
    ├── 3910393fd4592930c7958c01a27678fbfd06fd29.nq.gz
    ├── 39124bc122cd775ae485df9303c96b075828d697.nq.gz
    ├── 3aa805d6a1f8718910a1b8cd4a5a219b4a3fd913.nq.gz
    ├── 3ab6803a2749863963bcdabaf875ca3b77f1cf52.nq.gz
    ├── 3d2706d2821f08cfe88a71bccb97990e32d8c13f.nq.gz
    ├── 3db3642a80bade2ce77f6170790a40d7bfa557c9.nq.gz
    ├── 3de0f9397f95ef8d51dda95d2accde87db68510b.nq.gz
    ├── 3e4be178207db6e14603161ee43759d3ed55aaad.nq.gz
    ├── 3ed81c1e7a22bfcaafd9d61d72cd526f1712137d.nq.gz
    ├── 3ee99c028ba35283b6ecdcb58701fb24cd082f29.nq.gz
    ├── 3f17489f6aa8b86dfd11c80b138991e4641b6e22.nq.gz
    ├── 3f59b4be8d0f108a7e9f1db88076db84395e5321.nq.gz
    ├── 408ae6a3904f442b5f3a57fef56d44d59c6fd15b.nq.gz
    ├── 409077c801491deaa134d5e97df3532d570b66d1.nq.gz
    ├── 40a547c2d2eeaae2077c732486931a7429c55db9.nq.gz
    ├── 41365dfcbe77a1d853478b92a59a18cc01807255.nq.gz
    ├── 415981df6a433bfa55de872d9d7d2264e55a87e4.nq.gz
    ├── 42343955ef393d0cc5ecd8ef5ca92a1a8d0af0b3.nq.gz
    ├── 428b65cb001b197b568fcfb1e968b4041e34a264.nq.gz
    ├── 432db2bd7fc591008faa06934b7a57b3b1a797d0.nq.gz
    ├── 44560a4eeeff5c6df72ad3d1c4deed516a82a52a.nq.gz
    ├── 446059f30d20c1a7c7ae0151d6a5b91be3ad2e2a.nq.gz
    ├── 4527c9116a0483ce0ceef19c37c0c761ed868c5e.nq.gz
    ├── 461d1aeda16341856467e47224925519cc29db2c.nq.gz
    ├── 462455b6a9c2a062ab842c593acddd55adb1eaf7.nq.gz
    ├── 4649db3cab53830518eaf82cbddbf900cb68910c.nq.gz
    ├── 46e70841cf2cff6aaf1276e7b9eb12444beb520f.nq.gz
    ├── 46f190eabb7b50ce2bb7647e6b6ef0ce5c6f81f0.nq.gz
    ├── 475cb7d8b4103d1af0f7a30da149c62502727042.nq.gz
    ├── 4774c6839930b59505110d4fdc0ca4e75f8b1299.nq.gz
    ├── 47953f57016b55508900657efff0cb22727954d1.nq.gz
    ├── 487838ec439101d5fb2fd4603b0326da5236a7ed.nq.gz
    ├── 48acd0cb166c7677701ecc66a0681e18193cb7d0.nq.gz
    ├── 48d1ef23352a411fb801607457c594dc500111aa.nq.gz
    ├── 49d8fb3e0718a7e0d9c86bb8ce42eb90f6432b79.nq.gz
    ├── 49e85edbf6a16438ed192a4990caeb562cf44467.nq.gz
    ├── 4bb5b52ffdf27a41ddcb9f99313d613f81b25117.nq.gz
    ├── 4bf21e8721cdd37f9ad223ac4ebc51997a026d0f.nq.gz
    ├── 4ca9101b8cb57b7eaffa574c5097b578be12a843.nq.gz
    ├── 4d2fe1f43aa0d63669f0347f8af051754ef7d9ad.nq.gz
    ├── 4dabca8eeeac2d8a13ee2d1653a187c1af184b07.nq.gz
    ├── 4df3e14e5b899a91cc6392ba06a605b49d252c17.nq.gz
    ├── 4ea8e90025ce0fd0d7a35e5299bbfd820f96fa2d.nq.gz
    ├── 4f7057c38ce8594073124b99f1cb8f66e28e9916.nq.gz
    ├── 4f7fa65950f3f2e7c07a4e120c8a7ad0e301c742.nq.gz
    ├── 4fc086d8146eb93077dc776897e716c17ffee038.nq.gz
    ├── 5022b5eaac151ac842aaf1950cdc1b3ceb074c02.nq.gz
    ├── 50962b44c01f0aaaac9a7120cecb880a3bfcec62.nq.gz
    ├── 518cdf2858cce1b1d458fcb10ac5f3ccf182a816.nq.gz
    ├── 51e05212f8b37f06f0fcf0a30dc1aacb9849c634.nq.gz
    ├── 52dea7f32a51853ab8c91439b2383973d8c8b828.nq.gz
    ├── 53ba439e7bb742e58a22049ba3d829c9ef49990c.nq.gz
    ├── 546323a11e7a3875775004d1815c205d40ad01cf.nq.gz
    ├── 552fbfc325f3d5d75154c2aa02321f73bf2d817e.nq.gz
    ├── 55309dbe3d3006489fbd2483ab4820b839d06d6f.nq.gz
    ├── 559202cb3e79b13518b113bb5728fe41acfa2046.nq.gz
    ├── 5685a44b78635fb2746e58cbd7359d132822d31e.nq.gz
    ├── 578da0cb6415371cf1df04d024194d6a2cff3b6e.nq.gz
    ├── 5ba38dbeb1c25c011aae155e315398c8a740e3b7.nq.gz
    ├── 5ba7803d2b96845fdfdf214fac4c1bb3894b2299.nq.gz
    ├── 5bf4447b3aaf39b862390363c419c1f875df1ae2.nq.gz
    ├── 5c69570d75fae6b1fd1a84ff55ed60a1b59b7222.nq.gz
    ├── 5c8b6bd2da89363c5a4d773807d8689f27cba97d.nq.gz
    ├── 5ca5c406238a77d6329638477cd41ea7b342975b.nq.gz
    ├── 5d749bb844724a586240142be89f385e7bbd1c41.nq.gz
    ├── 5d9ff34859f0a050d9f115d9ff41de75a4c0c6e2.nq.gz
    ├── 5db3d41d300b1f9e14a0a28e51bc0dfeb1b60029.nq.gz
    ├── 5e282e64b52bef79b738e692abd45e7a4ca56396.nq.gz
    ├── 5e7c700757b17a30c8180a59475350cf9c76d7f7.nq.gz
    └── 5e847386aadc06a87798456a71f84fce02ee7f3e.nq.gz

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

[facebookresearch/fairchem](https://github.com/facebookresearch/fairchem)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
