# Function: <code>journal_submit_commit_record</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581899376,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:119",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899376,
      "name": "journal_submit_commit_record.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
int journal_submit_commit_record(journal_t * journal, transaction_t * commit_transaction, struct buffer_head * * cbh, __u32 crc32_sum)
```

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582086512,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:119",
      "file": "fs/jbd2/commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086512,
      "name": "journal_submit_commit_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
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
int journal_submit_commit_record(journal_t * journal, transaction_t * commit_transaction, struct buffer_head * * cbh, __u32 crc32_sum)
```

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582176608,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:119",
      "file": "fs/jbd2/commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176608,
      "name": "journal_submit_commit_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
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
int journal_submit_commit_record(journal_t * journal, transaction_t * commit_transaction, struct buffer_head * * cbh, __u32 crc32_sum)
```

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582263088,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:119",
      "file": "fs/jbd2/commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263088,
      "name": "journal_submit_commit_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
int journal_submit_commit_record(journal_t * journal, transaction_t * commit_transaction, struct buffer_head * * cbh, __u32 crc32_sum)
```

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582412128,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:119",
      "file": "fs/jbd2/commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582412128,
      "name": "journal_submit_commit_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
int journal_submit_commit_record(journal_t * journal, transaction_t * commit_transaction, struct buffer_head * * cbh, __u32 crc32_sum)
```

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582602336,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602336,
      "name": "journal_submit_commit_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582708314,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704080,
      "name": "journal_submit_commit_record.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582881657,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582877248,
      "name": "journal_submit_commit_record.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582988135,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983728,
      "name": "journal_submit_commit_record.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583305155,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583300256,
      "name": "journal_submit_commit_record.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583420356,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583415152,
      "name": "journal_submit_commit_record.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583442680,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583438208,
      "name": "journal_submit_commit_record.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583792110,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787424,
      "name": "journal_submit_commit_record.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int journal_submit_commit_record(journal_t * journal, transaction_t * commit_transaction, struct buffer_head * * cbh, __u32 crc32_sum)
```

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584351456,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:118",
      "file": "fs/jbd2/commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584351456,
      "name": "journal_submit_commit_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
int journal_submit_commit_record(journal_t * journal, transaction_t * commit_transaction, struct buffer_head * * cbh, __u32 crc32_sum)
```

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585001776,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:118",
      "file": "fs/jbd2/commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585001776,
      "name": "journal_submit_commit_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int journal_submit_commit_record(journal_t * journal, transaction_t * commit_transaction, struct buffer_head * * cbh, __u32 crc32_sum)
```

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585229024,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:114",
      "file": "fs/jbd2/commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585229024,
      "name": "journal_submit_commit_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
int journal_submit_commit_record(journal_t * journal, transaction_t * commit_transaction, struct buffer_head * * cbh, __u32 crc32_sum)
```

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585462016,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:114",
      "file": "fs/jbd2/commit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585462016,
      "name": "journal_submit_commit_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494672164,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494669064,
      "name": "journal_submit_commit_record.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228113356,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228108968,
      "name": "journal_submit_commit_record.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288486064,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288481696,
      "name": "journal_submit_commit_record.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274031236,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274028122,
      "name": "journal_submit_commit_record.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582956871,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952464,
      "name": "journal_submit_commit_record.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582894023,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582889616,
      "name": "journal_submit_commit_record.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582945479,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582941072,
      "name": "journal_submit_commit_record.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "journal_submit_commit_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583033793,
      "name": "journal_submit_commit_record",
      "external": false,
      "loc": "fs/jbd2/commit.c:116",
      "file": "fs/jbd2/commit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583029648,
      "name": "journal_submit_commit_record.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int journal_submit_commit_record(journal_t * journal, transaction_t * commit_transaction, struct buffer_head * * cbh, __u32 crc32_sum)
```
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int journal_submit_commit_record(journal_t * journal, transaction_t * commit_transaction, struct buffer_head * * cbh, __u32 crc32_sum)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int journal_submit_commit_record(journal_t * journal, transaction_t * commit_transaction, struct buffer_head * * cbh, __u32 crc32_sum)
```
</details>
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
