# Function: <code>__bpf_trace_jbd2_commit</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582624576,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582624576,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582726320,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582726320,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582899872,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582899872,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583006448,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006448,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583322912,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322912,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583439328,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439328,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583461760,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583461760,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583813808,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583813808,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584383392,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584383392,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585036192,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585036192,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585263792,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585263792,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585497024,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585497024,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494691952,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494691952,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228133348,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228133348,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288514064,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288514064,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582975184,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582975184,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912336,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912336,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582963792,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582963792,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```

```json
{
  "name": "__bpf_trace_jbd2_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583052320,
      "name": "__bpf_trace_jbd2_commit",
      "external": false,
      "loc": "include/trace/events/jbd2.h:34",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583052320,
      "name": "__bpf_trace_jbd2_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __bpf_trace_jbd2_commit(void * __data, journal_t * journal, transaction_t * commit_transaction)
```
</details>
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
