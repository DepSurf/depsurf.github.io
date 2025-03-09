# Function: <code>jbd2_journal_get_descriptor_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * jbd2_journal_get_descriptor_buffer(journal_t * journal)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581934352,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:808",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934352,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582120912,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:811",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120912,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582210704,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:811",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582210704,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582296096,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:833",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296096,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582445168,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:849",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445168,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582635040,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:846",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582635040,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582736784,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:846",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582736784,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582910656,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:829",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582910656,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583017216,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:827",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017216,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583334544,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:830",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:write_one_revoke_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583334544,
      "name": "jbd2_journal_get_descriptor_buffer",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583452112,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:1009",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:write_one_revoke_record"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452112,
      "name": "jbd2_journal_get_descriptor_buffer",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583474528,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:1009",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583474528,
      "name": "jbd2_journal_get_descriptor_buffer",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583828672,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:1001",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583828672,
      "name": "jbd2_journal_get_descriptor_buffer",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584396112,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:1003",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584396112,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585050608,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:1006",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585050608,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585278560,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:1008",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585278560,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585512112,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:997",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_submit_commit_record",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585512112,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494709744,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:827",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494709744,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228146444,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:827",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228146444,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288531056,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:827",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288531056,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274061404,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:827",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274061404,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582985952,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:827",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582985952,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582923104,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:827",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582923104,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974560,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:827",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974560,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
struct buffer_head * jbd2_journal_get_descriptor_buffer(transaction_t * transaction, int type)
```

```json
{
  "name": "jbd2_journal_get_descriptor_buffer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583063216,
      "name": "jbd2_journal_get_descriptor_buffer",
      "external": true,
      "loc": "fs/jbd2/journal.c:827",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583063216,
      "name": "jbd2_journal_get_descriptor_buffer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>transaction_t * transaction</code>
</li>
<li>
<b>Param added. </b>
<code>int type</code>
</li>
<li>
<b>Param removed. </b>
<code>journal_t * journal</code>
</li>
</ul>
</details>
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
