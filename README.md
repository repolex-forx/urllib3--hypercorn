# Repolex Knowledge Graph of urllib3/hypercorn

RDF knowledge graph data for [urllib3/hypercorn](https://github.com/urllib3/hypercorn), parsed by [repolex](https://repolex.ai).

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
rlex download urllib3/hypercorn
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 33ed00670894b29ec00f4341a4ec5100e3ade747
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 33ed00670894b29ec00f4341a4ec5100e3ade747
│           └── chunk-001.nq.gz
├── blob
│   ├── 009541bf1d908b2a3f52ce895f8f465f59a487a7.nq.gz
│   ├── 025ec0a0a70b0193f5d070708e2390e2d773f872.nq.gz
│   ├── 044ff852ed31827a64d97e2d474d71c282df0930.nq.gz
│   ├── 0ff2abf6ce8e2cf178d940511b3f8670a0774ce0.nq.gz
│   ├── 1299a776b71b7936960a6157cc4202518b01ceb3.nq.gz
│   ├── 1c3d7a28afbc5e810518e342848039c0613e3c2c.nq.gz
│   ├── 1d22ea2078ce33f48a1da7e64ace21a4ab494f36.nq.gz
│   ├── 237884156ce9ae7067f0c1617a72ddd8812b0987.nq.gz
│   ├── 244950c6d449f45ccbb103238180bca390b46849.nq.gz
│   ├── 24af59693d00380e8ce34ff1b1cb296788ff50dc.nq.gz
│   ├── 26607ba73e5da8f99a9cbc4ca37b03efe18c1457.nq.gz
│   ├── 269c4e4dfe13fcea91b2620e276603f607523ead.nq.gz
│   ├── 26f50f0011a72630d345044cad3fd374571feab0.nq.gz
│   ├── 287cd06da7a8e83841f5fec34d612deb16727e64.nq.gz
│   ├── 2e589035534b8c29d7d85c44729d7c70884d1d89.nq.gz
│   ├── 3356b864dc22f70baacb0570b02c94b52c2ccbee.nq.gz
│   ├── 339bcd216afb1e2205030f1c6b26512924af943c.nq.gz
│   ├── 3423d8f8b22474fe30c2dfb8e7d1437ae99f5ce0.nq.gz
│   ├── 3567cd6aa970896066f27c8db2764b68a0c584c9.nq.gz
│   ├── 358ba98739454bff6fee1535af3f33aa2e22316a.nq.gz
│   ├── 36cfdeb20200a051e9c22592b0a1f84317454547.nq.gz
│   ├── 374f4f9200eab58d53be4701af15bf401dc9b0c7.nq.gz
│   ├── 3755da0f02567562d73e6d26409048c4a64002a0.nq.gz
│   ├── 3828e37b269a34b205bb902d139ef2263c3b21bd.nq.gz
│   ├── 39385681593c5da57a63fcddf3e223a23b27f9f6.nq.gz
│   ├── 396d89090ff59564a2dedfc66b3d4e0591d37fca.nq.gz
│   ├── 3c3a4335e7909f1c898143ece3494187a1ab59ba.nq.gz
│   ├── 3c676b91d0cfc403e507a72a15120963c3564e5f.nq.gz
│   ├── 3d16e54d86c06ec16a95fa5115c083a6205c6668.nq.gz
│   ├── 44a2eb9ddab4c3a81513bbb6fb41b4edbfa00606.nq.gz
│   ├── 45b063e178284b765baca0d57422b9eec2e1e183.nq.gz
│   ├── 477453834800189b32c997ec6a5ce45084f6c4af.nq.gz
│   ├── 47f7185fe7a91f0d46c6b850b96c9e559208a90b.nq.gz
│   ├── 49f8b179c32208719826de06c17b68c669bf943d.nq.gz
│   ├── 4f3b416b306f145f44119832fd848e8ececb814e.nq.gz
│   ├── 509e1c2ded9c6d93c2f4fadb5a417cd96f664aec.nq.gz
│   ├── 52d6cd4963c6a1677d2ef0557e34449476f269d2.nq.gz
│   ├── 542b28feb63db7fed6101d251f99021d66497270.nq.gz
│   ├── 55350efbdf3d9f0b3abd814d8e25d573fe24dac2.nq.gz
│   ├── 55846288788c866645e8a6f33f554362b80b681c.nq.gz
│   ├── 558ddb4b9b7c0bb84cebb622b161c7e0e21f49e9.nq.gz
│   ├── 5629ff719356c971b05b55c6dcf2fd765919a7fa.nq.gz
│   ├── 5931e8c8b75d1d1624b5605283d6232b0bc68cb1.nq.gz
│   ├── 5e011a7c94fea00eeed81586d87ab4ce55363478.nq.gz
│   ├── 5f0ccfa965d147fd1f0d92b0db156b5ad5811efc.nq.gz
│   ├── 5f595828d946be66766c8462e61c89d4aefe66cc.nq.gz
│   ├── 629ab9f4559fdcc4d66ca7716c0eb5bcb53b6c5f.nq.gz
│   ├── 632161a629c9db2ce40804eef8c93f8cb0f136b2.nq.gz
│   ├── 6947dcd4a41652417ed485f90ffdd3c7319cceb6.nq.gz
│   ├── 69d80c3659ef840cd2bdc885c7a338e2874bcd39.nq.gz
│   ├── 6a7b8db00105852a43318e229c2a63e8ab3c4614.nq.gz
│   ├── 6b357f8f215c497d6134b86e989a8fe27fa49ba4.nq.gz
│   ├── 6e76d4935ab4e3eedf85050375707874e4bede0a.nq.gz
│   ├── 6ff422fbb83599f4b049a0759837f87b9e0d60e9.nq.gz
│   ├── 769e014be517953625e039096b43ac05a30521b1.nq.gz
│   ├── 7ae0e6856c0cac80a5b1c3b386405bcf59f40c14.nq.gz
│   ├── 7cf5f53772c4a8b61a20f14af38c227895fe0603.nq.gz
│   ├── 7da355bafa1e199e214264da9647188d4a1e0fcd.nq.gz
│   ├── 83ea29c7b1243b51d8a0328fc59a630e35824b8a.nq.gz
│   ├── 86bb00a4c73b9a45ceeba6354e4f92617e6d819a.nq.gz
│   ├── 87d7d45ae505825b12f6dad7e78961e5f7dabf03.nq.gz
│   ├── 88d9a4d335276fd64ab239f33dda76a03b11b94d.nq.gz
│   ├── 8a5dad99833445d87066b166b9aa87f6b60cce90.nq.gz
│   ├── 8e4f61b8daef597be728e02381dd323eb6b6f082.nq.gz
│   ├── 8ef153fe7daf3d25a4f4ef596c4aaae25ca6b1c5.nq.gz
│   ├── 9011999e41d74134ba3a8b59a8a32ffae05bef27.nq.gz
│   ├── 904872de60e64007298304dee6ec6cb1df827b56.nq.gz
│   ├── 94c3fcd662c580576260d78d642eb099a8ba029f.nq.gz
│   ├── 94f1262a579c558bab1a47bb83cb50b34e2845df.nq.gz
│   ├── 98808e91d51bb98be81c3bba58c94ea239b835bf.nq.gz
│   ├── 9cd764729417cb780f8a6384113c7fd0ab9f28e3.nq.gz
│   ├── 9e16e079723887286393a847ddcd26c07ef60aca.nq.gz
│   ├── a0994591b775c2994a6fbb0b382aa0b24a79ee51.nq.gz
│   ├── a45fc528c391def363c842f3dc57b8e56a45f86f.nq.gz
│   ├── a4880c07ec70056b56e0d43278747671d02751da.nq.gz
│   ├── a620dfa93a3745ff6ec5495b6e418f890285b773.nq.gz
│   ├── a6d2fb080f960e8701b73aa65169990155cc3042.nq.gz
│   ├── ab9ef2ec96db13a66db8bcf0dd5421633fe09508.nq.gz
│   ├── afe00c20e2d456a690e25673fac1a39c5a48c98d.nq.gz
│   ├── b3dc0e80f889b57189e78d00f908a457a3fc22e3.nq.gz
│   ├── b7b1e75f5c4d00ef3a42585b7afc67b4103f14ec.nq.gz
│   ├── b8d4530b9428b0bf34556445476ad919096ea7cf.nq.gz
│   ├── bb7b58970217081f5be8a8b8878bd6992cd0a9c3.nq.gz
│   ├── bccdd54181cc4279d194bdbb116789dee8412034.nq.gz
│   ├── bcfa1a51d8a666438d030a4033c8c73387f84687.nq.gz
│   ├── c44f39ae86a0e3bb34dd7cb710453e2828288e2c.nq.gz
│   ├── c59a395bdaabfb027392c373e28d4b00d3bb2632.nq.gz
│   ├── c6c0fc4eef8f757f635a1ee985b2950c539d4e75.nq.gz
│   ├── cd2cafaa35a535451b1e7aed1b24f83667dfa9e1.nq.gz
│   ├── d244e7c3a0048ee5bdb1cd9af79d177fc9a66428.nq.gz
│   ├── d30d82db313b1dfce5b1280c76e448f3be2e21bf.nq.gz
│   ├── d8721bbb03e039c1002d0c23104e149ab54a95ae.nq.gz
│   ├── d8ac0f86147b077136e0615e5b0abd4537beecdd.nq.gz
│   ├── d91d203fe11f4a369cb3aec1a6eb3106fbee6b0e.nq.gz
│   ├── d9b8901a52e994f07d87ad35bd999c69bdcddf5b.nq.gz
│   ├── db041768f232f35e77f33f1b8a32b1d5216d936e.nq.gz
│   ├── dbcc7a12981beaf54671f9f477887aae02ebcbbf.nq.gz
│   ├── dd8ab7754b7efda9e88ef61a87e117bf0b7789f9.nq.gz
│   ├── df0e60d46b8931d6492cc72fcda0a976cde0dbcc.nq.gz
│   ├── dfb509c00c04e3638971449ba238c6fe53f2a3a8.nq.gz
│   ├── e18836c1cf5f028695f08de05f41d0708e1668d9.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73ea91cc2db4fd9a1a7f13958c60c7d2c6a2c48.nq.gz
│   ├── e829616a139f09cc3e623191aee17bb55c29f25d.nq.gz
│   ├── e9cb0a0f7eb236f3171f832e81437b2588d74434.nq.gz
│   ├── e9d8f83656052d903b0cd41f844bfbf5b1a3059d.nq.gz
│   ├── ee2d2b735d19a75d7d994fe0a6003ede0fe2283a.nq.gz
│   ├── f24b3462146cdc809a301167b988237542dc179e.nq.gz
│   ├── f25c3f1a6f17a6a8b7ce870b67e2806e94ed25ac.nq.gz
│   ├── f34cbf77223aa301b4b167a3448e32a9fe32e7e2.nq.gz
│   ├── f5642f79f21d872f010979dcf6f0c4a415acc19d.nq.gz
│   ├── f782757a99b054f33be6e6e995bedb3f3cfd1581.nq.gz
│   ├── fa019bba7119cb0a76c8606d8dd87b96e243a4cb.nq.gz
│   ├── fd1ca24b23f425848b7d9bbb4b21645143f9531d.nq.gz
│   ├── fe758b5fad79b18c97b0d62ce85c78dbbf94657f.nq.gz
│   └── fe9ad1c74071ee3d971ab5e14b1b62264c291f06.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 33ed00670894b29ec00f4341a4ec5100e3ade747.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 123 files
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

[urllib3/hypercorn](https://github.com/urllib3/hypercorn)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
