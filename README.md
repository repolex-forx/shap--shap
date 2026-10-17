# Repolex Knowledge Graph of shap/shap

RDF knowledge graph data for [shap/shap](https://github.com/shap/shap), parsed by [repolex](https://repolex.ai).

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
rlex download shap/shap
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4f8a9c97fb0ea4ce4b3c023f7aa6e86f4780610d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4f8a9c97fb0ea4ce4b3c023f7aa6e86f4780610d
│           └── chunk-001.nq.gz
└── blob
    ├── 0001c2912c2daf9ec974bdfb0e44f083add340e7.nq.gz
    ├── 0003764b85fa266a1f25fa08ccaca281ffcfa8dd.nq.gz
    ├── 00ea9c8590ce61c78010713b11b35aba75861587.nq.gz
    ├── 01143add74d4ca548b2eab2e5da86debfc0885fb.nq.gz
    ├── 0132ff7a088f67097875ba0d1eb1b82295b51d4e.nq.gz
    ├── 0153e97e1ff03792f0424cab6ae22cf8f4411c0e.nq.gz
    ├── 0195aa75873c3b54bce8d27980606b9920a486ce.nq.gz
    ├── 02c896d23be3b32fc808a3d1e826d2675937ebfd.nq.gz
    ├── 0358dd349f6cc694c1621ffc3b847dfdae0876c2.nq.gz
    ├── 03a7b38bfb992aad103a00946b76ca3ac6f2d8b7.nq.gz
    ├── 03cddce46eaa338ca7f6ff743b577d11ea3038d8.nq.gz
    ├── 05374104bc7de8d562dc367ddaed4237c54288b6.nq.gz
    ├── 05520578d6c816dd4b8e6e9b7cd1aa050cf93df8.nq.gz
    ├── 058d6c224c71ebc93f0ca4f7d82abc5ac51628df.nq.gz
    ├── 05d444beb23ce2560e9cd79d654bff553315c379.nq.gz
    ├── 06fd5976109dd591d3816c7e799fe202ad9386b9.nq.gz
    ├── 0730ecca9b2c11aa5cf992bcf1e0d3030a9238fd.nq.gz
    ├── 073a631e4130ec616e936b3b2106b6310661ad7c.nq.gz
    ├── 076866c5fa37a8b95eb73045f84d44bb912a1f3f.nq.gz
    ├── 07f63b9d30995a98813739169a42da463df458f0.nq.gz
    ├── 07fddc3418f8c46a879f33171816caff5c1e5dfc.nq.gz
    ├── 082129acc7b9adb995aa3ba44ca06cc5cefd0fd8.nq.gz
    ├── 084ee3e90f976de88b6c1ff8f3843082c527ff55.nq.gz
    ├── 090b192d32183b55d6d2a17860d57d19eba027ce.nq.gz
    ├── 0a4021a317fa15609076752c4fe8d886960c1c9f.nq.gz
    ├── 0ca359a0124e89c391bca0ca2e2fdebcc5b5f789.nq.gz
    ├── 0d42d73233835179e818e187640115e1db73bc51.nq.gz
    ├── 0d8e59586cea9e9c978802a69802bf79348a314a.nq.gz
    ├── 0d8ef0a2e322642d413db8ece9c791f6230793af.nq.gz
    ├── 0dcf8ba232ea727c76560e66930638ee8bb5f631.nq.gz
    ├── 0eacecfd844cf824d5046a1de3a8a8f4cbcc351a.nq.gz
    ├── 0ec99fb0e4998c489240b6adb1637a43196ace84.nq.gz
    ├── 0fbfdd83066b664133cbf8be3fb7445809654640.nq.gz
    ├── 0fc775f467f3cc5166ee77d7eeb652a121be5b64.nq.gz
    ├── 0fe96498f066dffbb1e2c56e54285eff6a8b588c.nq.gz
    ├── 0ffe0caafea2ae99562f3f9859ef4389e9b77d2a.nq.gz
    ├── 1019a967f1f8a9f8aedb7196e219e88192004ef5.nq.gz
    ├── 105df795343400a01413f15b9b0b54e3d379afb0.nq.gz
    ├── 10ad600d6ac6ced9c6cc4ab9798f9d1d39e4c0a0.nq.gz
    ├── 10d8e632699b171e61e8acc365ea32da9634c1f8.nq.gz
    ├── 1152bbd29c3228ad9cc12a2d4514546fa9523455.nq.gz
    ├── 122ab517076247c570adb2422a677c0356975730.nq.gz
    ├── 133409c8b6904c90e64acfa0bd72075a936bd950.nq.gz
    ├── 13c2aa313ab5c311354f85a84d3504e8f2f16f9e.nq.gz
    ├── 143267b25f61fbba429df4b0e4bee5683196f237.nq.gz
    ├── 1438c2cca15b14d005c3aea767e748c2238589ff.nq.gz
    ├── 15342e377dac514fcb2e3d35d6daa67d928ad204.nq.gz
    ├── 160ba55c07370f97fe3cf7d40da5b96434891bb3.nq.gz
    ├── 16aa52c63ff628118a4337166f8eb840e721b8e9.nq.gz
    ├── 187155e2d89163960cc2e353cd6235635adcc5e8.nq.gz
    ├── 1904d35fa1701877cf5c7cac470da751fce0dac1.nq.gz
    ├── 197b605b31399b66ffd1b53ac2d6f9e6dc9820e5.nq.gz
    ├── 19eff208c1ddd99ffb2ef0f4ee061020582d87aa.nq.gz
    ├── 1a73d7087dc835c3716fc32332ad5f928c7b466e.nq.gz
    ├── 1a79c1377a684ac17685d7deee08cf6978d7dd9b.nq.gz
    ├── 1c405a0ad8728b51824351ac33836aaa6e2a0837.nq.gz
    ├── 1c48e9c660af81e83d3e5d373f838c768b6ca6c4.nq.gz
    ├── 1cc65fb389700d92b9a32023a948afb202c9d18e.nq.gz
    ├── 1d372d65599d626d8c08eaa7bd7eecf54a260a08.nq.gz
    ├── 1d48f34c0c89284da9f3bb95cdf43e921d97d390.nq.gz
    ├── 1d6927ccb3c7a69e3af1d24bcf4de4e8475a0a44.nq.gz
    ├── 1e5e38eb810ba15854f32b21dcb7289e2dfe3eb7.nq.gz
    ├── 1efbbfb253bb838f2e4902879963eb9a57dcd599.nq.gz
    ├── 1f2eb67e0f288ec374ffa93dd8114e416196dc8c.nq.gz
    ├── 2020c32f1e1c8e08498e475708e20e57b78f2045.nq.gz
    ├── 20df901fc3e22d5bf6200bba3debbcb344276694.nq.gz
    ├── 2178687ab78dbb7ec47f3d50b2322068380c16a1.nq.gz
    ├── 21f45991648dd71bdfea99238e4b75c67df70c59.nq.gz
    ├── 2243b2238508354b6c1100712ef71367b0acafb5.nq.gz
    ├── 233b2a9f99ece78de83e209ed1d5fda219a32f82.nq.gz
    ├── 23515eac7ebad5a5136565d13e79a98585229188.nq.gz
    ├── 23d91b94379a5d72f87b4e11056ede97f3f252d7.nq.gz
    ├── 25d4a3570bb2285d39bd74bc9a4bf2fa82076eca.nq.gz
    ├── 2611ce4fe0cbfe94232d8af1962b6f91cc02a75c.nq.gz
    ├── 265491f55ee71677f889cf2742feb5369aa66990.nq.gz
    ├── 265c96c082ade40277715242fcbc7c3382935f7e.nq.gz
    ├── 2687e36289c90d90f318554901ba66e1ebc05d1a.nq.gz
    ├── 275bb2f940a1b97cf2e2e8de99e320b6aa9f4598.nq.gz
    ├── 277413c596256cd04b0f17b673f4b395d0f3749b.nq.gz
    ├── 2855e16e8952777fb64bce939a557958b2df0a91.nq.gz
    ├── 28abe1cc36d064674d6850547f2002331b502e1f.nq.gz
    ├── 28c0b1eef58b0f865fb0ac6219b95259da97e184.nq.gz
    ├── 28dd93037c69d47573ee1e135953c70c6ca2e8ea.nq.gz
    ├── 28e2ed0a2bdc49ac4bebffe641f9f9a34d3bd8a3.nq.gz
    ├── 2a4bd91e1f79168c42d053da0e80092611a1c265.nq.gz
    ├── 2a9b1166e6f41ec3536bca014547ee94e639ada3.nq.gz
    ├── 2aa660b3fd94dd7535818a727858ee385d57045a.nq.gz
    ├── 2b60088530d266e9bbda54bcb3bbd1ddec72f6a1.nq.gz
    ├── 2b99d47d27c9cc7f3e6426f4a4d89523a1e8b482.nq.gz
    ├── 2d42fa99260c10b817869832e8880c722e6ca4b6.nq.gz
    ├── 2d6be08d4df3ea3e74f792ea796db8444e49d30b.nq.gz
    ├── 2d8f21e82258b0e2b13bc7b5afb70cfd9f5eee49.nq.gz
    ├── 2ddf5e2397c29036e3bff5a216f2b70fa325bab5.nq.gz
    ├── 2df81e3f23e6ec92c4cbe7fee01b0ef99487b4e5.nq.gz
    ├── 2fac7524172da30ba2090da7c623f7d9981c65db.nq.gz
    ├── 2fc0daddc1c0ecb26d8337dc11e77cc1ff2fb2dd.nq.gz
    ├── 2fdf20e3d7e3c655e541201fbe9511ddef97006f.nq.gz
    ├── 2ffb25fcb4545cfad5777a98db7b278b9aa502b0.nq.gz
    ├── 3107bf9eaa88363fbc7723b9727c0c0e32318a37.nq.gz
    ├── 32132f48d076501ba5d0db864bd7dbe836ae39ea.nq.gz
    ├── 3266a5cefe48f08edd876bf574224723bdc3e475.nq.gz
    ├── 3290d6e7ce7cb2d5204f05716e9bb9369728a585.nq.gz
    ├── 3608b20bfcdbe034c713fa4a671dee73766598cf.nq.gz
    ├── 3684f8b3655fee179fbb09b3f48ed9e6add889a2.nq.gz
    ├── 371464fd4b63a7b2e549a913ec05cf2854bf6136.nq.gz
    ├── 376a431cc8ffaa996fd9b6c70592f385deacf9e7.nq.gz
    ├── 376c386858d74d2a91fb903818a020c042f8d964.nq.gz
    ├── 383f1e84ed566e7ba4e5a04cbe7b5d1db770ac11.nq.gz
    ├── 39cd69d5497f8b793da61a80c8926b99feb33c35.nq.gz
    ├── 39f8eecb6ea4cdcbd52703005644e701938170f8.nq.gz
    ├── 3a19a07c1a9c07c9e6b4693e4f0ef6ebe3aa5d20.nq.gz
    ├── 3a3ac4c860d677df938ed1da25463d0a92f4d1dd.nq.gz
    ├── 3a6a324aaf30e0341c37982796a9049d59c8a090.nq.gz
    ├── 3a86e2b2f609cdfdd3ab9d27aa28df4c86d58ac7.nq.gz
    ├── 3ad1bed14409390b7f17f7d3be6a7c36876c6ed7.nq.gz
    ├── 3aecfdd7de51b86a4de73ed334b4dca9374df5a3.nq.gz
    ├── 3b76c8f7909043e627b1e1267902b004f040fe6e.nq.gz
    ├── 3ccb0259487b0e0a6b81a2707685221a9f6a04b7.nq.gz
    ├── 3d3f4f6d35fe75f920a7bc9a123dd47e92e971e5.nq.gz
    ├── 3d40b560dbe9419905942a9bba30811ffbe7a521.nq.gz
    ├── 3d858bd839d1d9da5f244ef161c69051df7c1890.nq.gz
    ├── 3d9f87f729355b3111bf9d59aaf3fbd507334508.nq.gz
    ├── 3e6ffcdf6ff5262b8922e334ea485e04ca212981.nq.gz
    ├── 3e7b5aba04f442455987eef21388fb5e86cad924.nq.gz
    ├── 3f0595f20d53df392dbfefdf090e669c9acd64be.nq.gz
    ├── 3f4993f8ec1a4fa318dbbf231649a40570d6e8ab.nq.gz
    ├── 3fb20eeb3ddc8234897f34027bb92258db26ec90.nq.gz
    ├── 3ff023380251db5e94190dd26d72bf5fb4128736.nq.gz
    ├── 426c4ca1cdf06340cfbcbe44fe5cbff7a5078c7b.nq.gz
    ├── 4284ed5e15b0758f0c2c1f5655542bdcd91d5daf.nq.gz
    ├── 42db1001b7177daee3fe0d81f22a8a0ffdc9335f.nq.gz
    ├── 430d49c9750e421fdf8fd7949326644fd23615a4.nq.gz
    ├── 436effcd53cf3c4b97fd14633ed190a13f3f9e4b.nq.gz
    ├── 44116e39959378e8bfb9ff8514ea5dca8f5d7bff.nq.gz
    ├── 4474c051d3f82fc611ad2cdb9b9f16b4b3512e5e.nq.gz
    ├── 447b7efafd704ef26520f5fde44d8b1d9567b69e.nq.gz
    ├── 4498357e12c0e9cf3aebdc5c5653c8a431cca96a.nq.gz
    ├── 44e31d4eac8350d6b3dcd007a1d16bdcc8e5d7ef.nq.gz
    ├── 44e4a34533ef4dbc924f5d37afced747b92de1ed.nq.gz
    ├── 44ec15cd7f0807a515c3f5a22f26b3cd8190cb14.nq.gz
    ├── 45043426ea66f21e08f3662544974f4c1acc9c04.nq.gz
    ├── 455ae09bc228a7aebdd23b15ee0c2267f220f3d9.nq.gz
    ├── 45e60204708fb9dcbf5c710dbaf4dc9a3b7e6988.nq.gz
    ├── 473c5c899e7db7a59bc6d32463759263ddd2ef50.nq.gz
    ├── 47950a437e6ec6baa5d480a7f54e15e8fa34d62b.nq.gz
    ├── 47f3e8c8062ae53378a19c5036fa23a3b085449a.nq.gz
    ├── 480715580b1588ade23ab6aa951d03b243949d14.nq.gz
    ├── 4808b5c38845d26f8cd10b43bfd0902dc3c57d96.nq.gz
    ├── 48ecfaaadde844f1435a92b189d04a9d8eddc021.nq.gz
    ├── 490a661aa097083c417240b0d1c67cf7ea34c708.nq.gz
    ├── 49307983dc1472f661235a8d9355a4f708574a39.nq.gz
    ├── 4992231734b002bd901a22d0f791ed13c0c4da3c.nq.gz
    ├── 49c02914c4e924b81079080893b8ca812126ec49.nq.gz
    ├── 49e6359f62c669f69f9eb2c40f48015fd48db046.nq.gz
    ├── 4a2b06264a0bdbc43d8a9ede33e080c6ea77b907.nq.gz
    ├── 4a4ca865d67e86f961bc6e2ef00bffa4e34bb9ed.nq.gz
    ├── 4a70516634261420a9353da9a8a6e32e5ca726d4.nq.gz
    ├── 4aa91b6e1be7303f50fc37a6187b4aaca8ce645d.nq.gz
    ├── 4c556d83a1f49a3c9f16f711be31f3df0cc40bac.nq.gz
    ├── 4c6e18d2dc98b54104fabc3a32235c5021f58de9.nq.gz
    ├── 4d25d9a148d69066aedbbbb733a1620644a02c14.nq.gz
    ├── 4d7f64b1e92b53c068de925a9049b007c786f8ac.nq.gz
    ├── 4e05950ccf373d34dd6b985f5b08f456c3ee1111.nq.gz
    ├── 4eac9c20814db4dee58a2715b0aa0fbe26897c9b.nq.gz
    ├── 4ecb931fe3c9daf3a6e08dcc2769d915ebc8fb2e.nq.gz
    ├── 4fe81035c131e7828464a2b009ca168fbce91461.nq.gz
    ├── 50241d2e8ded97cb2e81e63764ce4710b08b24c4.nq.gz
    ├── 513783af65b8e250dc6f8253b9ea3b6a6c078718.nq.gz
    ├── 51c832887a0818ad6875cb35f7cd33b08b8e2795.nq.gz
    ├── 537cb2564f5c3541ddecd8f5b2879e7cb9de554f.nq.gz
    ├── 53be2ac37bb3baf2db3614a7aab669e66789fc59.nq.gz
    ├── 53f21966060783e70f7c1f27e134148f21eae189.nq.gz
    ├── 544d50d7e7b4ee46d456a0ad6fc82f6b856bfc44.nq.gz
    ├── 5510b9d14ff98f2446f1d9f4d7e341ebdf375b4c.nq.gz
    ├── 55faa99a776c480f94dd76144d506d99a308255d.nq.gz
    ├── 565d93822ff5a8c79752a30a0397a998810b0848.nq.gz
    ├── 5693ece9a6dc36b64a895284e4f8318e39c3e049.nq.gz
    ├── 56e37557cbb6b3dd1174927961dc36be28041e78.nq.gz
    ├── 574d76551d4f43273de4b4e6f30d9649315e4d34.nq.gz
    ├── 57f5269c7c3dbc2c8448bf5b9d8e3223a857f9f9.nq.gz
    ├── 5872c2c57b1f5eb65f7c3999367054c84eaa524c.nq.gz
    ├── 59bf73c7cbdff275238f72bdc1b5fe0af3e1d56d.nq.gz
    ├── 59edf51fca7a9af264828a8b91bfbd29d73191bd.nq.gz
    ├── 5a5161967f29b14146a73577795b3aea27387073.nq.gz
    ├── 5ac3521105b47fa45b63af37a6c13415fb88ea60.nq.gz
    ├── 5bb3c72ae4711b997b173231509bd57befdcb592.nq.gz
    ├── 5c3f83ce4239e3f216ffbb7395bfa853d9cfd92b.nq.gz
    ├── 5c43dac5b7c117878a466ee5fa8d220ef7c177ab.nq.gz
    ├── 5c8db731c9475012c27cb2ca45e6b0ac93490cc3.nq.gz
    ├── 5cc1495816afd22e9e442ffc55e11641585fcf35.nq.gz
    ├── 5d313ad88e33cee7e473a3886b4409ace0e77588.nq.gz
    ├── 5da547c499eea5b8b91ab7f29d6752a376148a8a.nq.gz
    ├── 5f5c64f12f283464e8e77dc0455ee82d28d888e5.nq.gz
    ├── 5fd1ca84bd8066cc6225070c6fdbe179eb2d1a31.nq.gz
    ├── 602d65867ad484896bd0c68235f64060945d7883.nq.gz
    ├── 60f933d19393c0c6c7838fd1451b80823de613c7.nq.gz
    ├── 61a21d820b4c50b84eb70b070bc5bc49af9e436c.nq.gz
    └── 61e6e635fe148ab3125aba17a682dc7bdd1a974a.nq.gz

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

[shap/shap](https://github.com/shap/shap)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
