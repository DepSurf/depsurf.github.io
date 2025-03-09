# Function: <code>__jbd2_journal_file_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581893280,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2327",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581893280,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 469
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
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582080816,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2312",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080816,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582170912,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2317",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170912,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582257440,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2335",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582257440,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582406464,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2338",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582406464,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2341",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582601859,
      "name": "__jbd2_journal_file_buffer.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582596800,
      "name": "__jbd2_journal_file_buffer",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2381",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582703602,
      "name": "__jbd2_journal_file_buffer.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582698464,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2415",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582876745,
      "name": "__jbd2_journal_file_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582871104,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2424",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983236,
      "name": "__jbd2_journal_file_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582977840,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2483",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299591,
      "name": "__jbd2_journal_file_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583294480,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2481",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591349163,
      "name": "__jbd2_journal_file_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583409840,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2486",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591291952,
      "name": "__jbd2_journal_file_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583432528,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2486",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592273012,
      "name": "__jbd2_journal_file_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583781840,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2504",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594054912,
      "name": "__jbd2_journal_file_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071584345360,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584995072,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2512",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584995072,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585223008,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2491",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585223008,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585455952,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2501",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585455952,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 503
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
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494656816,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2424",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494656816,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228100424,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2424",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228100424,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288470720,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2424",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288470720,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274021750,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2424",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274021750,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2424",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951972,
      "name": "__jbd2_journal_file_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582946576,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2424",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582889124,
      "name": "__jbd2_journal_file_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582883728,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2424",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940580,
      "name": "__jbd2_journal_file_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071582935184,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void __jbd2_journal_file_buffer(struct journal_head * jh, transaction_t * transaction, int jlist)
```

```json
{
  "name": "__jbd2_journal_file_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__jbd2_journal_file_buffer",
      "external": true,
      "loc": "fs/jbd2/transaction.c:2424",
      "file": "fs/jbd2/transaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583028675,
      "name": "__jbd2_journal_file_buffer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071583022624,
      "name": "__jbd2_journal_file_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
