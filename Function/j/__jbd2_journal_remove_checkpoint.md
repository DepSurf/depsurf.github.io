# Function: <code>__jbd2_journal_remove_checkpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911744,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:551",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911744,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582098736,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:551",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582098736,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582188832,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:551",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188832,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582274624,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:551",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582274624,
      "name": "__jbd2_journal_remove_checkpoint",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582423792,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:551",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582423792,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582614128,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:548",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614128,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582715872,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:548",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582715872,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582889536,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:560",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582889536,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582996112,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:560",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996112,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583312432,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:560",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312432,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583427584,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:562",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427584,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583450256,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:562",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583450256,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583800016,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:674",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583800016,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584364544,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:674",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584364544,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585015648,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:674",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015648,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585243344,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:558",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint",
        "fs/jbd2/checkpoint.c:journal_shrink_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585243344,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585476640,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:554",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint",
        "fs/jbd2/checkpoint.c:journal_shrink_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476640,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494682336,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:560",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494682336,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228122192,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:560",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228122192,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288497168,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:560",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288497168,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274040134,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:560",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274040134,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582964848,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:560",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964848,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582902000,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:560",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582902000,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582953456,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:560",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953456,
      "name": "__jbd2_journal_remove_checkpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int __jbd2_journal_remove_checkpoint(struct journal_head * jh)
```

```json
{
  "name": "__jbd2_journal_remove_checkpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583041904,
      "name": "__jbd2_journal_remove_checkpoint",
      "external": true,
      "loc": "fs/jbd2/checkpoint.c:560",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:journal_clean_one_cp_list",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583041904,
      "name": "__jbd2_journal_remove_checkpoint",
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
