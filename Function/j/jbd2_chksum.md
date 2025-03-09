# Function: <code>jbd2_chksum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581899683,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1472",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909298,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1472",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581914916,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1472",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581923351,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1472",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_superblock_csum",
        "fs/jbd2/journal.c:journal_get_superblock"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582089829,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1487",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096932,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1487",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582116127,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1487",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582179925,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1487",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582187028,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1487",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582206367,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1487",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582265915,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1489",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272973,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1489",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582291630,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1489",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582414965,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1595",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582422125,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1595",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582440702,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1595",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582605182,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1595",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612117,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1595",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582631022,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1595",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582706900,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1596",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713883,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1596",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582732846,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1596",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582880207,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1616",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582887342,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1616",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582906532,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1616",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582986705,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582993918,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583013220,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583300906,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1599",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583308363,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1599",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:scan_revoke_records",
        "fs/jbd2/recovery.c:scan_revoke_records",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583330889,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1599",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583415802,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1734",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583426093,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1734",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583446953,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1734",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583442000,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1743",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583448762,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1743",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583467767,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1743",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583791430,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1782",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583798415,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1782",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583818663,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1782",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584354553,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1774",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584362495,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1774",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584390739,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1774",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585004608,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1772",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585013215,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1772",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585048293,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1772",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585233209,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1773",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585241187,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1773",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585271170,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1773",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585466324,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1786",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585474415,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1786",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585503682,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1786",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_set_features",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:journal_load_superblock",
        "fs/jbd2/journal.c:journal_check_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494667880,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    },
    {
      "addr": 18446603336494677440,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ]
    },
    {
      "addr": 18446603336494693408,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_superblock_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494667880,
      "name": "jbd2_chksum.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336494667888,
      "name": "jbd2_chksum.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336494677440,
      "name": "jbd2_chksum.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336494677448,
      "name": "jbd2_chksum.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336494693408,
      "name": "jbd2_chksum.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    },
    {
      "addr": 18446603336494693416,
      "name": "jbd2_chksum.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u32 jbd2_chksum(journal_t * journal, u32 crc, const void * address, unsigned int length)
```

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228108804,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    },
    {
      "addr": 3228117124,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ]
    },
    {
      "addr": 3228135472,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228108804,
      "name": "jbd2_chksum.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 3228108820,
      "name": "jbd2_chksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3228117124,
      "name": "jbd2_chksum.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 3228117140,
      "name": "jbd2_chksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 3228135472,
      "name": "jbd2_chksum.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 3228135488,
      "name": "jbd2_chksum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288484712,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288494352,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288523504,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274031600,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274038044,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274056386,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_superblock_csum",
        "fs/jbd2/journal.c:jbd2_superblock_csum"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582955441,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582962654,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582981956,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582892593,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582899806,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582919108,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582944049,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582951262,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582970564,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "jbd2_chksum",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583032205,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583039685,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583059080,
      "name": "jbd2_chksum",
      "external": false,
      "loc": "include/linux/jbd2.h:1614",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:journal_get_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set",
        "fs/jbd2/journal.c:jbd2_descriptor_block_csum_set"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u32 jbd2_chksum(journal_t * journal, u32 crc, const void * address, unsigned int length)
```
</details>
</li>
</ul>
