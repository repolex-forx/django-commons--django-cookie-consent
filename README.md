# Repolex Knowledge Graph of django-commons/django-cookie-consent

RDF knowledge graph data for [django-commons/django-cookie-consent](https://github.com/django-commons/django-cookie-consent), parsed by [repolex](https://repolex.ai).

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
rlex download django-commons/django-cookie-consent
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e5e009edea4744c5e081345849bcff0b83c6a8c8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e5e009edea4744c5e081345849bcff0b83c6a8c8
│           └── chunk-001.nq.gz
├── blob
│   ├── 008e2c436a654aec8035232201538ccc5a6c7de9.nq.gz
│   ├── 009b9f6690b6b7ff20c01ac24338b5537ab90f95.nq.gz
│   ├── 016afcd51d14c418589ab20b01961f6bfd0a2886.nq.gz
│   ├── 02de0e48e22a9f804b067e2d8df9ad9c87ae61c0.nq.gz
│   ├── 02fa462483498a077fa0fa3b3172b5be6fc73ade.nq.gz
│   ├── 03bc45a29122294aae4db4983d2ab0ba309fdae2.nq.gz
│   ├── 043490a4a2d23c8f7e2a679d4d253627b45b947c.nq.gz
│   ├── 08a7d949f07c5b5f54f22bbca668b0429412ae35.nq.gz
│   ├── 0a979bc3fcd7d4a4559f72fa9f09e4be75b5e4ed.nq.gz
│   ├── 0b26cc61e678c366fbe236e0ee918f788df93072.nq.gz
│   ├── 148b9f3e77200497ce1ad0647dd230f54a0eb66b.nq.gz
│   ├── 15cbb8dd1ae8b85422aebe1fe5f1347ec8a5f92a.nq.gz
│   ├── 1b15cf6d09b2ef7cd76ba617a2b24356ca79d40a.nq.gz
│   ├── 1b4311a7c500d2655df68b9f4f64135eacaf1b64.nq.gz
│   ├── 1ea12ac0ef859a3be785f87b80e8743d7f174bf3.nq.gz
│   ├── 21b56f6758197ce1f6c2bfd1de3e301bc81ff244.nq.gz
│   ├── 240cafb85825a9826d957f857ad04caa84f39de1.nq.gz
│   ├── 257a7e7cfcfb07df5fa5419aa6d4e21319d8b846.nq.gz
│   ├── 27d088692b3510e0bf087091af84c50b5f7bdaf9.nq.gz
│   ├── 2e801f0c9ddab5226b53adbf95bc01dafb5b9f35.nq.gz
│   ├── 3c76f78b98a61e5d9d4bf80333949cff98c1e888.nq.gz
│   ├── 3e4c452d94a8a1440d664612e984c673de3d30af.nq.gz
│   ├── 3f656d6f15b453a896d65a51f76e958222a39f75.nq.gz
│   ├── 406a26f89f588f5510568bf308dd85926c85be20.nq.gz
│   ├── 40e9a60fccdf19c545fae7bd0a3684ad3bfda088.nq.gz
│   ├── 48a08bff96ba52130f03f0d3102b80334c258b00.nq.gz
│   ├── 4a1a20c85630757e5aed78dfea51aa3821f322d8.nq.gz
│   ├── 4cd9fd42ed67924639be02f0fd24374c76c41626.nq.gz
│   ├── 4fd920409c2b94c27462360b9462d601511eeb88.nq.gz
│   ├── 532761c4d3565daf8faf7de6580f3624f90ebc69.nq.gz
│   ├── 5377f4beef4c753a6639b5a2cd60ac8592438c2c.nq.gz
│   ├── 54c65116f15a6832459847f69931fe830411bbbc.nq.gz
│   ├── 556343f840d3972bcc7c73c7d1c446287630a718.nq.gz
│   ├── 571601aba193e1bc21f9fb40cdc16b2f57a8eede.nq.gz
│   ├── 58111a5638cd5c73f4027e6bdec40617a1fe4122.nq.gz
│   ├── 5becc17c04a9e3ad1c2a15f53252b7bb5a7517e7.nq.gz
│   ├── 5e5e9ea8f10ca6ea28e8f7460e69c4ab78349a2f.nq.gz
│   ├── 6539845ecdb1d742352d7d591435945abf315f9d.nq.gz
│   ├── 66b6c44a6ba729c9bc88946bc153efc3070c33c3.nq.gz
│   ├── 673689cc337e65cc4e99ebf9d68b7d04c8ccbcb8.nq.gz
│   ├── 673c5806145d952bf97c94574a197cb8601a2955.nq.gz
│   ├── 6851e93e2163030aa15112c519ecd914aaea6bd1.nq.gz
│   ├── 6afa3e23169066560689102eaffa4de49972a3c0.nq.gz
│   ├── 6d20309c8d40a297b04d95e01d7ebb3a3e632a80.nq.gz
│   ├── 73a760c46865996fa5edd994ba3527c886d75af1.nq.gz
│   ├── 7bb5a7ea6ca6f0dcfc0d2a86e6ab2274310ffdbe.nq.gz
│   ├── 80e6d389dbe5cfa484543d0874fead8f92db5032.nq.gz
│   ├── 818d25d2332ab93066b085528e962573ae531430.nq.gz
│   ├── 85a3037f988d2b3cc07634d24e35bbefe8fd4be4.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8b308b912c52d9c9a6edd0dc82f49ea635cd3022.nq.gz
│   ├── 8de36810a67f240cd9419878404e42107ab6067f.nq.gz
│   ├── 8edaf2b098aeda4eea432059e067fd2137de4454.nq.gz
│   ├── 949ad300928865dd66c4d7df96e7294e1ac98083.nq.gz
│   ├── a0142029a91e9a0a0cd4131faf0d24ad7ddba292.nq.gz
│   ├── a0f540c7c4a90a9282c5db527eb1dacdcb66ca78.nq.gz
│   ├── a4c8655fcb52fb9efe9854fbc3820b64e7f7138f.nq.gz
│   ├── a6e41752af6658d1c2cc6f783d0df8200caee5db.nq.gz
│   ├── aaff741bdc1311a750f0f5d3f2217c40c949562c.nq.gz
│   ├── acd618e7f3694b768018ea2ec8059fa81834cf93.nq.gz
│   ├── b2f94d2e80d00931afc356219286a0443afebbc0.nq.gz
│   ├── b49930c002057597875524d068980772c9cd3e74.nq.gz
│   ├── b6b960b396d2c70317e5dee40877f8f81600d8f9.nq.gz
│   ├── bb58f58f8ef364579908441c2e5e17c1c081fd14.nq.gz
│   ├── bbdce9dc1ca7a6959e1f17d33dcb6e5af184bc8f.nq.gz
│   ├── bbe1527c588e9a37707f1f38669061584a6f44e3.nq.gz
│   ├── bdf5239f4454e7e45937d135d244b05ea61044e6.nq.gz
│   ├── c04d0f6e994b9bfc3d86a0129a65c363d7d8d1f9.nq.gz
│   ├── c27a3f5b630af7de0da3630c840df18415c2768f.nq.gz
│   ├── c29d49c948b10e29fdd884efee87a089b581c042.nq.gz
│   ├── c3b18359de8ff23847a71ae4fb79e2a58c1e70a6.nq.gz
│   ├── cbdfd495dc075d2cd8f6777bfa7f4158cc9de40d.nq.gz
│   ├── cc1003a111af13fae92c4c48fc9d1c2ddd04c1a0.nq.gz
│   ├── cd39d5857fe616b437da02205a329fedc69aa5ee.nq.gz
│   ├── cdc041b6a53cf0a821ed9069ca39cb86eddc16ac.nq.gz
│   ├── ce0349c16a1677d7328a115333055fab35c30355.nq.gz
│   ├── cededad37f004a803dc53d4c2208e7c86c10545a.nq.gz
│   ├── d03afb82b25fb1773b64944c6c949ce785d65ec2.nq.gz
│   ├── d1d37475e2c374f583b552b4600664b7342f06b0.nq.gz
│   ├── d8558b6853092efaf1c290a8a1f055f1f4f4c879.nq.gz
│   ├── d8d1ef7774301d7024bf64ac8b68f1187b7313a9.nq.gz
│   ├── d9525604a9ed216dd6b44f0d4a33c35cf905dc05.nq.gz
│   ├── dc4839008ae9b325d625276c6864e577b835c700.nq.gz
│   ├── e165f4a624df2366fd50f00635bdb6223104ad92.nq.gz
│   ├── e692cb61c7eae01de3258477db99631549b56ec8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e800c5eca34d0380820f0ef897f4b5a49ff014e8.nq.gz
│   ├── f01131083ea273aaddb91513b74cc0aaf8f89fa7.nq.gz
│   ├── f02ac6386bc904ed4a8dfb08a857ed46e3d4b37a.nq.gz
│   ├── f0d608a1a08a7f3d191d6a9c59e2fd95111f0ea9.nq.gz
│   ├── f4b0e55b8380434636d94b200cd35d62bb8f28ff.nq.gz
│   ├── f708bd6aa2350d5a6f698b9a023372c4fb7edcbf.nq.gz
│   ├── f7cf72f7698fdb2710f1e01467bfe9fe1607a907.nq.gz
│   ├── f82a4fb0f2ced2527440a6d8aff78ca5be778b21.nq.gz
│   └── fcaeb42bc1904aad6cbe10bd8b38bd85f43e8b09.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e5e009edea4744c5e081345849bcff0b83c6a8c8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 103 files
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

[django-commons/django-cookie-consent](https://github.com/django-commons/django-cookie-consent)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
