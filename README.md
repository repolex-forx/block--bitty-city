# Repolex Knowledge Graph of block/bitty-city

RDF knowledge graph data for [block/bitty-city](https://github.com/block/bitty-city), parsed by [repolex](https://repolex.ai).

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
rlex download block/bitty-city
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── da450e32f14d117e43c23c0de6e94d2823521798
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── da450e32f14d117e43c23c0de6e94d2823521798.nq.gz
│   └── repolex
│       └── da450e32f14d117e43c23c0de6e94d2823521798
│           └── chunk-001.nq.gz
└── blob
    ├── 0079b7126b811d35006fecd71e7c59680230bb59.nq.gz
    ├── 01c39d01b6c00e0cd79fad4a25857086b1b86188.nq.gz
    ├── 01f4658b3fe8979d326e1e4de826e9218bbdfa78.nq.gz
    ├── 0342f21878388a75ac2020d935fc86fdf206614b.nq.gz
    ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
    ├── 0416ea9b603815c24f8604b98cc8edc638d226ce.nq.gz
    ├── 04786f54b3e985434a4bf555a4bef0f3685d3c1d.nq.gz
    ├── 05427ec7b37d053689a34f590781a266fb14d888.nq.gz
    ├── 05be25ad7fecd34eb0bcc62d5f8ebe213b8d1a1b.nq.gz
    ├── 067eb3e5fc158ef239d5847581656c0af4e1dd5d.nq.gz
    ├── 06e798babbeba5565d34de95935daf4c527ac356.nq.gz
    ├── 072dd6acfb81c0948c2616cf97cf18d95f136d09.nq.gz
    ├── 0791a8bab16afa40818fc06ca521ab09eb45272c.nq.gz
    ├── 07abff4aa04062d51c143ef9f6dce04eb5ed1d55.nq.gz
    ├── 081cbe83449cf8e625a3e2e79b6b35415c4e1503.nq.gz
    ├── 08387739bb2158575ea51e739d5ae480a9c49dfe.nq.gz
    ├── 08c96ad69a022139b511c3b7c53505bbb0d76e47.nq.gz
    ├── 08e98a3a5fcb577fda09a2f844b3ba2160065753.nq.gz
    ├── 090a21deefdc79be1b63bb59e89832288a368d85.nq.gz
    ├── 091be47c2e874d8181398cc5a2c2c71c3e8b5377.nq.gz
    ├── 09b4f9451c3ccbe5dfb4290312e256ca1b12eb6c.nq.gz
    ├── 0a7415a0113bc163dde53a297239e1a114da1a1f.nq.gz
    ├── 0acdb70d3067fe8b507731f6caab93dcef3bb5d5.nq.gz
    ├── 0ba9db25329d0b336e39ca8cde8470c5b7bc45eb.nq.gz
    ├── 0bba4b3523c5ea4694a369daf09a11082118b905.nq.gz
    ├── 0c503d2c46122e30a3c77af8a73db78ce50c965a.nq.gz
    ├── 0d5f1b8ed31c8213d419fdafa5c129ecaa2904b1.nq.gz
    ├── 0e123a71d449035c38f8ac36fc74933faa94760e.nq.gz
    ├── 108c9b95b1de3f9f1c411591cfafdc05b4f85717.nq.gz
    ├── 11238dfd1462c2411e9830a7e216fda0d1bacda2.nq.gz
    ├── 120e2e60be5f70c7f93797243fefe57222365865.nq.gz
    ├── 12a18ec0ca4d4993ff3f0b2f24bc2ceea6746abd.nq.gz
    ├── 13de0149ebca6b79426f0c7b8e8e95d56986b9f4.nq.gz
    ├── 140d236cb6a3671a106ea8009dd315dbab77c399.nq.gz
    ├── 150bddf45102871ec73389058aade10350f18125.nq.gz
    ├── 1713069fa51d6e64c5ebdca1cf413a7bd42c3192.nq.gz
    ├── 1b2bd289867f02f228a9659934ee60599ea702db.nq.gz
    ├── 1bc469e68eb776aa52185c6cbfc5cdcaee837ce3.nq.gz
    ├── 1be267b7058d21bdd1eff197d922de06d26394a2.nq.gz
    ├── 1c8a364e9a34c84febde519bf12e755889e284a0.nq.gz
    ├── 1d2fbfc354b684c92e6093e6f6480b965bb61249.nq.gz
    ├── 1ee382913f09ae781da1ca7448b7d287496642dc.nq.gz
    ├── 1fa317b78a3a0819928a6c40a21788bac958ea1c.nq.gz
    ├── 20123e6d39483415f634b8e15f7ae619cfce1448.nq.gz
    ├── 20220c3b3d57ce2a42ceebd4cb3818aa4ed566ed.nq.gz
    ├── 2150e19f4bcc470eb50859b37b2e3ac68afe6e6f.nq.gz
    ├── 2255798821991c827ba16d1a30033b45ab445883.nq.gz
    ├── 22af6d03f1af79d96c455b86ba5e12b1ccee4c6b.nq.gz
    ├── 25039d349eb49d28476aef6119d680a3cb2f9bd6.nq.gz
    ├── 25f0bc5ed80683a81f46e6bfd1cf8ea0b56c6807.nq.gz
    ├── 268e0b60809785bbb519edf80c507c47df6bdeef.nq.gz
    ├── 26aab2c40e4e6cf5e03917e5eaf90c563451b711.nq.gz
    ├── 28284ef7c2e4f7aa0184afa7c7009bd46da10b8a.nq.gz
    ├── 28cc2aba5d527650212fc0ef5a4396b2aa18a117.nq.gz
    ├── 29024d31ad14ffd79edeb3955522f530de85a850.nq.gz
    ├── 2aaa4d1bafc617006b3407f29964dc428b693c50.nq.gz
    ├── 2c728c2d07a45dd7a50b98ec60e28d03d46ed505.nq.gz
    ├── 2e3429f86be6eabfc318802143c563c99430008a.nq.gz
    ├── 30a2a0fedaacdfb2f4d66e838962bf3e0d9485e2.nq.gz
    ├── 31559b7d115e3c105b328cce9b9dcd9774025061.nq.gz
    ├── 33b73350ec9463f074164d13a02e5bb9006630d2.nq.gz
    ├── 35aec055bb5e5ca41997b4fbaab7ed929924d6e3.nq.gz
    ├── 361df92ec1263d0eb3ba7920c362b99d606dc425.nq.gz
    ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
    ├── 3a376c074aba5d53a15607b23151fca0e416d290.nq.gz
    ├── 3a693fc93dfadfc4d5811bd4706d48466ae6b076.nq.gz
    ├── 3beddbafe7795cd2255e60cfd3b8de7706bf931f.nq.gz
    ├── 3c4d2f72512ae5c9e2a43ee9f9ffd8dfac3ad284.nq.gz
    ├── 3d5982c343224b3cf7403bb87fcc53b05e39c7e7.nq.gz
    ├── 3da08ae0f35156ef61e50341ca4f75ec7af68cc0.nq.gz
    ├── 3e19903d6d76b69892e1726493b9bb2a51d9ea44.nq.gz
    ├── 3e4490477b41fa3a94c4732bd2e933c03f1bc084.nq.gz
    ├── 3f7eacfad912c389197d6e58f539fed5add9df0b.nq.gz
    ├── 3fe9c3fc9468ed54c4bd2e529f1adae3aa311f19.nq.gz
    ├── 3ff899414b209ed362ab2654a88c6bd897d0d212.nq.gz
    ├── 40071b4d07219100368ea85baae3c9e410141603.nq.gz
    ├── 4379e7fe28d7635cbc8392dc54cc683b9f1b7db4.nq.gz
    ├── 449568b00de5dd31822135e3eea10f9bb1f148c2.nq.gz
    ├── 44cb47c0cfa9d907825c58097975df1c4e3aaf62.nq.gz
    ├── 46af037b55e0eeb918953d4360b6f5281754848d.nq.gz
    ├── 4804059ef75c17b6de6ca87fcf9eddd89f92c65f.nq.gz
    ├── 4870903e8fe15e2b62d44c61fb9d1634eacb4798.nq.gz
    ├── 4920f5ac8425b7545e11aaf98cd27bd672e45964.nq.gz
    ├── 495f855d919e65f6cc036ee7c5cdaabc84637cfb.nq.gz
    ├── 4bf97af8020ee45e554bc482af4d7eed14667dee.nq.gz
    ├── 4d55343559dcbbca3758f62c50ad61068b45ee79.nq.gz
    ├── 4da967282d94a9494e13ae4a130f80daeff6f55f.nq.gz
    ├── 4fb970606bf66275f4767b4405ea771ba0199fae.nq.gz
    ├── 50c28c72acc9aecc7ff8b601a6342c55f87761fc.nq.gz
    ├── 50dd94b0ed50a546f7f553bcc9a3e783a297d5a1.nq.gz
    ├── 52d8b9c40b3293adbd36498abbeee284b1f691fd.nq.gz
    ├── 52f19d7d6f119b37e85d043c24e61270b704bde1.nq.gz
    ├── 530c938e905ae45498e5b260e9c77b4ec1123d16.nq.gz
    ├── 5711960981536988cce0987c12743e521c71b5cd.nq.gz
    ├── 58a234c6129470ca04938512209c6bde380f6b23.nq.gz
    ├── 5b1df48189c70d3851628637e5bf2618a95bf47f.nq.gz
    ├── 5b8821f078e72b531f492046aa58d5684e66bfb1.nq.gz
    ├── 5c0406e252fe21538c54c65e66b5d6f0d23941f1.nq.gz
    ├── 5c2fedf57ba2ce91bcf85c12faf875c43c23f175.nq.gz
    ├── 5dfbf72b73128491be987d787c015ecde8dff716.nq.gz
    ├── 5e77960bc05512347802cb6431f10893ae84d9d9.nq.gz
    ├── 5ebd7e31ec4084112a30376bfb9efb631d90db15.nq.gz
    ├── 604c6d65c19b9e93b24f5da661e0a593ca8ecc43.nq.gz
    ├── 608d749ef9015c193c695f5c21de00589e2ac0d5.nq.gz
    ├── 6175c1457afdc99801f46c0251da28ab930fe434.nq.gz
    ├── 62a68f38f3cce8e39add4a756d5cfde0c4630cf0.nq.gz
    ├── 62de03733db18b6d92daf5e90ee46348bf8944de.nq.gz
    ├── 63c41d2b582ca427e844eaa0d0b01702d5ae74e5.nq.gz
    ├── 64546e8ca8c6a8e31c46b5cc4b9212be45c368a2.nq.gz
    ├── 6472b3e65b630d4ce045c516a111f1ff8e8253e7.nq.gz
    ├── 67e2cface2307e9d7c097f914ace1f7b3254c291.nq.gz
    ├── 6a295222fdaad99300159687f19b3cf4f72fa180.nq.gz
    ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
    ├── 6bf4a3087c32395a253141cd2d061d29c9e661a3.nq.gz
    ├── 6ee2ea2bf864e87594c0ce29bb111bef582eb068.nq.gz
    ├── 7417cc461212a0e9c8a5f89e033d87d34dad68bb.nq.gz
    ├── 74fb287d23dd7806a089a740af710dcbf507b012.nq.gz
    ├── 75880978c1ca074c9eb1fc007e4bc24edd9b7344.nq.gz
    ├── 7591fad2445c67326df76ebe840dbbdef554a67c.nq.gz
    ├── 76c2de8218e5553f78c6b39c32857faa644aec12.nq.gz
    ├── 7791964d67af69f708ec1e46887e34c01f7ab497.nq.gz
    ├── 783c0e446e6ba1675b67b3d395cee9aa0c69bf22.nq.gz
    ├── 786832175f71d1860a5c3c624204c4c15878b582.nq.gz
    ├── 791b36d8e5736e376a57c1a909c612c99bfd4f9b.nq.gz
    ├── 798a5fb36d2614fb5094b5622a13b71912bcf538.nq.gz
    ├── 7a8d80e258fcfd3727789f6cc34234ebe1980c5e.nq.gz
    ├── 7a8ec52dffc698882cae8d2fb2d1666f207341bb.nq.gz
    ├── 7a943ad256c17ac4b562fec7793adce69afe26ba.nq.gz
    ├── 7b41e065e75dce8d3629e630c234854625d80e6f.nq.gz
    ├── 7b66fcf1659108ba297f2cff564f343b7caee690.nq.gz
    ├── 7b82e58f1cf84eeedbd4eab440d6c417655d4c5d.nq.gz
    ├── 7ba6fcbf126c1d589a80a642a3697cafc2a15e49.nq.gz
    ├── 7d79ea49d29b2243a79b521578bdc61225273448.nq.gz
    ├── 7d9e2b9f3e9bf3e31bb154d523f947c10f9197ec.nq.gz
    ├── 7e30fa7466d3308172e83912f332e0067afb4f65.nq.gz
    ├── 7ebd2fdeb9ddab1a90ae9ddf919bee0ef2de1108.nq.gz
    ├── 800da8913adc80834dcc3264c6cba713a1d42a49.nq.gz
    ├── 8221823799cefa7b93a8ef0e290c6f2884e7477e.nq.gz
    ├── 851960f0b3da77eba339cc9e2066a4af8cb82a1f.nq.gz
    ├── 8545f0e777773419fc7a0e7bc5dfa416f0b9232e.nq.gz
    ├── 8566b0d5bda93aa17da9b73cea9362f717bce1da.nq.gz
    ├── 85b744da923cfce2201b3caaf7d40fdbc7ccc1f7.nq.gz
    ├── 86d82ab330ff2d2cb65752ef36de3d9f5654906f.nq.gz
    ├── 89d5f7d55285859489e5e529e55fa17018359f72.nq.gz
    ├── 89f82821266cc730ef6b489bf3ac73ac8377a637.nq.gz
    ├── 8a042027958d856c05b4622db2977c64c937928c.nq.gz
    ├── 8acfb31fa7ce2f5f4577c470727b0e0a4952a9c2.nq.gz
    ├── 8f1b4a9cf424042e4dabab14185b865e4af97d9e.nq.gz
    ├── 8f4894c971fd16339e986c90c87ec6a200c0c0f5.nq.gz
    ├── 918fd103cb48be3560e25e22d5b83610ca080e5f.nq.gz
    ├── 921b46897bb64d18b06b30b17e9a328956dca192.nq.gz
    ├── 9372c908a828d389218f2417334831c3c2258167.nq.gz
    ├── 9391bcd6df72e7bbb93dd3a353bb948feacb8e2b.nq.gz
    ├── 93f6e5fa0d7eb8dd2199aec8f7e91a607d7c7490.nq.gz
    ├── 94721af22a334909063cb66c5938dd80cbb0b820.nq.gz
    ├── 95c5f3e70a5a2ec1f2ab3fb096292aaf3e007416.nq.gz
    ├── 960e369d9b42b7bb3b0174dad6c037fbd7745b0a.nq.gz
    ├── 96e031f4e430ef427202befc826f8420084b3ce7.nq.gz
    ├── 9c1a77d3dd572760badd048caabd8594e1378653.nq.gz
    ├── 9c44165f98518efdfac7645074ff27d4f0f3f368.nq.gz
    ├── 9dc9c3df2cfaf280089ac03990589ce3b444f3ae.nq.gz
    ├── 9f2a371ac31fd1b24bbe856f5637234ac913f07a.nq.gz
    ├── a1e4f57012cf1d5da4648fe39caa955f115fa515.nq.gz
    ├── a1fe1b319732bda2195fcc68aa62714c7249462e.nq.gz
    ├── a226e2224aa39bc8cc5b59be5f354af56322ab54.nq.gz
    ├── a38bddec1c8ec4cf02b821085ba811d08e8a70db.nq.gz
    ├── a48dadb8c68e4fde7aa5c9fe8ea0a4074199471a.nq.gz
    ├── a50046b985021ca3f165da5f4a0bd17f6d9297de.nq.gz
    ├── a51aca79176c8a15756483caac8210d07b70c3f5.nq.gz
    ├── a5738ff339c534a26d756aeb7abd8306fc52d0dd.nq.gz
    ├── a630b134e0b766a606b1d4cd419b5d2dc6b6bb04.nq.gz
    ├── a64f3de28ae446e4137d70e49b014e66ba339253.nq.gz
    ├── a75efe0a777178594c6a571b1804c46f7f2851fd.nq.gz
    ├── a831c2c479607fde291dcd65d607d7e05466d375.nq.gz
    ├── a96fc1a0b7ec8570b56a4fe952914ee3aff9fabf.nq.gz
    ├── a9a8ffe51611c19575a287d3d6bd0ea63436f225.nq.gz
    ├── aa38e61254123516c9cb00fcc60fbcf5b4b2e134.nq.gz
    ├── aa9650918f4b871b142085cd2411d0e38af6d464.nq.gz
    ├── aaa1571bed61c576a7a11d81f4a016f69273a895.nq.gz
    ├── ac03fe0f1980c58f83cc0b1ccf2e3119c6aae213.nq.gz
    ├── ae008d7e9ac94f11a1b871b4a52732282ed29cc8.nq.gz
    ├── ae109f7e8240af57a228e6823fa3c7f16c6d1954.nq.gz
    ├── b0200a78c28345b20c1a01f4682e9967107eccce.nq.gz
    ├── b048279060d6b4a224b477595251fd17f27def47.nq.gz
    ├── b2f5b19d850ffba92e27412c33d0fddbe758568e.nq.gz
    ├── b3e14d806b9891f863ac33a3ffc69c6c423e8310.nq.gz
    ├── b3e5f4f307252bc09a7e97e9f864c5220659cf74.nq.gz
    ├── b424bb9ecd6905e1573c39c99e404a1ee0808d5e.nq.gz
    ├── b4c791387c5ea7044a472fe027b2b3d34845a95f.nq.gz
    ├── b511ec5b3370c9d074ca57a1dc337ae1778c6d59.nq.gz
    ├── b5ce472d16085c5710d1b3515bcae373f2d6106b.nq.gz
    ├── b6e2d9cdc063c6d0c4b5d4f3c06648fa91162e58.nq.gz
    ├── b757928883d46c6005630466974e6267770d90ff.nq.gz
    ├── b8c9558ebba839237715b4ee6f24b7070812eaf9.nq.gz
    ├── b9d277b471b3f93a619a235399f3b212281a6213.nq.gz
    ├── bad69a419d589e2a90490d26ae4237e91c7b38e1.nq.gz
    └── bc296d058188513e7bce33c8c91644f7ea92666e.nq.gz

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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[block/bitty-city](https://github.com/block/bitty-city)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
