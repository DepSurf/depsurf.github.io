# Function: <code>mutex_lock_io</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588315312,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1118",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588315312,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588880784,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1118",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588880784,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589261120,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1142",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589261120,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589503616,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1320",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589503616,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589964304,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1325",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589964304,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590191968,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1351",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590191968,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591208256,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1351",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:journal_reset",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591208256,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591703456,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1354",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:journal_reset",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591703456,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591643744,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1352",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:journal_reset",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591643744,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592817392,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:966",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:journal_reset",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592817392,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594724336,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1022",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:journal_reset",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594724336,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596474768,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1022",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:journal_reset",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596474768,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597013328,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1022",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:journal_reset",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597013328,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597942672,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1027",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:journal_reset",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597942672,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503932544,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1351",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503932544,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236546780,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1351",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236546780,
      "name": "mutex_lock_io",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297784976,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1351",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297784976,
      "name": "mutex_lock_io",
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279803058,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1351",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279803058,
      "name": "mutex_lock_io",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589794256,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1351",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589794256,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589516736,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1351",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589516736,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590237664,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1351",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590237664,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void mutex_lock_io(struct mutex * lock)
```

```json
{
  "name": "mutex_lock_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590285712,
      "name": "mutex_lock_io",
      "external": true,
      "loc": "kernel/locking/mutex.c:1351",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_flush",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_journal_destroy",
        "fs/jbd2/journal.c:jbd2_update_log_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590285712,
      "name": "mutex_lock_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void mutex_lock_io(struct mutex * lock)
```
</details>
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
