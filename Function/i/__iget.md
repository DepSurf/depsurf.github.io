# Function: <code>__iget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581102818,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:380",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:find_inode",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:insert_inode_locked"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/inode_mark.c:fsnotify_unmount_inodes",
        "fs/notify/inode_mark.c:fsnotify_unmount_inodes",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581109200,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581272742,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:388",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/inode_mark.c:fsnotify_unmount_inodes",
        "fs/notify/inode_mark.c:fsnotify_unmount_inodes",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274832,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581350726,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:390",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/inode_mark.c:fsnotify_unmount_inodes",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352912,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581406335,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:388",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408640,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581547937,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:388",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked4",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581550240,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581705140,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:394",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581706160,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581792000,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:394",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793008,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581910609,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:407",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911616,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581983137,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:411",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581984144,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582217441,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:412",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:wait_sb_inodes",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:add_dquot_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214160,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582264865,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:413",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:wait_sb_inodes",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:add_dquot_ref"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261616,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582290129,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:413",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:wait_sb_inodes",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_unmount_inodes",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:dquot_load_quota_sb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582287216,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582608923,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:417",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:wait_sb_inodes",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "block/bdev.c:iterate_bdevs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582605888,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583140603,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:441",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_prepare_wbs_switch",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "block/bdev.c:sync_bdevs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583141536,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583712283,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:440",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_prepare_wbs_switch",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "block/bdev.c:sync_bdevs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583713200,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583929746,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:440",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_prepare_wbs_switch",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "block/bdev.c:sync_bdevs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930688,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584136514,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:441",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_prepare_wbs_switch",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:try_to_lock_encrypted_files",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "block/bdev.c:sync_bdevs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137456,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493492744,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:411",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493495104,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227052168,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:411",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227054464,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287054048,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:411",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287057888,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273168370,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:411",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273169954,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581951873,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:411",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581952880,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581889441,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:411",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890448,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581943185,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:411",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581944192,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __iget(struct inode * inode)
```

```json
{
  "name": "__iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582012641,
      "name": "__iget",
      "external": true,
      "loc": "fs/inode.c:411",
      "file": "fs/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:igrab",
        "fs/inode.c:inode_lru_isolate"
      ],
      "caller_func": [
        "fs/fs-writeback.c:sync_inodes_sb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/block_dev.c:iterate_bdevs",
        "fs/notify/fsnotify.c:fsnotify_sb_delete",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/drop_caches.c:drop_pagecache_sb",
        "fs/quota/dquot.c:vfs_load_quota_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582014240,
      "name": "__iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
