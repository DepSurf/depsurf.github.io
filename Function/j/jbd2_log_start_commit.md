# Function: <code>jbd2_log_start_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581930992,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:531",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:jbd2_complete_transaction"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581930992,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582117797,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:532",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582117376,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582208037,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:532",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582207616,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582293451,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:541",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582293024,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582442523,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:540",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442096,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582632192,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:537",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582632192,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582733936,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:537",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733936,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582907712,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:520",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582907712,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583014288,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:518",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014288,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583334148,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:517",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583331616,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583451284,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:521",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448752,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583473700,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:521",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583470944,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583826855,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:521",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824384,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584394173,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:521",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584391520,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585045069,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:518",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585048784,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585273933,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:517",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585276688,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585504618,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:506",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585510240,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494704880,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:518",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494704880,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228142588,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:518",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228142588,
      "name": "jbd2_log_start_commit",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288525936,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:518",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288525936,
      "name": "jbd2_log_start_commit",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274058092,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:518",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_complete_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274058092,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582983024,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:518",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983024,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582920176,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:518",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582920176,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582971632,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:518",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582971632,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int jbd2_log_start_commit(journal_t * journal, tid_t tid)
```

```json
{
  "name": "jbd2_log_start_commit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583060144,
      "name": "jbd2_log_start_commit",
      "external": true,
      "loc": "fs/jbd2/journal.c:518",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583060144,
      "name": "jbd2_log_start_commit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
