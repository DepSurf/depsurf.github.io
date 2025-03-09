# Function: <code>jbd2_journal_grab_journal_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581937776,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2485",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937776,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124608,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2502",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124608,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582214384,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2472",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214384,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582299552,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2495",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582299552,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448592,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2511",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448592,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582638304,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2521",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582638304,
      "name": "jbd2_journal_grab_journal_head",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582740048,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2521",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582740048,
      "name": "jbd2_journal_grab_journal_head",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582913872,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2509",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582913872,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583020448,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2504",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583020448,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583337840,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2535",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583337840,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583455504,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2782",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583455504,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583477952,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2782",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583477952,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583817632,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2961",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583817632,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584391168,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2964",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584391168,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585043408,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2967",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585043408,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585272288,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2967",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585272288,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585504336,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2954",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585504336,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494714056,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2504",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494714056,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228150680,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2504",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228150680,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288536192,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2504",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288536192,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274065050,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2504",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274065050,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582989184,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2504",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582989184,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582926336,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2504",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582926336,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582977792,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2504",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582977792,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct journal_head * jbd2_journal_grab_journal_head(struct buffer_head * bh)
```

```json
{
  "name": "jbd2_journal_grab_journal_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583066768,
      "name": "jbd2_journal_grab_journal_head",
      "external": true,
      "loc": "fs/jbd2/journal.c:2504",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:__jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_set_triggers",
        "fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583066768,
      "name": "jbd2_journal_grab_journal_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
