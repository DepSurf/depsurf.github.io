# Function: <code>filemap_fdatawait_keep_errors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580480928,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:411",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580480928,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580560240,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:490",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580560240,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580627616,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:455",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627616,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580642944,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:481",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580642944,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580725232,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:599",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580725232,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580861008,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:599",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580861008,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935600,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:576",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935600,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021824,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:613",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021824,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581077072,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:619",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581077072,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581264016,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:619",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wait_sb_inodes",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581264016,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581306192,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:620",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wait_sb_inodes",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581306192,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323776,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:611",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wait_sb_inodes",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323776,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581569360,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:629",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wait_sb_inodes",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581569360,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581924848,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:617",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "block/bdev.c:sync_bdevs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581924848,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582363632,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:614",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "block/bdev.c:sync_bdevs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582363632,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571840,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:621",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "block/bdev.c:sync_bdevs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571840,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582741632,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:616",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "block/bdev.c:sync_bdevs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582741632,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492443808,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:619",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492443808,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226316332,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:619",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226316332,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285712832,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:619",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285712832,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272516696,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:619",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272516696,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581045920,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:619",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045920,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993200,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:619",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993200,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037120,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:619",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037120,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space * mapping)
```

```json
{
  "name": "filemap_fdatawait_keep_errors",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581098704,
      "name": "filemap_fdatawait_keep_errors",
      "external": true,
      "loc": "mm/filemap.c:619",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/sync.c:fdatawait_one_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098704,
      "name": "filemap_fdatawait_keep_errors",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
