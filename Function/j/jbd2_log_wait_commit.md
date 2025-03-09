# Function: <code>jbd2_log_wait_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581919856,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:689",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_journal_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581919856,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109616,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:690",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109616,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582199776,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:690",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582199776,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582285184,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:699",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285184,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582434240,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:698",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434240,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582624784,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:695",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624784,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582726528,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:695",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582726528,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582900112,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:678",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582900112,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583006688,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:676",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006688,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583326304,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:675",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583326304,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583442960,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:681",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583442960,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583465152,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:681",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583465152,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583817696,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:681",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583817696,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584383888,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:681",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584383888,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585036928,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:678",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585036928,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585264528,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:677",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585264528,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585497760,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:666",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585497760,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494701416,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:676",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494701416,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228142004,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:676",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228142004,
      "name": "jbd2_log_wait_commit",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288514624,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:676",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288514624,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274050284,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:676",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274050284,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582975424,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:676",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582975424,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912576,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:676",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912576,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582964032,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:676",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964032,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int jbd2_log_wait_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_wait_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583052560,
      "name": "jbd2_log_wait_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:676",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583052560,
      "name": "jbd2_log_wait_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
