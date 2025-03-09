# Function: <code>try_to_free_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581219152,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3214",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581219152,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386960,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3273",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386960,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464880,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3314",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464880,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581520176,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3299",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581520176,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581661520,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3267",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:try_to_release_page",
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661520,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581824976,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3238",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824976,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581912112,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3250",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912112,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582049248,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3257",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582049248,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582127104,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3234",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582127104,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582366528,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3244",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:try_to_release_page",
        "mm/vmscan.c:pageout",
        "mm/migrate.c:__unmap_and_move",
        "fs/buffer.c:grow_dev_page",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:release_buffer_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582366528,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582425312,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3225",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:try_to_release_page",
        "mm/vmscan.c:pageout",
        "mm/migrate.c:__unmap_and_move",
        "fs/buffer.c:grow_dev_page",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:release_buffer_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582425312,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582452992,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3246",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:try_to_release_page",
        "mm/vmscan.c:pageout",
        "mm/migrate.c:__unmap_and_move",
        "fs/buffer.c:grow_dev_page",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:release_buffer_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452992,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582775632,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3225",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:try_to_release_page",
        "mm/vmscan.c:pageout",
        "mm/migrate.c:__unmap_and_move",
        "fs/buffer.c:grow_dev_page",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:release_buffer_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582775632,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
bool try_to_free_buffers(struct folio * folio)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583316144,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3210",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_release_folio",
        "mm/vmscan.c:pageout",
        "fs/buffer.c:grow_dev_page",
        "fs/ext4/inode.c:ext4_release_folio",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:release_buffer_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583316144,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
bool try_to_free_buffers(struct folio * folio)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583899920,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:2815",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_release_folio",
        "mm/vmscan.c:pageout",
        "fs/buffer.c:grow_dev_page",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:clean_page_buffers",
        "fs/ext4/inode.c:ext4_release_folio",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:release_buffer_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583899920,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
bool try_to_free_buffers(struct folio * folio)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584127776,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:2953",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_release_folio",
        "mm/vmscan.c:pageout",
        "mm/migrate.c:migrate_folio_unmap",
        "fs/buffer.c:__getblk_slow",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:clean_page_buffers",
        "fs/ext4/inode.c:ext4_release_folio",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127776,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
bool try_to_free_buffers(struct folio * folio)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584344400,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:2913",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_release_folio",
        "mm/vmscan.c:pageout",
        "mm/migrate.c:migrate_folio_unmap",
        "fs/buffer.c:__getblk_slow",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/inode.c:ext4_release_folio",
        "fs/jbd2/transaction.c:jbd2_journal_invalidate_folio",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344400,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493664120,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3234",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493664120,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227201964,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3234",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_slow",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227201964,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287269968,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3234",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:try_to_release_page",
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287269968,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273296948,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3234",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273296948,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582095840,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3234",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582095840,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582033312,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3234",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582033312,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582086320,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3234",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086320,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int try_to_free_buffers(struct page * page)
```

```json
{
  "name": "try_to_free_buffers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582159008,
      "name": "try_to_free_buffers",
      "external": true,
      "loc": "fs/buffer.c:3234",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_releasepage",
        "fs/ext4/inode.c:ext4_releasepage",
        "fs/ext4/super.c:bdev_try_to_free_page",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582159008,
      "name": "try_to_free_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
