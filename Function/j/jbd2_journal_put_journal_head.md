# Function: <code>jbd2_journal_put_journal_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581937840,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2528",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937840,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124672,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2545",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124672,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582214448,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2515",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214448,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582299616,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2538",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582299616,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448656,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2554",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448656,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2564",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582639475,
      "name": "jbd2_journal_put_journal_head.cold.57",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071582638368,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2564",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582741219,
      "name": "jbd2_journal_put_journal_head.cold.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071582740112,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2552",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915159,
      "name": "jbd2_journal_put_journal_head.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071582913936,
      "name": "jbd2_journal_put_journal_head",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2547",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583021716,
      "name": "jbd2_journal_put_journal_head.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071583020512,
      "name": "jbd2_journal_put_journal_head",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2583",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583339056,
      "name": "jbd2_journal_put_journal_head.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583337904,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2830",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591351148,
      "name": "jbd2_journal_put_journal_head.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583455568,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2830",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591294032,
      "name": "jbd2_journal_put_journal_head.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583478016,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:3010",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592275373,
      "name": "jbd2_journal_put_journal_head.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071583831984,
      "name": "jbd2_journal_put_journal_head",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:3013",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594057208,
      "name": "jbd2_journal_put_journal_head.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071584399680,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585054496,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:3016",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585054496,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585282560,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:3016",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585282560,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585516192,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:3003",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585516192,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494714248,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2547",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494714248,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228150928,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2547",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228150928,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288536400,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2547",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288536400,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274065156,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2547",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274065156,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2547",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990452,
      "name": "jbd2_journal_put_journal_head.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071582989248,
      "name": "jbd2_journal_put_journal_head",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2547",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582927604,
      "name": "jbd2_journal_put_journal_head.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071582926400,
      "name": "jbd2_journal_put_journal_head",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2547",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979060,
      "name": "jbd2_journal_put_journal_head.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071582977856,
      "name": "jbd2_journal_put_journal_head",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void jbd2_journal_put_journal_head(struct journal_head * jh)
```

```json
{
  "name": "jbd2_journal_put_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_put_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2547",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/checkpoint.c:__jbd2_journal_remove_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068159,
      "name": "jbd2_journal_put_journal_head.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071583066880,
      "name": "jbd2_journal_put_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
