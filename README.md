# Repolex Knowledge Graph of ansible-collections/community.sonic

RDF knowledge graph data for [ansible-collections/community.sonic](https://github.com/ansible-collections/community.sonic), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.sonic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 59d2dcaa251166d63135bbbc171bc71b82f3b946
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 59d2dcaa251166d63135bbbc171bc71b82f3b946
│           └── chunk-001.nq.gz
├── blob
│   ├── 0164155b81025416095f31a4732098ec238e6476.nq.gz
│   ├── 02569cef818e343a4f0569de0a4ad9abf720cdd5.nq.gz
│   ├── 056ecbebba080def784331a7b3f7e4157cf9a6fa.nq.gz
│   ├── 07f7cb26f79a3d17e44b3c78922d8eb23dd440a7.nq.gz
│   ├── 07f9b64e535394e1a99160daee9c6233c0dce41d.nq.gz
│   ├── 0829f38a09d7c538a470aaa9897d5a80b4b10b43.nq.gz
│   ├── 083c654c4954c95b7255f091ad12754b1889fe3f.nq.gz
│   ├── 0a16949e605ce4da622f278a8851e4b537f350c2.nq.gz
│   ├── 0cc45da909726f8d056229f0940938a029e4fe6a.nq.gz
│   ├── 0dc902fceaca7f1a1c4943509774298ba065a039.nq.gz
│   ├── 0ef3dc2582074a81222533e8171ddcab11134773.nq.gz
│   ├── 12cc325e27d6d8eb13be220bdb29bf25a8d85d0e.nq.gz
│   ├── 1406c463de1c08a6fe08dac3fdd745cd0c7b6994.nq.gz
│   ├── 1b62de8f58c4a5bc9169e5be6b00cea876a596e2.nq.gz
│   ├── 1c931d5b37445b91b06ef5297883493760abca7e.nq.gz
│   ├── 1cf48806914e6f6a1459ce612fd29311f48dabc9.nq.gz
│   ├── 1e642fbc02971f7206b45fd018bc93fa3901d410.nq.gz
│   ├── 1f600af133e6226a4093086c62eb669d5edf9a3a.nq.gz
│   ├── 20ac2f9859463569fd02afd235e17acf75bebbbf.nq.gz
│   ├── 214837e00648e84c799f5f9d87d7dab7984a5958.nq.gz
│   ├── 24da6334be46336e5c156cc55218147d92fffffc.nq.gz
│   ├── 257fe0c35b28210fb147c0dfa3f615ab09d39ed5.nq.gz
│   ├── 2793b4b125e36cc10987ad145304920e822a1865.nq.gz
│   ├── 27bf11eb492f3e571d5b51ddd9a1bb75f8f27e9b.nq.gz
│   ├── 27d74185701e0dc9c334c81cc670a9ab5766c0a4.nq.gz
│   ├── 3041018ce8c85f035c7564722cab4f7467861d08.nq.gz
│   ├── 316c330f049564e40bb930b1b3d3b9dab4822dd9.nq.gz
│   ├── 31d6091cae84f8494f8c8ff1d236673bafb7e118.nq.gz
│   ├── 3380df8c9bb865bb9efc6f949c3192192e28eb21.nq.gz
│   ├── 352e5118398ee69a153810a12c95d6542d5b1767.nq.gz
│   ├── 35a2e087e557155f86a8498039c9b8ab8edf8f44.nq.gz
│   ├── 365a539e586ba46e2f15386608d9d438cb4b31ac.nq.gz
│   ├── 36a26b7a0cefe3882e88128e95256d364c92cb3b.nq.gz
│   ├── 3c4d5a79e97f993e26e71700dc64c04cd5e2ce4e.nq.gz
│   ├── 40d6f68c3e8a43e59a4416d88136731839634e2f.nq.gz
│   ├── 40f3902bdb0b36fb64afdb5a9369fa44eec77f2a.nq.gz
│   ├── 41032242559386a30332ad77802457d980d21247.nq.gz
│   ├── 435473b79a9310f96491b6a0c8ed81c4d917d8e4.nq.gz
│   ├── 4515529392d6e6e4a51292e6cfa0412c2f056e4e.nq.gz
│   ├── 4ea41b2624113b53b0ce3ad1070fe06c96ac63b0.nq.gz
│   ├── 51f9eced0aaf761ca1f944cce520e6a028730b59.nq.gz
│   ├── 525daa448b2d5b6e6a4873f992b09985c0bb140b.nq.gz
│   ├── 52b9b14e3d3bbb5fa7f21027e6a6e4086572e077.nq.gz
│   ├── 539298e35ca76077d6163d225fa5d070f08f19d7.nq.gz
│   ├── 567aeae630a6fbe2718b4cb6c23118a55d92ad38.nq.gz
│   ├── 590b90b302e6de60f402bd6203c59610c28422a7.nq.gz
│   ├── 59b95d695e9568e4bd5545b1b1890d1413ee3951.nq.gz
│   ├── 5a4a3f1855811c0299ef51770f059dfcc1bc21b9.nq.gz
│   ├── 5a81d173f8211d426e022ef8e77118ed1d67c258.nq.gz
│   ├── 5f55c73c0398c46a14ac1fdfa895ffb25b6de41d.nq.gz
│   ├── 5fa6453a34a381dceb8ee2ee53e9a6f4918f2fef.nq.gz
│   ├── 627dc3db79a57fa85b6faf2a4fed1ef688d7a3f9.nq.gz
│   ├── 62ebd927f03780a028b6c7818c83cc219a788cdc.nq.gz
│   ├── 66fb960302e64ced7c76f9e2dcd28f09f7d405fd.nq.gz
│   ├── 6757f83670b84c2dc0e013df4d12d909b37adfb8.nq.gz
│   ├── 6a66a7cacad3819f98fcc40972a98d69ab02a28b.nq.gz
│   ├── 6b0ae0a588782b6588b2ecb50483b3ae585fb555.nq.gz
│   ├── 6eefee90f78ea3180f5210ac748fb45f42a6d5f3.nq.gz
│   ├── 720fbcfa1c8767a77b3a1912f0cfb7c2e5b4a75a.nq.gz
│   ├── 770e36d4268fb016f0f9a7ab43d583c5285b8785.nq.gz
│   ├── 77e4cfdcc275c3dfef003104183608db69151c6b.nq.gz
│   ├── 787f9f317c795821a56c47f0b409012ab771df6f.nq.gz
│   ├── 7a43c44ee5aaa420afc016249156a6f82878d396.nq.gz
│   ├── 7c09a1f8cebc8b09e924cef052de83046f1c46f1.nq.gz
│   ├── 7d3579372dd4bf4d5c599d6ba876737268a8a198.nq.gz
│   ├── 7f2f5ad86e1097fce28ef0a634f8241e05449ad9.nq.gz
│   ├── 8193db19c7aac43d1d07f00da022bf5b2eee9558.nq.gz
│   ├── 8599f75dbdf18bfe9018f8b4eeead91297b5254b.nq.gz
│   ├── 85ea86978e4c7c1e0e4e76f4d85b40a68d8dbdc9.nq.gz
│   ├── 8c13b9c110e03b7b9471f68261eed84ca59d22c1.nq.gz
│   ├── 8cfb8f4d994eedf0dd50df06ce4a8ab61283024f.nq.gz
│   ├── 8d7af5d2c614491fc4244b111234a13e5246bcda.nq.gz
│   ├── 8d9504031c2392207f30a16fb6033bd36e01c1d1.nq.gz
│   ├── 9153f727dd3621109827e6d8ca4342e048e0c25a.nq.gz
│   ├── 9424d5ce580064d84ee8e4b249060eba1d04df98.nq.gz
│   ├── 95bfff8c544570d701339f505e1544034497b95c.nq.gz
│   ├── 9655c5c005c2c6c7d6714c8a24626c8f8b52c6f7.nq.gz
│   ├── 983a14b3fe37ae0760d4a50a27fe542a480b68a0.nq.gz
│   ├── 98c30b98cacc97e80a978bc1534932b1ca895f29.nq.gz
│   ├── 998415061823267968292c6db915251cb64eeea7.nq.gz
│   ├── 9cadfc089db3db8695ccd630e9453153b8cf0c13.nq.gz
│   ├── 9dccf7ef174657345b77b37626c52cdc0390117f.nq.gz
│   ├── 9e745d99e7bc0ac0ab104b0c7f55d18178bc9018.nq.gz
│   ├── a10903a78b39aa91caf6af5f6d6d6f522a0e5c51.nq.gz
│   ├── a3471f8e1c5610fedb8ce43c52e194ce6a9309b9.nq.gz
│   ├── a465fb71caf487c5ae89938d6b84ca0e08755268.nq.gz
│   ├── a5151a00d319cbe8c1530dc16de4c9af55664c1c.nq.gz
│   ├── a639fc51996423ba4e46c2efe2c39e0da71eefdf.nq.gz
│   ├── a669f11617c1caf3a6f17e057cf8aa181a8e4736.nq.gz
│   ├── a7ce04a858959a37cbaf46a1cd5e835903a83333.nq.gz
│   ├── ae441977fc91204f3e7d65b5b0cf5d15283ceac1.nq.gz
│   ├── afc3f7ffbdd6e54e71cd65dcf2bdbe13be85526a.nq.gz
│   ├── afca3c607fb0b1f4127f1ab4223355ac4dd35231.nq.gz
│   ├── b05d917d5f323558d3466bb0f427e2a42a0a0f92.nq.gz
│   ├── b39e5790de790f089f431cd21d5b766ef8a44c07.nq.gz
│   ├── b428b38f94c32c49dab5346b319717a01c0c1da0.nq.gz
│   ├── b511198bd8b2d42f0f28f913ad92f9d8e139714e.nq.gz
│   ├── b8184422ebb1d336cdb31e19a09703d76c19ee49.nq.gz
│   ├── c261a148564988822d9262bab09f37eac5e739ec.nq.gz
│   ├── c522161b6ad200bff01e36923892ef840f1dadcc.nq.gz
│   ├── c6ec0bbb14bdf7cbb535cec65c73f77e728015cc.nq.gz
│   ├── c731870fe3e79717d7c4c540f122316316cd91c5.nq.gz
│   ├── ccdf96248b29072bba25b756b1a7df9b04772a43.nq.gz
│   ├── d1a33b78409fd2050d47090226cc4a03052b97af.nq.gz
│   ├── d1e8c646dea94dac6ed78503cb7774daf924006e.nq.gz
│   ├── d50890ca140fab410884c37ef9d38746034937b7.nq.gz
│   ├── d552db51ff568552d419d5087b444e5de1fcaf11.nq.gz
│   ├── d79424fbd366549a14e6491f982b835f5d17b344.nq.gz
│   ├── d90f013aa4a7ff5d1eac15ab1b30818a6588d3d6.nq.gz
│   ├── db430ecb2a7d654b93c1e99fec9730956aea9af7.nq.gz
│   ├── dd891e7084319ef42bbe22ebedcb2c70716e4dcb.nq.gz
│   ├── df8854e7f0ec955f1d8aaa8e7fae79c934402148.nq.gz
│   ├── df8ae2679d20d81fe292a00b7071edd7e920524f.nq.gz
│   ├── e150e44dbb20d99f6c8f6b63ee963ef828f8895d.nq.gz
│   ├── e21bded54f1b442e7506083df2ec839f86d7f97d.nq.gz
│   ├── e28e0c754224f42b98876efebc13fbc042d53a7a.nq.gz
│   ├── e76e61c0feabceff97f72c7aa220087a141c3c5a.nq.gz
│   ├── ef7fbd401f0ecc8d8d625ea9ebffcd752a985900.nq.gz
│   ├── f0313637fe607f41afc90909d94be27e0e4a9497.nq.gz
│   ├── f128844685fb507b7f3fb0585f13c0334308bbe8.nq.gz
│   ├── f14b430557810ff22fb49929dd78385aed897084.nq.gz
│   ├── f166b23e04d9931d62e9f3361982ced0df7c843c.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f2ae4df9933588e2c69afa37cf817825211dc8dd.nq.gz
│   ├── f2fc7bf6f3d40d6a6d3f50c6727f16928902abc4.nq.gz
│   └── f6b09bdda743326acb4e020bea730d236a211cfe.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 59d2dcaa251166d63135bbbc171bc71b82f3b946.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 134 files
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

[ansible-collections/community.sonic](https://github.com/ansible-collections/community.sonic)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
