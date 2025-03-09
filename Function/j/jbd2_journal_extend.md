# Function: <code>jbd2_journal_extend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581890528,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:559",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/indirect.c:try_to_extend_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890528,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582078032,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:556",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582078032,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582168144,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:558",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582168144,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254736,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:565",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254736,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582403744,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:567",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582403744,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582594064,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:563",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582594064,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582695728,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:596",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582695728,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582868400,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:596",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582868400,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974944,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:599",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974944,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int jbd2_journal_extend(handle_t * handle, int nblocks, int revoke_records)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291696,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:641",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/extents.c:ext4_ext_try_to_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291696,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
int jbd2_journal_extend(handle_t * handle, int nblocks, int revoke_records)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407232,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:643",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/extents.c:ext4_ext_try_to_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407232,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int jbd2_journal_extend(handle_t * handle, int nblocks, int revoke_records)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583429936,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:648",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/extents.c:ext4_ext_try_to_merge",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583429936,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int jbd2_journal_extend(handle_t * handle, int nblocks, int revoke_records)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779296,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:665",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/extents.c:ext4_ext_try_to_merge",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779296,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
int jbd2_journal_extend(handle_t * handle, int nblocks, int revoke_records)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584342496,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:660",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_up",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584342496,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
int jbd2_journal_extend(handle_t * handle, int nblocks, int revoke_records)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584991984,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:660",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_up",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584991984,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int jbd2_journal_extend(handle_t * handle, int nblocks, int revoke_records)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585219984,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:660",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_up",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219984,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int jbd2_journal_extend(handle_t * handle, int nblocks, int revoke_records)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585452928,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:660",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits",
        "fs/ext4/extents.c:ext4_ext_try_to_merge_up",
        "fs/ext4/inode.c:__ext4_mark_inode_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585452928,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494652720,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:599",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494652720,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228096540,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:599",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228096540,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288466096,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:599",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_try_to_merge",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288466096,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274018792,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:599",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274018792,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943680,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:599",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943680,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880832,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:599",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880832,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582932288,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:599",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582932288,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int jbd2_journal_extend(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_extend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583019488,
      "name": "jbd2_journal_extend",
      "external": true,
      "loc": "fs/jbd2/transaction.c:599",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/indirect.c:ext4_clear_blocks",
        "fs/ext4/inode.c:ext4_mark_inode_dirty",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583019488,
      "name": "jbd2_journal_extend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int revoke_records</code>
</li>
</ul>
</details>
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
