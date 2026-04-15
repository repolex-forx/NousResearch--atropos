# Repolex Knowledge Graph of NousResearch/atropos

RDF knowledge graph data for [NousResearch/atropos](https://github.com/NousResearch/atropos), parsed by [repolex](https://repolex.ai).

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
lexq download NousResearch/atropos
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8284a0b95c88f6f2930409fd948794eeb152f063
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8284a0b95c88f6f2930409fd948794eeb152f063.nq.gz
│   └── repolex
│       └── 8284a0b95c88f6f2930409fd948794eeb152f063
│           └── chunk-001.nq.gz
└── blob
    ├── 009130ae0337e5462fe9732663fa9e3056d05c3d.nq.gz
    ├── 00bf6eaa31b7ff4746ce2d333b8677bab48885f3.nq.gz
    ├── 0133795f641d359ba4ea7b312406ccf4c75c8be3.nq.gz
    ├── 0172328effd16b6eb094c794917386f920ed7ade.nq.gz
    ├── 021be8184e118e175defb66bd0cb4ba6bada9ac1.nq.gz
    ├── 02713f5ebb82b78dda66882bd4ebaa182b990843.nq.gz
    ├── 029321785caee990fc23f735f1dbc38aaa7b37b4.nq.gz
    ├── 03ad09ebc544072c173e63db422f07fd8ab2ffbc.nq.gz
    ├── 03fc511c09b01e3acdb571c749961b9e18eaba36.nq.gz
    ├── 043d190f5e00b4fbbe488ba77a834d6d62b88df1.nq.gz
    ├── 0449c940ff84ba4ad591ebf555fceb6aa765f03e.nq.gz
    ├── 04b5c7f7109aeecfe96187db9f08bb07cc6578fd.nq.gz
    ├── 0542a9e3c3ff6893023211cd2bc88c246a891223.nq.gz
    ├── 05d40302d4c378d445f18fdf800b394cdcae857a.nq.gz
    ├── 05f7b15334cd8026fcf5be723c9518e720ec9490.nq.gz
    ├── 0652b76285179cbbec78902618f293abefa5fdaf.nq.gz
    ├── 06ece2d374db4af6ca20157601abcce28c1e1d61.nq.gz
    ├── 07a1c141d73dc41085b48fce24bf08ad586de980.nq.gz
    ├── 0834c67e32abfe71d84dee4ab336c286654cebb8.nq.gz
    ├── 08be5228eeb5fbb4d654a3ecd172d389196bc955.nq.gz
    ├── 08d1e96ed82e98e9e289afd2e4cedae41257c630.nq.gz
    ├── 0a1c75d4220c12c03af0011dfde0edcc83a9a3bf.nq.gz
    ├── 0a9ac07dcf00381051fbd96127217bdf21d6c3ae.nq.gz
    ├── 0ad3042a2e01046b1abccb68da3fb4ec91991816.nq.gz
    ├── 0ba2364031e4bf2d82c48471d7ac0b8cfdee54cc.nq.gz
    ├── 0be3da689760d5eaf362f7466d2d6c809bca1f3c.nq.gz
    ├── 0c7cef28841d3d6b601d5cc4edd3c3eef89a8f66.nq.gz
    ├── 0ccd7a3d9e3155d27d4cfbad81d0ec349bed0e65.nq.gz
    ├── 0dcbad7a4ee3e35aeb28dfb9e6fca7a7e2ffb4f3.nq.gz
    ├── 0debd02f93d66d406cd3215b53dc65b2e8082951.nq.gz
    ├── 0e5e0a402789049dcc524fb34bbbd372c72ad770.nq.gz
    ├── 0e726f6891ac19b0ca7fd8eba5ee82268a794371.nq.gz
    ├── 0ea12acba7109ce611edbd8d07cbafb3309d9d90.nq.gz
    ├── 0f8f0a82906ede876e8c164fa1dcf34068b32a15.nq.gz
    ├── 108d8c0c70752567b06e8036c42067e494098a62.nq.gz
    ├── 11618659b8f6fe8c5b01630dd4bee680fcdcf9f0.nq.gz
    ├── 12d35a54bd0c2111bc5a848d6fdfe6cb25b0924a.nq.gz
    ├── 13673a18a0564c5986abd36b472d6fca51d5ec17.nq.gz
    ├── 13779ab922f86f1065eac2ee02f3cb28a6d7f6d8.nq.gz
    ├── 13dbff495539d5fa7f442ed2505abea319b5fb21.nq.gz
    ├── 144a9d81b601b016b77332b3065b6d15bdd06e31.nq.gz
    ├── 147a16ed3164eb04062bdf63d7dcd09677cab611.nq.gz
    ├── 14a37b69a5ccb64cec93088913ca51d58eb98efa.nq.gz
    ├── 14eda5c3c4f15c25c2027c8015863572cd09d062.nq.gz
    ├── 14f16a4f77ce407d9a97e8b51e4132ade2dbb7d6.nq.gz
    ├── 1515c78e446cafeed896ed9c03d8c73443ad2a91.nq.gz
    ├── 15452f24267f81ec05907036133cfa01942fd8a7.nq.gz
    ├── 16038d22469095669ccfd087b9753fb94d2daaad.nq.gz
    ├── 16d7b9fe5ae50330e6e058065f75dde60cbca797.nq.gz
    ├── 1774b948ad26424e94c9aeae6b4ee6355fbe400c.nq.gz
    ├── 1787c38b8cede0bcb074934a2de81215cd8f0a48.nq.gz
    ├── 1a0bc8e2d0d56b75715753319c4185a19d3bdad8.nq.gz
    ├── 1a226ff9f77cf695f38ea66a8dc4cc1bd5d3c5b5.nq.gz
    ├── 1a4cb66eb6833d5519cf79e9474342b2530670b0.nq.gz
    ├── 1a7ec4dbac1d6c1d3388003abbbaa8d6874b5c27.nq.gz
    ├── 1a84fbaa32ba6014f5d15610c049f7a43fee7ce9.nq.gz
    ├── 1b2d69fd2856456bd527f31e0ef05b871212d256.nq.gz
    ├── 1ba8994f9ff6ca99b9f40dd033cdd24861075aac.nq.gz
    ├── 1cfb96afeb0029e6c6bdfa6c7dae4e0b963120d6.nq.gz
    ├── 1d08c42501bcca414c6fc92333f1f22e986f6949.nq.gz
    ├── 1d430b2194a509b222f3b04148ca73b5007bc375.nq.gz
    ├── 1d54aaee2d40e524e12c2b0241c5be3aa6012768.nq.gz
    ├── 1e45bf14d853499f243b9301119d1418a73da443.nq.gz
    ├── 1ea3af052df380593a3a2a358e35c9fc22e9353e.nq.gz
    ├── 1eacdb8b74ffe4053b5359d784dbc60769cc9ac6.nq.gz
    ├── 1fa270500b0da01b8ed8f5dfe6cce10f58810a76.nq.gz
    ├── 206fa3bb6cd21dc0c0ba2b4fb853bb980994f63c.nq.gz
    ├── 20844ea25f11cc8a43bf93fa68bb0dd1a308ba6c.nq.gz
    ├── 21a59a513a9b38c1dac3f78ca4298d8d338af0a3.nq.gz
    ├── 21b4e3d0d6593850ed51c009199db71eea39a6f4.nq.gz
    ├── 223502e016c8ae8347d896d80a897f28f41b4212.nq.gz
    ├── 2246a1215377bd69615c6f067596977966afdcc2.nq.gz
    ├── 22494695fcf8e15d72856f0c46eee4d4a2e7fbad.nq.gz
    ├── 22706f0ae4b33efac1fcaff1e3eb5125cec3ca9f.nq.gz
    ├── 22f950ba58d9afcf79ab3d3647918620e7d9e7f5.nq.gz
    ├── 23548c73abb9b154fdc1e8d9a208e039f923f499.nq.gz
    ├── 2365dded907db6d9ede998b1a333c9641f9498fb.nq.gz
    ├── 23693f97c9290d32dc959c557e88990b79675cdd.nq.gz
    ├── 2383d7e9e8524233b8ba616dfb4380a48f522f7d.nq.gz
    ├── 23f3cb3d21d4258a8b45d15db8f9bb33f16c8825.nq.gz
    ├── 244861f8af6d2110df731af8177068598264aa3d.nq.gz
    ├── 2450f75bb084c139340d6c520736ee1099faef22.nq.gz
    ├── 25c0055182602c3b39260caa8de37cee75dc9b8c.nq.gz
    ├── 2643f580d14d4ae6bd46745a87277318aa0cfe69.nq.gz
    ├── 26c1928d743bd6e3b1d4c0dd3167758b99703aa9.nq.gz
    ├── 26c44e13214eefe410708da7761d424132e32912.nq.gz
    ├── 27189c2e2ec49f025558a17bee72f34e096b5fc3.nq.gz
    ├── 27358261273023eb40205ab6c4d6beee93bf5f00.nq.gz
    ├── 276a9a1991d8021b17b55a32c47cf9665dc1af0a.nq.gz
    ├── 27db2ee92a4293444a48a4e90fb4b305837f5048.nq.gz
    ├── 28c08fe1d910d645837c5743c44d5b7153a8be7c.nq.gz
    ├── 296563f767709bc44e0d0298c091ff0ce92877f2.nq.gz
    ├── 2a29e05abb5e481651d6bc2f3f3b7d69aa7fe9a3.nq.gz
    ├── 2a79aa495cd591cc62d8a9160bf06806391a39ed.nq.gz
    ├── 2ad260fd8ef234b1f449dc7e7c1e86988420851f.nq.gz
    ├── 2aea22fc14808c15a09c2f183664075164242fc0.nq.gz
    ├── 2b45e6016af550bbacd25e16f792e7a50ca28034.nq.gz
    ├── 2c9493b3dcea4d0f1d5c79e5b08cf6909bf47221.nq.gz
    ├── 2cab45688e70fe93f65d6ef7ed3c2802762fc2c6.nq.gz
    ├── 2e00dfe9ef74b2a02750784a3c8fa74989512254.nq.gz
    ├── 2e95d05a51232ecfbe248421d29888ed05746e80.nq.gz
    ├── 30403461e9481404f5aa296122d9f961c4316474.nq.gz
    ├── 313efdf7e65078e8dbc2e86b6658422b40369147.nq.gz
    ├── 31ea42a4b2829aa9594b4dca57ae508b9ed1f872.nq.gz
    ├── 32113d1849a0a1a10ee71eb4ed2ec7ce6064fe68.nq.gz
    ├── 3316e2c9f45c9ff3dd80a569860277b809975dfe.nq.gz
    ├── 33322262822b4f6c2402ba5459b619e6a55744e1.nq.gz
    ├── 342e62c12163de4931ff1f312a46e5c1387ec4a7.nq.gz
    ├── 364b8854cd56a1b1d8f1817fec2061c397a20b3e.nq.gz
    ├── 36fb5e3c922cc5cad223b4d805c993c84289d525.nq.gz
    ├── 371e937b7d816ffed9d7d135c3ef8b164e6200b5.nq.gz
    ├── 372c5a3eb9d566cedc8d228535d3a382624384aa.nq.gz
    ├── 381566730b46b51b13ee0318593d15570c41040d.nq.gz
    ├── 382731531f4d3bc47d26801f90aebb230d939402.nq.gz
    ├── 382959bcd75abe16c8de0e20df74955692ff46d4.nq.gz
    ├── 3861587e9cc531e7739ab8211b677c51e7456799.nq.gz
    ├── 38fb420bfd32e1fcf495d7ee60700080c111519a.nq.gz
    ├── 393a75229cf946c220f5a466cca3795e17fa0d7c.nq.gz
    ├── 395fe610be75cde874fedc833c74630ce1ff9283.nq.gz
    ├── 396bfae41b77d831a025d4dca9a792fc2744c8e4.nq.gz
    ├── 3a0a9b158bee321dba66769bcec40e34fb06941d.nq.gz
    ├── 3a34198bf41144b476fd54a7f4e0c437c324d6c3.nq.gz
    ├── 3a42712110c0f98e9c103bb917bdd33675278813.nq.gz
    ├── 3bc4636ba5975209b61dfdebb28087113322691a.nq.gz
    ├── 3c765c72193163c09ba0c6e86fa295bdcf3986f4.nq.gz
    ├── 3cdafc017ac3539ee15a4a24bad1214b6da30cc2.nq.gz
    ├── 3d14102c65343fb2628a47718196b4562f8e4ee6.nq.gz
    ├── 3db9d5816f2b993bad927a40aff266f31d3b94c4.nq.gz
    ├── 3e59827d04f9495ad3b279938876f0e1133121d7.nq.gz
    ├── 3f16b88394b0286529f64b5e5f08411b32ae9864.nq.gz
    ├── 3fbbc94e57fb37b36c2e0daa7cb013e54e45a7f5.nq.gz
    ├── 3ffcbfea92fc34598dad440048c910f3d80051be.nq.gz
    ├── 400ee761e5937f95e2d059e6e82dec614b79a1ad.nq.gz
    ├── 402982439bc868b71e82c8e29887b8442ff37d54.nq.gz
    ├── 403d558cc3981e79d6e7271b5cfe9f3e3c72914d.nq.gz
    ├── 40d069a862288a5ecea0e4f1404b63a9d6f662a4.nq.gz
    ├── 41034bea72b2f3f86e0e2f7dc711578f1a27f268.nq.gz
    ├── 411d614906a93f4591250281b93703feea735ca0.nq.gz
    ├── 413e7ada97a700833e5f315f69a0605f3527a201.nq.gz
    ├── 4174d8eadb9e4a7961dad6fc0bb5099f6d0afb76.nq.gz
    ├── 419aea03bcec9d0e1ded8d538927785c5db503fe.nq.gz
    ├── 41b7300003ca8a6cfea89721629017129a22accd.nq.gz
    ├── 434da0296bac19a64ba0a3397f408347fc6cd84b.nq.gz
    ├── 43f9526774fee3eae72aaced7606cc95b6eae93f.nq.gz
    ├── 43fe81ac95cff63b48b1b5118682fe3f66dc0275.nq.gz
    ├── 447013b46d8df16b4ece479071d7ccba31a2d202.nq.gz
    ├── 44859132f003dc2f9e0c845a7f60cf362e1ffe9c.nq.gz
    ├── 470cb978590631cf7d7e58a02b295292de9ee403.nq.gz
    ├── 479f82492333345f61ae23c65004a37c2fc3181a.nq.gz
    ├── 4ad9368a87a2dd13af2d06139b5c7d19e453a82e.nq.gz
    ├── 4affb1a07830266384d2d32ede3b97d70b222e23.nq.gz
    ├── 4ba690f5b3accbfb5a4e258d2bd323aa39878e1d.nq.gz
    ├── 4c279b8679b347eadd2fddc80be6b09d68d774ab.nq.gz
    ├── 4c3fdb3654dc9b1eb724f9c18a539de77c0a0780.nq.gz
    ├── 4c53f16893107d2341c7780eddefc01dfa79f1df.nq.gz
    ├── 4dec37a511d4dafd65fcf9211ebaeba9e699da2e.nq.gz
    ├── 4e4576dc89e063cdbdfe6fdb786b83dedd766598.nq.gz
    ├── 4e96ce24ce10f8e7a4687c58f6287977f8c62e10.nq.gz
    ├── 4f3ee071a342d55e2583fadbab6da03509bb57bc.nq.gz
    ├── 4f7de5bb2c4b971d81c4d6c373359c2b78b311df.nq.gz
    ├── 4f98bd9fee1897857d389989e7e21d1fda634cdb.nq.gz
    ├── 4fae379ecc7c578e9dbeabd74632465988e911f7.nq.gz
    ├── 501013a6c0f2a8eddc6f1375e4cb6fffefaf18c2.nq.gz
    ├── 504d3ac266b924e9f9c5d3870b9c9d820c2696b5.nq.gz
    ├── 518316fa644957dff590d4ab162f6dc30b41daf0.nq.gz
    ├── 51edcf6d9fc0a89ee58f3509f22baf0ad56777bd.nq.gz
    ├── 529e2ae0f7bdb77618476e439df969edec2faac7.nq.gz
    ├── 5434f0e563a4dd1de1f3469c3b4e4bd5a3e55de6.nq.gz
    ├── 545ad9faa869979e49981308cf43b3b7d801e629.nq.gz
    ├── 552c86fc43d443a2c52f509d023912c81b124be2.nq.gz
    ├── 55ad9ff5d8ad6f3668487e2d3cd431b1d8cee548.nq.gz
    ├── 561444771a831556c02ceb4b4bfc4437cc6626f8.nq.gz
    ├── 56f23075f4002a305b07a4e0f78a164f78272b07.nq.gz
    ├── 573d049e2c7719ba6d0d5bc00becd84d9a46370d.nq.gz
    ├── 5839b38dd87ed0ba61e0fe48ac834b02b83b4720.nq.gz
    ├── 584b778563aaa923f9fc4bc863fa560db850c0f8.nq.gz
    ├── 5898bba0247e2385f784c25895ad76d2f4621e59.nq.gz
    ├── 58b1f1cb167640a3ee56db59e718bbaadbed6ed8.nq.gz
    ├── 592955a6fbb90de41d58d62ea0f520510acbab55.nq.gz
    ├── 59b9075b4b26231246e207025a8643af04060a90.nq.gz
    ├── 59c42a78f7aed5581d7a304519ddcf2c509851de.nq.gz
    ├── 5a475e5fd7b15eff42c9982cf5f8ede1357f0543.nq.gz
    ├── 5a5a1f9a19db224dda0aa161b4809ec4fc6fdb6d.nq.gz
    ├── 5b486859b23fe4e3863d1b4d17ae4e8e14cf5a96.nq.gz
    ├── 5b9230d7b3ffde4f96a504536c63df8b56fe462d.nq.gz
    ├── 5bc945ee9fb628ed720606b5c66221c482a1bb4a.nq.gz
    ├── 5c0e05503f6b2e723c1b60ccfd1107f125543cbc.nq.gz
    ├── 5d40861459fc2b31468acf74178724b059e5ad64.nq.gz
    ├── 5d6c29fa72eb57ac4b35b48839e6fe45827908a6.nq.gz
    ├── 5d85d6566f88d21b63b89340ebe8d31e47afd90a.nq.gz
    ├── 5db8a762e7acacc4ba8fc8b34f18d5fe94e13e0e.nq.gz
    ├── 5decacb5cb334657ad98ef25e1e1c80354cc94bf.nq.gz
    ├── 5e54dbd5c53ad1da521b6f38dac64d7a620ef63d.nq.gz
    ├── 5f6a37d096310363329254d70bd698be7297cf5e.nq.gz
    ├── 6003fe3974d589f44e3b8c3778f752864cb5fafe.nq.gz
    ├── 60937a09c9288d3541da26e7b3a31edfafd0689a.nq.gz
    └── 635837e94b4e7580f353fe67f46cd333f29b9cde.nq.gz

8 directories, 200 files
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

[NousResearch/atropos](https://github.com/NousResearch/atropos)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
