# Repolex Knowledge Graph of pgvector/pgvector-python

RDF knowledge graph data for [pgvector/pgvector-python](https://github.com/pgvector/pgvector-python), parsed by [repolex](https://repolex.ai).

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
lexq download pgvector/pgvector-python
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2968f258f9486531bd1340cbda4ff8fcaf06cdc1
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2968f258f9486531bd1340cbda4ff8fcaf06cdc1.nq.gz
│   └── repolex
│       └── 2968f258f9486531bd1340cbda4ff8fcaf06cdc1
│           └── chunk-001.nq.gz
├── blob
│   ├── 00586799dd57795c6b72943443160130c8df9e80.nq.gz
│   ├── 0901fd23dd5991e01e72e5a89464710e1d5e57e5.nq.gz
│   ├── 0a4c7368718d3f22aaf529d4b5c7744e03b33bc3.nq.gz
│   ├── 10688b5c4d7ab50a188f95ad8267597db183126a.nq.gz
│   ├── 148eff2f578e8b1c7c55c61362dd131fbdbb140c.nq.gz
│   ├── 15411cdc285cfeaa23e3658594b6675e5c8559b6.nq.gz
│   ├── 15ee219494fe3f8a0497500ef12f5514014ad063.nq.gz
│   ├── 18587e26719650322be0874e9c4258f794393f88.nq.gz
│   ├── 185c7853b92b8ca1ad9142a89649e1751bd418c0.nq.gz
│   ├── 1bc9d4491e0681ea4f5bafa9cbca06d2e37dc78b.nq.gz
│   ├── 1cf8ee9b58d21a1635d6373401f2b57ef58bbeab.nq.gz
│   ├── 1d04739dbcca510782d320b249a84911524d0d8c.nq.gz
│   ├── 1ea85c388eb1c30d2cf8503055491380d8a98896.nq.gz
│   ├── 22fd056e38cc840d318c787924e380c8dad076a2.nq.gz
│   ├── 237dcd192b440892696b73a420e70173964c18ba.nq.gz
│   ├── 26a9d8d71863371936a25d23797e5f16785a3ffd.nq.gz
│   ├── 2b5daead2ea7985e21f78bc0c39bf3e823210304.nq.gz
│   ├── 2cc847ad6c1eacfb03466e331389f664e62f8df3.nq.gz
│   ├── 33e5124e8852e138d026fd722b7d20d0e24ebe8f.nq.gz
│   ├── 34d66a19501e9709b00ed8b2c274a4ff6d723f01.nq.gz
│   ├── 34f15d50b2c27189c20fadab84d7bbfa5c082ffa.nq.gz
│   ├── 384a0e14eefdeabb506957774affd7c7933a6f38.nq.gz
│   ├── 3aeb90fa22324975b0523224ff1f269a000d3593.nq.gz
│   ├── 3c011605aacbddcad63ee0735a3a7dbf34041b54.nq.gz
│   ├── 3d82365e1d542e0686b00c65598ae3a045a1f80e.nq.gz
│   ├── 3de81c781a422ed349f2e08eb759a84491a70236.nq.gz
│   ├── 41f88b2319620b3cf0f79eb635db55435e8de60d.nq.gz
│   ├── 424abbd3ce94838b3ea0094c5740c9d3ee0ea8f4.nq.gz
│   ├── 43c64a31d9a6b1d7458d3c6f8b2f533b09372705.nq.gz
│   ├── 4cf770d5c2bae8088d50ddd2720a65710ef027e6.nq.gz
│   ├── 4d3e4747b219ea5c116c9a05ecfec47333501375.nq.gz
│   ├── 4d5d3075f9d9cca512037a8a149094ebf4a84993.nq.gz
│   ├── 4eb5864a33b27a219e2e34b2683030c384f7cd56.nq.gz
│   ├── 50997d98d0e0487e73fb90d3318ff03e6bae3afb.nq.gz
│   ├── 52adf88e26b5b08e76ee2a7db954217fab7436f5.nq.gz
│   ├── 54b2cb9c815ef0c842a871129c108ef487d5baf1.nq.gz
│   ├── 562de1841634edaac5c186dc8cb78ab739ef2634.nq.gz
│   ├── 580f27c37a7a8e62b4e34b7412accc0099988d90.nq.gz
│   ├── 5a1e11f0ca1a520f275f78848875089154081bb2.nq.gz
│   ├── 5a716421179d9419bfe77cdfff0e50ea50787dea.nq.gz
│   ├── 5bec0eba4d5917ad1c920558252d1eebb59910bc.nq.gz
│   ├── 5ef4eec49d84d2cb4f4b13b26efd98559820ca6f.nq.gz
│   ├── 63726f30c3c513828c2d444ae5582c6608d9c422.nq.gz
│   ├── 64fc009c6088c8c0cdba7b587bb791959ea0d8c5.nq.gz
│   ├── 698b34f74cd081cb895a5d1f8b16533bf0d0304b.nq.gz
│   ├── 6f91e049be3a2e16ff8eda80c38abaf0ea27e3e7.nq.gz
│   ├── 72e3ca7e4d156df45dcac7e5222179b7dedbaafc.nq.gz
│   ├── 745335ff76d0cdcc067f8f13c124593080bf407e.nq.gz
│   ├── 74d60bf74922dc3a82b788b8d16ab8b69d3d1ac0.nq.gz
│   ├── 78b4977636d784e62cc541dc0052a4147d0a395f.nq.gz
│   ├── 7a8a6eb958e53edcec35043f611185bc8390fbe5.nq.gz
│   ├── 7cff86cf7ea8c48fa77a91b6059db14b9fbf3dd8.nq.gz
│   ├── 7f3dce81da5719828a0cdf01ec21abae99f1b95f.nq.gz
│   ├── 7f4932d0c601e703981fa0223c7a253dc307d8b5.nq.gz
│   ├── 80bb603ed4f4201505cbb3b38a0955db04d67cfc.nq.gz
│   ├── 83f9997eb6b4a9ba5f0093bcb453f683b4314d10.nq.gz
│   ├── 85a3e4f4b533bf3dec82bf9f84f7a92843a2a149.nq.gz
│   ├── 861cfdec2a00c85e4fc514a02c2491e2288e3774.nq.gz
│   ├── 86dea738b3e97102eabdf2552d05a9b65fce6bb4.nq.gz
│   ├── 895fbd0494cf27747ffcaa4e7759da367920bea1.nq.gz
│   ├── 8cdb5d66259e9e6837750aa826c5c51aeed44c65.nq.gz
│   ├── 915c25f6a57ad418d4e83a7688a1abfbe1b87462.nq.gz
│   ├── 980af84d50360dc66c1e3e4a2bdabc4eea7a37b7.nq.gz
│   ├── 9df4fdb3a0691922dd1c958ae65bde6e131b4a4a.nq.gz
│   ├── a13be061c8422562a9de9a57901fc4588570edd0.nq.gz
│   ├── afb56ec930a4fb27c76b78b7d4ab92e4fdc10141.nq.gz
│   ├── b3a00603bad8ba486b7ea7b3b432dbf8e5bfe242.nq.gz
│   ├── b3b4440e3b58fd69398f58bfc42fada996448ec4.nq.gz
│   ├── b4cf13147d40a50b2c34a37652d567d919814d9d.nq.gz
│   ├── b612d6d3f70fd6bb43992cb7da0884f0c09d7195.nq.gz
│   ├── b93fd3ee6003e12aceea244acb7428497ccd9644.nq.gz
│   ├── b9a078c7767daa5afdad9b6f3d8b9886adf7fcc6.nq.gz
│   ├── bd7d18d887f6c6a1c5757652b59f939fd23a29f9.nq.gz
│   ├── c4e6eea9f606dd8e590c75d4721337a2c2492ac3.nq.gz
│   ├── c55ff443ebd8dd302afe6f3be116b335c89e684f.nq.gz
│   ├── c59c12e56d87c4bf7e7e326257ea02f3057f82d9.nq.gz
│   ├── c6a3b4ea8b46831036ed0fe66ac13af9a902e20e.nq.gz
│   ├── cb2dca475d35d19ac166888a004564c385964375.nq.gz
│   ├── cfa5f51f1a7a8589bacc6053316b975a18bca58d.nq.gz
│   ├── cfbf18d3d2076a66eb8e2c5d607dbdb8b4584956.nq.gz
│   ├── cffe8fbbd3bad74fa142ca45eccdfc31cfbd84d0.nq.gz
│   ├── d580f327448822c9a647d10e47272c5138b16ca3.nq.gz
│   ├── db9e826acdee91f833533e9880217205ad1dfd90.nq.gz
│   ├── df21200e120612281fd8221031d6d26438dc969e.nq.gz
│   ├── e3971e6c836c3dd1b7af35d7472413ef63bf3e70.nq.gz
│   ├── e5a16fe2228ddede1eb6636ea74ecc474a3c186b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a2936af8c46fa0a30b8a21e87bebe51503a498.nq.gz
│   ├── ebbcafd30a9311719879e67bf4ad2c0b01b3fc6b.nq.gz
│   ├── ee5f12fe4df8ce38d09a1f906ada76e9dddfd8ef.nq.gz
│   ├── f0831c4903ef5ea8efe527159730f1861e98876e.nq.gz
│   ├── f335f2f6cf5fb1e517542dbce187ce27405ab6d4.nq.gz
│   ├── f4994f4e3000b3f900ac1bd6fce8ba4a5f95a431.nq.gz
│   ├── f49af4054e9cddd967412af9fd7039fb09794ab2.nq.gz
│   ├── f70eb8c862e53a2be475cf58bcaae8e47b16b8f1.nq.gz
│   └── fcb9027b03a34edea8614a3635afb7718810c2fa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 2968f258f9486531bd1340cbda4ff8fcaf06cdc1.nq.gz
├── filetree
│   └── 2968f258f9486531bd1340cbda4ff8fcaf06cdc1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 106 files
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

[pgvector/pgvector-python](https://github.com/pgvector/pgvector-python)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
