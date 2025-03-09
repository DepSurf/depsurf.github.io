# Function: <code>jbd2_journal_restart</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581890400,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:683",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890400,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582077904,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:680",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582077904,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582168016,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:682",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582168016,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254608,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:695",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254608,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582403616,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:698",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582403616,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582593936,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:694",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593936,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582695600,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:727",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582695600,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582868272,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:727",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582868272,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974816,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:730",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974816,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291248,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:809",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291248,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406784,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:811",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406784,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583429504,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:816",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583429504,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583778864,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:833",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583778864,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584342336,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:825",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584342336,
      "name": "jbd2_journal_restart",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584991776,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:825",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584991776,
      "name": "jbd2_journal_restart",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585219776,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:825",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219776,
      "name": "jbd2_journal_restart",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585452720,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:825",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585452720,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494652552,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:730",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_swap_inode_data",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494652552,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228096408,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:730",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228096408,
      "name": "jbd2_journal_restart",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288464464,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:730",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288464464,
      "name": "jbd2_journal_restart",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274018628,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:730",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274018628,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943552,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:730",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943552,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880704,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:730",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880704,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582932160,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:730",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582932160,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int jbd2_journal_restart(handle_t * handle, int nblocks)
```

```json
{
  "name": "jbd2_journal_restart",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583018416,
      "name": "jbd2_journal_restart",
      "external": true,
      "loc": "fs/jbd2/transaction.c:730",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:finish_range",
        "fs/ext4/resize.c:update_backups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583018416,
      "name": "jbd2_journal_restart",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
