# Repolex Knowledge Graph of python-hyper/h2

RDF knowledge graph data for [python-hyper/h2](https://github.com/python-hyper/h2), parsed by [repolex](https://repolex.ai).

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
lexq download python-hyper/h2
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1aae569315eb170cdff00582644aca37ee38db62
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 1aae569315eb170cdff00582644aca37ee38db62.nq.gz
│   └── repolex
│       └── 1aae569315eb170cdff00582644aca37ee38db62
│           └── chunk-001.nq.gz
├── blob
│   ├── 024110a3271388dac806a939528e714b7264012d.nq.gz
│   ├── 06111c33d647dc5fb495f82ea77d10a6601aa530.nq.gz
│   ├── 0830a91d4a0268cdd5cae503971c87f4adb75b3e.nq.gz
│   ├── 0abd70dee3f559375dc911effa70f074486a0cd6.nq.gz
│   ├── 0ce3e4442dd5d6f845e587baffb466db31321f4f.nq.gz
│   ├── 0e5017e8081a936661c292f28b2c69e41168becd.nq.gz
│   ├── 0ea7e47bcdae37d41269358a60003aecc42ed362.nq.gz
│   ├── 0efdd9fe6c277ae790dfde3321eb0732e232492a.nq.gz
│   ├── 0f6092c2f09671a7544a7f124bc8fc14a1a85694.nq.gz
│   ├── 10d111628b200a467ca545ead28c6ccdd2688786.nq.gz
│   ├── 11105cbb9e6b76e26325dc6a1c6a3304eb8d993a.nq.gz
│   ├── 11f9ea094b85820acd85dbca8c379a322046ee8a.nq.gz
│   ├── 1371f200a5b39856455be464dc2ba3a309def5b2.nq.gz
│   ├── 202ca64e170d31edf0b00015eec2085305fb2941.nq.gz
│   ├── 21cc7b8f08f0a990baa555c3c586fb8b277eba20.nq.gz
│   ├── 22cfd4e0c8f58677cbbedd50ea04cb15bb1339cd.nq.gz
│   ├── 24c7927b9d4f3271ae9282a8459f30fe619c0133.nq.gz
│   ├── 24ebe00fae0733639654d091f719ec85bcc95cdc.nq.gz
│   ├── 2509c225a512a17b74401fc05bd5f5bbd9592a8c.nq.gz
│   ├── 269194d6c770cd3ae00131164a2c1be882ba0075.nq.gz
│   ├── 313efc146cfc41edc04cb38a7595bd5b696be8c7.nq.gz
│   ├── 31634f40e8e20b8e777cc7e0067f7efad8488004.nq.gz
│   ├── 3480c6fc37b4412dd0dbe40cc4d6c4851e9a4230.nq.gz
│   ├── 37e7dfa9a87f375c587bc78dc6c264d67b1cee4e.nq.gz
│   ├── 39401ea2bec3b2dc53e0028e32c2b632ee029687.nq.gz
│   ├── 42a10d73821526c77844345c300a55ed298a02b2.nq.gz
│   ├── 4f288bef38e64949e57f30a1c602f9f60b0d7fc0.nq.gz
│   ├── 5651f7bab94e264fab92490167cb713be8aa57a4.nq.gz
│   ├── 6039326a022cec4903e2888206590746bb19cc33.nq.gz
│   ├── 60b4512588b0ec8a779f7250452b7e6003c8757a.nq.gz
│   ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
│   ├── 63a4d2ccd70a9c2a5159a3ec94b3e64225a29cda.nq.gz
│   ├── 6aab0713d17363edaeeeb10b4a1a756842e13055.nq.gz
│   ├── 6fa8c4b74a0008f6ddb1a08855b50c5d9265df93.nq.gz
│   ├── 75a271d9b79da8e2cf71636f338254542abeafbe.nq.gz
│   ├── 761df4ab0908746ac28dd57da49cb9d0e987192d.nq.gz
│   ├── 7a910df8623719f21f9ab2c091563d3d2560543e.nq.gz
│   ├── 7e3aba41a38e94d5d0192463528a6e93210d5ecf.nq.gz
│   ├── 7f0ccd774dd5fe5d02b2c2d5717b615eaf388eb0.nq.gz
│   ├── 84866b4243724a93c4851a6f157f2dc8b2827cdf.nq.gz
│   ├── 89acb90e08b1fd82c0a50e5488cec1a6ff53fc61.nq.gz
│   ├── 937748218ef2148d7041c039cfcfa0ad85c0cae1.nq.gz
│   ├── 96876c6f597f6e6c7325d78a47a16d9156484880.nq.gz
│   ├── 9e4e571fe88d119159f48cf0e3d780614cc98b6e.nq.gz
│   ├── 9fc361f2c6229afa70b5642b7faac4f4cdbedfd7.nq.gz
│   ├── a23a79ec614125080834098626d9c47b775657a9.nq.gz
│   ├── a23b5e248f09b85d1b2b3b80dc15ced82cde35e3.nq.gz
│   ├── a43543c86db859a300504dafeb6f9028b4c909de.nq.gz
│   ├── a46cfb3d158278baa42c08934644001b450a7966.nq.gz
│   ├── a7409b388157e019fa60e4a568e6cba4da7fa633.nq.gz
│   ├── aaeb34f01ab17de895918e2caf59085b860d66d4.nq.gz
│   ├── aaf1f5d34eddc7bc4d2bf603390d0a7f19a4352b.nq.gz
│   ├── ac6d2c38f176fe1b066f12b8da5353c02a287ab7.nq.gz
│   ├── acb395c45a4d624d74c0d6a7fa78ad09f3d5f01a.nq.gz
│   ├── aed7c18747a5de2e0386c21549618089a1762343.nq.gz
│   ├── b7b5f224feead03b866ad42dc414be9417fd3811.nq.gz
│   ├── b9261cd2fcfddffba4d4619b94631fcbf3afc86a.nq.gz
│   ├── b92ef59769e4de52e00dc1537493e0277da47e5f.nq.gz
│   ├── bae9c74f029629a832c11fd1854136d9690085f1.nq.gz
│   ├── bc8a4c08d2b82f63847b3a0710f5028ddb40851a.nq.gz
│   ├── bda69e836cd9e88609f7cc35ca189ce38d695f96.nq.gz
│   ├── be01a9fdb3a1736398f6ac98a70bdeeaff0db6fb.nq.gz
│   ├── c1be953bd0af79a0f0195513fb2940ad04a1cb7c.nq.gz
│   ├── c2f7943f4fa6b3ffb94760ff407cfa96f37fdf19.nq.gz
│   ├── c657986daf2dde0b14c9bc8a6b79aff8832ea089.nq.gz
│   ├── c7a80713a1c4bea78fe42ae04d3361d897b6bdda.nq.gz
│   ├── c8df048cb9d7f88265100ceb1a5947baeb43aa9a.nq.gz
│   ├── cadb53a512dc26cfccda0b872ea5f983d2a8e369.nq.gz
│   ├── cbc3b1eaadfb9c86213d588cf97588c7e5092775.nq.gz
│   ├── ced19a5183ad8d55436808aa9da963808632d3fe.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d238c48b629e103ad876648e2b2e562bad2612eb.nq.gz
│   ├── d3ec7a11389d774f1af444268115f52e0455d48b.nq.gz
│   ├── d6cf7d504db883f68fac8ca4d4d9619d2499f95c.nq.gz
│   ├── d6f5845c308b5628808b35393f1e2a7bfd496f2b.nq.gz
│   ├── db2472009c60acc72ca2f6f065bb4b674dc66746.nq.gz
│   ├── db41662749ab7222cefbb4cfe1167be750597a06.nq.gz
│   ├── dd01fe3a2efeeb5c435154507597413564250f2c.nq.gz
│   ├── df0b4f2bdb6ec19b41382465c23e84eb9375a4e0.nq.gz
│   ├── df93b144e71789ee5979b33a1a5600e902db0af4.nq.gz
│   ├── e32d1525f676811ba04930ce07923072f14aa662.nq.gz
│   ├── e4776795b999eaa8c493178ef57ce07088e5bbd2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7b0a712618f95630679f46fd0acf5ddf3201f04.nq.gz
│   ├── e7d08ab1910948e22d1d9be82adb69a6be791d83.nq.gz
│   ├── e7d64b7f380c2d968f3ae9b6d388356b111f60bc.nq.gz
│   ├── e94955b4e2794a3706ea4e79217a5022478ed5b9.nq.gz
│   ├── eb7d911b42f11933b15d332d55bf8532946ce9e5.nq.gz
│   ├── ec32fb957231d13807440d98e00ad9e9f8b1ebe3.nq.gz
│   ├── f094f1d98cd8d8c5b07088b7edd59f795634ba6f.nq.gz
│   ├── f50f23d8bca68e6aa7f33b8c4e1cbdc33aec44f1.nq.gz
│   ├── f78e9f14cd554b46703f4bb7197aa3be2e2aa709.nq.gz
│   ├── f93d4db9d040e30519303f02383b12201352ff41.nq.gz
│   ├── fa4e379b13ee15e011251bed0684ade65e1da226.nq.gz
│   ├── fae46082e276c09a9882bd85ca357106c26ae32d.nq.gz
│   ├── fcbcbb65256b5ca196739b1f00b37d2b9a7c6120.nq.gz
│   ├── fcde8143d4301ff3b47cdf79d6c86394e326a3b9.nq.gz
│   └── ff2f158010241f90dca8034bcf85960815647711.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 1aae569315eb170cdff00582644aca37ee38db62.nq.gz
├── filetree
│   └── 1aae569315eb170cdff00582644aca37ee38db62.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 108 files
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

[python-hyper/h2](https://github.com/python-hyper/h2)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
