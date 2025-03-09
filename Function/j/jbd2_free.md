# Function: <code>jbd2_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581936336,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2322",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936336,
      "name": "jbd2_free",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123184,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2349",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123184,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582212960,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2319",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582212960,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582298256,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2342",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582298256,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582447328,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2358",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582447328,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582637056,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2370",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582637056,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582738800,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2370",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582738800,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582912576,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2361",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912576,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583019152,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2356",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583019152,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583336878,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2385",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583337472,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583454208,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2632",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583454208,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583476624,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2632",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583476624,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583830944,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2811",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583830944,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584398544,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2814",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584398544,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585053328,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2817",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585053328,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585281392,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2817",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585281392,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585514960,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2804",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585514960,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494712344,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2356",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494712344,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228149028,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2356",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228149028,
      "name": "jbd2_free",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288534016,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2356",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288534016,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274063610,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2356",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274063610,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582987888,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2356",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582987888,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582925040,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2356",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582925040,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582976496,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2356",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582976496,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void jbd2_free(void * ptr, size_t size)
```

```json
{
  "name": "jbd2_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583065184,
      "name": "jbd2_free",
      "external": true,
      "loc": "fs/jbd2/journal.c:2356",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583065184,
      "name": "jbd2_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
