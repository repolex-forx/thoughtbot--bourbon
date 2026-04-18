# Repolex Knowledge Graph of thoughtbot/bourbon

RDF knowledge graph data for [thoughtbot/bourbon](https://github.com/thoughtbot/bourbon), parsed by [repolex](https://repolex.ai).

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
lexq download thoughtbot/bourbon
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c3551e46f41738681216a7f957bc88bc79155b16
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── c3551e46f41738681216a7f957bc88bc79155b16.nq.gz
│   └── repolex
│       └── c3551e46f41738681216a7f957bc88bc79155b16
│           └── chunk-001.nq.gz
├── blob
│   ├── 00e6b4f0c7226ccd51149fac58e9c72b18478cf5.nq.gz
│   ├── 010336bf549ada477078043e658f69d1e397cfcd.nq.gz
│   ├── 01e18f56fa76e2be2757c17d7b6f82f8da84499f.nq.gz
│   ├── 0220fb32ce1c4c42f14a65767fc8ccf1504d67f2.nq.gz
│   ├── 035e516a912a029b721d0d87cfd02f829ed97e2c.nq.gz
│   ├── 0369551bedf4425c3893fccb8f3452ae4ebd8fce.nq.gz
│   ├── 0468a8af15a4d52266f9c6757504c4b9769fa0e2.nq.gz
│   ├── 0494a6eb0922aaa4e34cb3dcb8a553daf1ffae34.nq.gz
│   ├── 07604666542371cf5ae687e94aac211fd616b1d5.nq.gz
│   ├── 0cf132624d58bee33cea6fedcaad33925a3672c4.nq.gz
│   ├── 0ef194db77499df2cfb6a277646797cccc23feeb.nq.gz
│   ├── 10474b0aea7bcce59e3d4a79010716c6dd8ade40.nq.gz
│   ├── 178174a3872d52f3bd9684f1a1e8b4d8e505f65c.nq.gz
│   ├── 17a4f92d0f928559316613a752eea3b602169d75.nq.gz
│   ├── 193f3299b4a09034330df084cbd8c4a54e77c2f8.nq.gz
│   ├── 19814162fcafcfa1c25cb7064f4d85ad173a9597.nq.gz
│   ├── 19bc066f3c38b5d4fffe1ae14e73f4f404192f62.nq.gz
│   ├── 1ba65ce1525ef2c7f3b152e9be31f57540fef38f.nq.gz
│   ├── 1ba822ca9a4e7cae2aef0ff500ab6adc9674808d.nq.gz
│   ├── 1ca072011fa00d1df7dd9d6bc3e9f9440a07f7ae.nq.gz
│   ├── 1e1ec7218c716717442e1e2d6642451d2e8f1b26.nq.gz
│   ├── 209b9af758d88d6b4e16a910bbe3b43892e4d667.nq.gz
│   ├── 222f2740c4059853ae320826acd1170e03b7b10c.nq.gz
│   ├── 26e2349fe72e920adbf3c2c545fa4d937cbef785.nq.gz
│   ├── 27a9d8b62d0f45a3d3bdc88612e316cf2ad24d18.nq.gz
│   ├── 2926c93623732b6a995a88ca67fbd88b5d39cdb3.nq.gz
│   ├── 29fa7abbb8a61b56653136f00a53cd544b9a74e3.nq.gz
│   ├── 2ac4cf52edf0712922b6e3770f9f3fb442ce22fa.nq.gz
│   ├── 2b50258655c9c6438284982e1c425c855f12cd7f.nq.gz
│   ├── 2b5b293ce6700fc71034619875059cbb3e61c91b.nq.gz
│   ├── 2cb0beaaf04c5f4014bac5e51085859b1da539f9.nq.gz
│   ├── 2e845f762f0ca32cf9e53dfe9abe9d8c5543d83d.nq.gz
│   ├── 3161757c197440e94d3a4bea195ffc632c08b4d1.nq.gz
│   ├── 3171f405aacba734da23aec5e3c845d24f89d281.nq.gz
│   ├── 33b3e8cd265966f1488f062c3c54f58e6c3f6968.nq.gz
│   ├── 33e80a07381f5d4219e34d5efab6eaf591db3626.nq.gz
│   ├── 36fa0864f1b1f37c0cdaddfe3da9d708e3503ca0.nq.gz
│   ├── 374ed8dede30178da5b019dc3b4765ffc13e0778.nq.gz
│   ├── 37ad7a58456ff6872e08bc052d45dc1165189557.nq.gz
│   ├── 37b3d06376fc835a854a4ef7b574828eb76a7015.nq.gz
│   ├── 38cf2bb7e9be4fb31b29b19df3f77229ddb62e5d.nq.gz
│   ├── 38d263df7fff2d5596669d199640c3349e02b5e8.nq.gz
│   ├── 3a0cc63930929def54fb0e9fec9dd40ae5a51adb.nq.gz
│   ├── 3e5145b127b1c9d59520edc683c968c79e68ab4d.nq.gz
│   ├── 3fce348b687ef1165e2798b6e1fedbd4c72722c3.nq.gz
│   ├── 3fe07d5e135cf6aa092eee2bcd78ea5ad4721639.nq.gz
│   ├── 43eb6cbf0e87e3db9701e49ce18c900c27bac7aa.nq.gz
│   ├── 44c41c7b73eeeeb00aca4abdb28d03a6fbea364e.nq.gz
│   ├── 44ce493ad826e46e519ae283a332921095deaf32.nq.gz
│   ├── 4501e588aea19a25751099804693228803fcb9e8.nq.gz
│   ├── 4545be319ecc615d6470438dfcb8c9d348fdb84e.nq.gz
│   ├── 479326ad87009aa69668e240285a9156e42f9615.nq.gz
│   ├── 4ca228378ca32eaa8319d2521d47245bc9ab0361.nq.gz
│   ├── 4d092c70b64a2aebe30ca442f93db3171cf193b7.nq.gz
│   ├── 4d8aa16b9e0df95e145dcc3eb87e9aa3089e683c.nq.gz
│   ├── 4dae354ef18b8b9654817f665011124c0942770a.nq.gz
│   ├── 4e7d4a9884278ad28de91eac1e4ea6900d66e95e.nq.gz
│   ├── 5009b313bff37397d9ff1c42a0e4fd1480ba57c7.nq.gz
│   ├── 529c738d6852e7d18e402214fca23b4634befb3c.nq.gz
│   ├── 52ab34c1113e9f35d0cadc6b35e16a7288b59b75.nq.gz
│   ├── 53186a5c9ec9e33ff152c6c7b525fcd5159279e1.nq.gz
│   ├── 54146d3b0220bc6021f4a06a3360e7c793946954.nq.gz
│   ├── 54edcb55c9c9dafcdaca9a80c2f6cbeb96ca2d7e.nq.gz
│   ├── 5725fd497d6de0662d82ee35e021e56e8bd3b776.nq.gz
│   ├── 57af8b8c85b3ac8c5dfc665e6db7497f0ee0489a.nq.gz
│   ├── 58fec2b9aeea1c1c24ef1b6ed33ebfe41c980273.nq.gz
│   ├── 5bf03ddc9d35400332d1d6d77dd7be03d29c48cd.nq.gz
│   ├── 5c0783a4ba38da193450860696dd3a5205b8f273.nq.gz
│   ├── 5d39a713c288479514d7da8b06f05eb0bd155948.nq.gz
│   ├── 62fe264c98dbd1a5d86ed67f870cefe744e8fbf0.nq.gz
│   ├── 6443bccc518fe02cadae9bf7edc1567edda7dbc6.nq.gz
│   ├── 645bc1bd93873bfc9cf6dc59faf7c7223365b907.nq.gz
│   ├── 65c9f5699f7f13756751039f58cf5a0439ba3c7b.nq.gz
│   ├── 6a4d148f476008b3c76920c00cc7ce5f11ceac9f.nq.gz
│   ├── 6b53560e0f961d46ad72c9085f1ebffb85c2c8e6.nq.gz
│   ├── 6d3e5c63d57ca63f6e5a95a2a7b62fb2c04ae1cb.nq.gz
│   ├── 6eb886732a2f06c1fcf256c2d824b020799b0765.nq.gz
│   ├── 6ed32a1c3880e13b575fb2c0edb3e4eb6e69dc63.nq.gz
│   ├── 73e9182cdf228ecaed00a440406e2bf7e2c7218e.nq.gz
│   ├── 7814ae8d27f7794eea883a2495c2e13ba5fc7ddb.nq.gz
│   ├── 78691023ac9be8428e835e99796d62a49dda07c9.nq.gz
│   ├── 79209381486b9d88b28b88a948e08aa1a2eec424.nq.gz
│   ├── 7d401bb7d4812f9bcb50d13e46ee1818e2ff419f.nq.gz
│   ├── 7f715d79f7cd01c4096116408fd4187fa76456dd.nq.gz
│   ├── 81f2ab9a0cc965f15de6eec19c8bc9002bef39c1.nq.gz
│   ├── 834acbf39112e6e752ff472b781938d573a372f9.nq.gz
│   ├── 84f86e2523e2f0fba910e2b20c9f80bd82e33acc.nq.gz
│   ├── 86ed5aaf6864ad412d2ca2354631ce2247020746.nq.gz
│   ├── 8aab1dc2875ab28165e51d54499c8d0c58196300.nq.gz
│   ├── 8cc9b4ef31ed24b27a7d8299f5677b330c1645a4.nq.gz
│   ├── 8e9546e9249f6884d87db43bba179864f56fad6c.nq.gz
│   ├── 9078f61361d58be1068069c9932dbb64774c2192.nq.gz
│   ├── 93e14264e3383e680c1fd99a87139b185c6cb9f1.nq.gz
│   ├── 9447d35e1390d153b95d59d44baf2ef2a36dd63d.nq.gz
│   ├── 972e242363c1e57c7c145849025f5ecc9f50176c.nq.gz
│   ├── 97910a1b1719d1910bbf590b2667e3585a7e0396.nq.gz
│   ├── 98a98dba1cc7fef64c9e17261ad0b5e90cc4dc79.nq.gz
│   ├── 99d49754557c1f2a8f870169cc03f96a614f86cd.nq.gz
│   ├── 9d6e9eac0bdb7e16158c4214e754dba176bde459.nq.gz
│   ├── a03485dbcdf95ddf4357d32211b161e6e9533b6c.nq.gz
│   ├── a2929044ba795acf5ac28f684c5f738a428a9bc7.nq.gz
│   ├── a64e4b88692df5555378f56310d777a80b398322.nq.gz
│   ├── a684586955331490bdffe04dabce075567699d1d.nq.gz
│   ├── a6e9868686b5da6f4c7fcd3852b7779151aa6b32.nq.gz
│   ├── a95c8140c84bb656ec954551cd14371be3fefd8c.nq.gz
│   ├── ab1d26f4c27b91d3154d6846485ea216a67d4daf.nq.gz
│   ├── ad28e5a5f03506040f416603bedac716ab6db939.nq.gz
│   ├── b010cb64c9df02cd4c1f3b0e631b6bf87a7de8e2.nq.gz
│   ├── b1b610c9dec054a23944b52409f6b75accc46b59.nq.gz
│   ├── b29492703d51d633ea555643722a1b5af38c9339.nq.gz
│   ├── b38efdb48b7e3211c8ecc7eeff14d914bc913206.nq.gz
│   ├── b4e2a20bb6069d33479542fc863e7e36810e0f01.nq.gz
│   ├── b6e4366c1394b9af1efa009c8e232819a5016c2e.nq.gz
│   ├── b86f0158acac44203f05152d51bc260024bc869c.nq.gz
│   ├── b8a8659afaaf805662610e1cb95ad8f09d121510.nq.gz
│   ├── ba5a3303da2389a4dd382574fd3d66c7902c4e35.nq.gz
│   ├── bc8c153717f16bc9b2b97abc009cbede179693e2.nq.gz
│   ├── bce651d24d3917ac855b92696136acb7e3ba0129.nq.gz
│   ├── bd7845537c395f8c60a0b6a6140985c9ee90eb45.nq.gz
│   ├── bd825b67e8667f344087a22ced6d0aa56452580f.nq.gz
│   ├── bfc3964303114d5fbd9572351e155ece203a6c8c.nq.gz
│   ├── c2036f5b581d456d6a7f4634b7f931b4a2733c3e.nq.gz
│   ├── c22188232204725b19eea1766f4d6c7c0eadaac3.nq.gz
│   ├── c36979356c77393637eee73699033e30a2c815c6.nq.gz
│   ├── c58492514158a66445e9b603459aa1dac4fe19d3.nq.gz
│   ├── c5ba20f596fe328e187288454419aaa3d911add8.nq.gz
│   ├── c700b3fc9fdb37a460a2016da57e6917d1b6d9d0.nq.gz
│   ├── c90f36ea0b20d410ff7e4993248a99410ecb88b3.nq.gz
│   ├── c9ef892914fc009fb4964d9dae8c8b6740f77437.nq.gz
│   ├── ca610b15472fdf20f93011f973bec6967a3a47ca.nq.gz
│   ├── cd4ff79b363590656d65f90331a4f7b269a62900.nq.gz
│   ├── cde6e23f524575216d0f938d81eb57cf2c5b59e6.nq.gz
│   ├── d0fa08c44eec60596d016c3da9491ad8794cf4f9.nq.gz
│   ├── d318ff991881d7354be6250eaca32a032cf002a1.nq.gz
│   ├── d5616976e5b48b6d61c0b55ff8b3be064f314fb1.nq.gz
│   ├── d8265f9f43d99361932ebf78f331687e4aaaabae.nq.gz
│   ├── d8ccc42114b8b0fa43a27beb2d1856484d3b193b.nq.gz
│   ├── dca42f994a09a14d4df2627b731a8906cd961438.nq.gz
│   ├── de25d17a78e75cfe3420d54f781d3ee74ce44e9c.nq.gz
│   ├── de7135dbbc4f0583d6f067e0ea269d298dc2a45a.nq.gz
│   ├── dfebb79d5fb2cf42cecb3101463df0a85e5d97fc.nq.gz
│   ├── e1676ba191418db267d3036a7eb02f5bb4ac4b18.nq.gz
│   ├── e1756bb5b8615cd085402f440c831fd5b416b65e.nq.gz
│   ├── e2538f8a6a4c4231be486b3ebb035c6b25886afb.nq.gz
│   ├── e37455373fda41fa4676eaf061474188edfb763d.nq.gz
│   ├── e51f3b5af6bcc7d6bbb6f6e5354e9d888b0c8f60.nq.gz
│   ├── e640eb88b1b8c7efa1341ee762ea95f658b431a7.nq.gz
│   ├── e9ee0f929b94771d9a8f1f940a725c955482b362.nq.gz
│   ├── eb40a3477746e564560874d3088db3317f97e6c9.nq.gz
│   ├── ef3c9e514bc57ec518d25c55f195d544280cbdba.nq.gz
│   ├── f11495c7fc8325a533ba208a9a97622f64e91145.nq.gz
│   ├── f202f34ab24d8dd5a047313cc751a81b7d7b9872.nq.gz
│   ├── f2447aa3ad5301d97a09664938852f8103cfadc6.nq.gz
│   ├── f4f660a35bec04fe6401a49690554af5b07b57da.nq.gz
│   ├── f79aab7faf9e8ae6ac410ccb00101bb688d41194.nq.gz
│   ├── f9183a29ff2b02a681461a355fbef4a96cdf594f.nq.gz
│   ├── fa40e74f693ea010dccfc4740af8a1d256c79c9d.nq.gz
│   ├── fa6e62370fd97a53d8cb70f488aa51c15eaebe25.nq.gz
│   ├── fa98841f651a1879fffbef07f9c356e44aee00a6.nq.gz
│   ├── fab17c2557092b2d18aacb37bf95d9e62ecada2c.nq.gz
│   └── fcab4b0af5a45206d4a1f99f3118c971dc5455de.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── c3551e46f41738681216a7f957bc88bc79155b16.nq.gz
├── filetree
│   └── c3551e46f41738681216a7f957bc88bc79155b16.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 171 files
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

[thoughtbot/bourbon](https://github.com/thoughtbot/bourbon)

---
*Parsed on 2026-04-18 by [repolex](https://repolex.ai)*
