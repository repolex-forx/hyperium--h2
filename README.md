# Repolex Knowledge Graph of hyperium/h2

RDF knowledge graph data for [hyperium/h2](https://github.com/hyperium/h2), parsed by [repolex](https://repolex.ai).

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
rlex download hyperium/h2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d57d1b852fec9dda6d42d3454502006d52104da8
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── d57d1b852fec9dda6d42d3454502006d52104da8.nq.gz
│   └── repolex
│       └── d57d1b852fec9dda6d42d3454502006d52104da8
│           └── chunk-001.nq.gz
├── blob
│   ├── 00642f83799e7c7a2b997c26cea2e7fa04fded37.nq.gz
│   ├── 01634e4577356d1d3461de3b919f923764fc71e9.nq.gz
│   ├── 02792c134c5426551e49e7283b6c24be7ff9ecee.nq.gz
│   ├── 02b6450d007c18acc6241d046f5a1b9cbaffd362.nq.gz
│   ├── 02d265061ce68046e40dbccf7f010ab74c77bc7e.nq.gz
│   ├── 04e709ca008557b75171ebf5e31e889876b48b2a.nq.gz
│   ├── 04f8dddaf3ad036c23e1aa1d3ce2ad0104e837fe.nq.gz
│   ├── 0b46726530139a3f0295d4e7e20bd4b99c2616e6.nq.gz
│   ├── 0f427dfb491b632bbcf18d49f46780f1252319fe.nq.gz
│   ├── 101987342f385e24b65a10c3f8341ff05a3d008b.nq.gz
│   ├── 10e30849c62119a275217fb428a0926b1084a2fb.nq.gz
│   ├── 11239dd1c157a353a2402fc66a1f5e7596d88c76.nq.gz
│   ├── 11d1207e1d9b79588c36ddcfeb6cd1840151e1d4.nq.gz
│   ├── 1230fd14231574ed36d5cbfc09c57a46fa720030.nq.gz
│   ├── 12c75d553588e30f955430a568c9053651c7634e.nq.gz
│   ├── 1b73b33394b79b006b4fdbdae827d9e1a7593fc3.nq.gz
│   ├── 1cad3dfd24ae6ae967793be361f4b9b1c92f9204.nq.gz
│   ├── 1e31126e06d364fb8cecd6f40c401589dafe6b87.nq.gz
│   ├── 1e7af32f57f82bc92a0134ce8d8c7dc650df1f20.nq.gz
│   ├── 2132c7acf3f9edf2bf95424dfca56fb97b897a85.nq.gz
│   ├── 241d06ea176f8965f5db711ae6bebb8fdb0ce9f3.nq.gz
│   ├── 249438d5ccc0ee844da1c910199925b1913c563a.nq.gz
│   ├── 27ae85b8db837aad848e5cdf1fa9d1eaf6621578.nq.gz
│   ├── 28905524b6fb2de5965ac222d40505cf8c8c9579.nq.gz
│   ├── 316d6a1800d50888a34e0650f9069bfa4c24313e.nq.gz
│   ├── 32efd7e41eaa0fe7433381cb7a9e82898350ab13.nq.gz
│   ├── 385bcef75dcb0737bb4b1602566b322963467c09.nq.gz
│   ├── 3861aa2d34d77ed60958bb1328891b7ac9b7f978.nq.gz
│   ├── 38be2f6973b1ea8e50f3b077110ea48392a49fe9.nq.gz
│   ├── 39f6ac20229c91bb031c3e25a0dbb95a2aee1f20.nq.gz
│   ├── 3b0ddec7605dcfc385c872f264ab8db3ad419623.nq.gz
│   ├── 3bcd132058eca94e4dc997c2cfc2cabb7bedf32a.nq.gz
│   ├── 3c13c0afe123111042bbab5a9f7a045a787ff15e.nq.gz
│   ├── 4338143fd2f732fb874f35cc7b31eb4dfab751f8.nq.gz
│   ├── 484498a9d9e67084f021a7506e723d953dda2ece.nq.gz
│   ├── 489d16daf789228edc093317f78665f53370230a.nq.gz
│   ├── 4b5d043410af7834a389c54cbdbee5b9cf1244db.nq.gz
│   ├── 4b69dc699daa84ec04b8f2fd2da5aea802db8c7e.nq.gz
│   ├── 4d9486960c0181951009e111acf3a84706f5e48b.nq.gz
│   ├── 531f39d0a3432918de91cd822953b46309a4a2b1.nq.gz
│   ├── 53363239cb7a55763533ef3fd5942119e17e77a3.nq.gz
│   ├── 53acb79fd6429ec240baed351b06169bc7e7e7c1.nq.gz
│   ├── 5454ebd793a5b5ff8f99c216aac322dc368011aa.nq.gz
│   ├── 55fcff85f9ec68b2a6b4fe73499710d4c76fe0c7.nq.gz
│   ├── 572e03bdf321b6cc3a99488183436905cefd086d.nq.gz
│   ├── 57a9358252bafb83180a2ab875efd02a21aef6f8.nq.gz
│   ├── 5ca03a746d47979a2d18c680d1c14b8384c40c79.nq.gz
│   ├── 5e3b4f40a382caf1afeb07e16f1b9e2e0b2aafdf.nq.gz
│   ├── 5e72c424caa9c59596444b8d72b71c6d4743f0e4.nq.gz
│   ├── 61e237aa3c0ba6a305dde299563ecaf699e70a9b.nq.gz
│   ├── 6780fd10e1c856990b1577dc6e5dfdca214e2a5f.nq.gz
│   ├── 692c0bae98bcaa04d0c94e23509b20f64a69801d.nq.gz
│   ├── 6afdf90539a16172c426ac3236858e8ddb9000e1.nq.gz
│   ├── 6c0c8b0b37e97d9184ef7c14e2350d728672c4c1.nq.gz
│   ├── 6d6490db08363bfc4a8671930c1c6177ad569e05.nq.gz
│   ├── 6d6a883513edb79aa4331b36af1da6fed7e306b4.nq.gz
│   ├── 70c823eaf874a1a61d489575758d7aa467123692.nq.gz
│   ├── 757e2b2750532fab8519a61145219d55b86ade2a.nq.gz
│   ├── 7ec84db86719eec5d31c2e6a6adf662e4cb36150.nq.gz
│   ├── 80ce8834e0e0e9f1925328fe7510acd5a7ffd7ba.nq.gz
│   ├── 81214995f6b11a6f47c207c783d03d8d09ac45ae.nq.gz
│   ├── 87038c350521fb2e990503661e796a9cc9403f04.nq.gz
│   ├── 88e3d4f7cc835a7f1abf3fc11b24393304411766.nq.gz
│   ├── 8f10e2e4c8e15ecdf24b45181680fbd5e0521d98.nq.gz
│   ├── 922eca2381d4c7c9b81a883c8349fa4dd1b41fdf.nq.gz
│   ├── 96a471bcbd34b61617f775e36191a0b743340a90.nq.gz
│   ├── 970648d5aa6422e6fdb2e4ce12aeaa677dd7b7b1.nq.gz
│   ├── 97800193f872583075a1b57893764a0051b60e19.nq.gz
│   ├── 99330e98112778fc7d421e079d51daacfabc271b.nq.gz
│   ├── 9b1f27169d11af78c3fc966b6dad5c9b16e22156.nq.gz
│   ├── 9b3e14b2a35633b94299b2d5db140924563c23ea.nq.gz
│   ├── 9dc7b00f9545f396efa04b1dd5ab4cee3a4adc11.nq.gz
│   ├── a0a58800c9318898c11df46a4037be9c736550b5.nq.gz
│   ├── ab8c43c1baacb603f64c42ca1214a700ca9f6ea6.nq.gz
│   ├── b0f9599e93f260c6ba28b493337b48197702f07a.nq.gz
│   ├── b1c76707a9d30fdf486ea8268362372f113be1fb.nq.gz
│   ├── b2685ed3328bb2501bd5d1c2b886227c43fa564d.nq.gz
│   ├── bc6384c5a25836da4c532a766a04f3ab5c573b3d.nq.gz
│   ├── c04742dfdf06a0b5e999597d1855a6e254a4ab9e.nq.gz
│   ├── c0845507fd73286976e5c8c5f74003ffdefdc569.nq.gz
│   ├── c0adf3ebb7217fe47bbb9c0c40c8a42a1b0ceadb.nq.gz
│   ├── c2597bb94f1f78aa0652c77d43abc2e0ba7b21b5.nq.gz
│   ├── c56b368fb195eb3f1c0f42751343677ef85fda21.nq.gz
│   ├── c67d2dfc05596141b77cf9558a0e8e7a9e6685dc.nq.gz
│   ├── cb7e677aedb728d6426cc2d4173baab886f9ab84.nq.gz
│   ├── cbe7fb289c4222a5e9322d1080c64810d53d2589.nq.gz
│   ├── cca18c66e1e7fe2caeffbf59ea93e76ab6c89474.nq.gz
│   ├── cce7eb1b170de42ffb8e56f935cdc4e659dc5670.nq.gz
│   ├── cf383a4950c7eeb171f833009e53965e6705c386.nq.gz
│   ├── d0009a5a032fb60f97bc11ba9e6ddd3c9bc3253a.nq.gz
│   ├── d28ec0510b2133c2f13a551b4bcb2f095722a4af.nq.gz
│   ├── d52252cd7464c9c7f7b1f5b16dca976219acc72c.nq.gz
│   ├── d6155fc3d2f362f5b30ebed361759a48b8b1cfd4.nq.gz
│   ├── d7aecee91e93d84e9a4bdb4e9cee67b61e7723f1.nq.gz
│   ├── d7d47dbb0192bcc57a3744e285a90be13b469992.nq.gz
│   ├── e485dd781742e67cf22023ddecbc066442ec6856.nq.gz
│   ├── e65b2dad9e85d7a1cde54fb18e6d200d6dffe157.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eacd3a78c58323a53a323923c1dac69e9b621d82.nq.gz
│   ├── ed6ebc81d8b3bfcb6ae22509d2f603ba1e31f6b9.nq.gz
│   ├── eebbae98b7142947b8e129000dc8c417af360877.nq.gz
│   ├── eed2ce17ec2686211e2e886bb4168acc2020a357.nq.gz
│   ├── efd1966cfea02bf8838a84e29771883394cfbd55.nq.gz
│   ├── f0f34b2c42cd5e3e41ac81d472d30722c32486a6.nq.gz
│   ├── fa467ac36db0eb3e5114382f80bf7786bd8f3c60.nq.gz
│   ├── ff5e2012f80614900cd3ca32f62e4204f252d5c5.nq.gz
│   └── ffc0d226b761a818e2beb9d308376adbfef4bd90.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── d57d1b852fec9dda6d42d3454502006d52104da8.nq.gz
├── filetree
│   └── d57d1b852fec9dda6d42d3454502006d52104da8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 117 files
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

[hyperium/h2](https://github.com/hyperium/h2)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
