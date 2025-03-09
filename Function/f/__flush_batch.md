# Function: <code>__flush_batch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581912828,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:182",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582099792,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:182",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582189884,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:182",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582275671,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:182",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582424845,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:182",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582615152,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:179",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582716896,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:179",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582888768,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:178",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582888768,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582995344,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:178",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582995344,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583311648,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:178",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311648,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583426864,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:180",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583426864,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583449552,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:180",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449552,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583799216,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:172",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583799216,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584363552,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:172",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584363552,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585014512,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:172",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585014512,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585242256,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:133",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242256,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585475568,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:121",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585475568,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494681456,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:178",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494681456,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228121284,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:178",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228121284,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288495888,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:178",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288495888,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274039478,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:178",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274039478,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582964080,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:178",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964080,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582901232,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:178",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582901232,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582952688,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:178",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952688,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void __flush_batch(journal_t * journal, int * batch_count)
```

```json
{
  "name": "__flush_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583041104,
      "name": "__flush_batch",
      "external": false,
      "loc": "fs/jbd2/checkpoint.c:178",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583041104,
      "name": "__flush_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void __flush_batch(journal_t * journal, int * batch_count)
```
</details>
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
