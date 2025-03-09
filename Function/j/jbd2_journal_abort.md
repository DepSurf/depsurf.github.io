# Function: <code>jbd2_journal_abort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581931760,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2129",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/super.c:__ext4_abort",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581931760,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582118688,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2164",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/super.c:__ext4_abort",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118144,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582208930,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2134",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/super.c:__ext4_abort",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208384,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582294309,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2157",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582293792,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582443384,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2173",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442864,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582633428,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2186",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582632912,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582735172,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2186",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582734656,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582908976,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2177",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582908464,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583015536,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2172",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015024,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2156",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583338550,
      "name": "jbd2_journal_abort.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071583331792,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2403",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591350659,
      "name": "jbd2_journal_abort.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071583448928,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2403",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591293543,
      "name": "jbd2_journal_abort.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071583471120,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2582",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592274847,
      "name": "jbd2_journal_abort.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071583824560,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2585",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594056738,
      "name": "jbd2_journal_abort.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071584391728,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585046240,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2588",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/ioctl.c:ext4_shutdown",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585046240,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585275072,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2588",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_force_shutdown",
        "fs/ext4/ioctl.c:ext4_force_shutdown",
        "fs/ext4/super.c:ext4_journal_bmap",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585275072,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585505792,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2575",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_force_shutdown",
        "fs/ext4/ioctl.c:ext4_force_shutdown",
        "fs/ext4/super.c:ext4_journal_bmap",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585505792,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494706876,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2172",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494706368,
      "name": "jbd2_journal_abort",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228144188,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2172",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228143636,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288528040,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2172",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288527360,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274059312,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2172",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274058880,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582984272,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2172",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983760,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582921424,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2172",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582920912,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582972880,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2172",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582972368,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void jbd2_journal_abort(journal_t * journal, int errno)
```

```json
{
  "name": "jbd2_journal_abort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583061492,
      "name": "jbd2_journal_abort",
      "external": true,
      "loc": "fs/jbd2/journal.c:2172",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ext4/super.c:ext4_handle_error",
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583060960,
      "name": "jbd2_journal_abort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
