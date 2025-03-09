# Function: <code>__jbd2_fc_end_commit</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __jbd2_fc_end_commit(journal_t * journal, tid_t tid, bool fallback)
```

```json
{
  "name": "__jbd2_fc_end_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583451541,
      "name": "__jbd2_fc_end_commit",
      "external": false,
      "loc": "fs/jbd2/journal.c:769",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_fc_end_commit"
      ],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_fc_end_commit_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583451312,
      "name": "__jbd2_fc_end_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int __jbd2_fc_end_commit(journal_t * journal, tid_t tid, bool fallback)
```

```json
{
  "name": "__jbd2_fc_end_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583473957,
      "name": "__jbd2_fc_end_commit",
      "external": false,
      "loc": "fs/jbd2/journal.c:769",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_fc_end_commit"
      ],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_fc_end_commit_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583473728,
      "name": "__jbd2_fc_end_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int __jbd2_fc_end_commit(journal_t * journal, tid_t tid, bool fallback)
```

```json
{
  "name": "__jbd2_fc_end_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583827125,
      "name": "__jbd2_fc_end_commit",
      "external": false,
      "loc": "fs/jbd2/journal.c:769",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_fc_end_commit"
      ],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_fc_end_commit_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826896,
      "name": "__jbd2_fc_end_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int __jbd2_fc_end_commit(journal_t * journal, tid_t tid, bool fallback)
```

```json
{
  "name": "__jbd2_fc_end_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584394208,
      "name": "__jbd2_fc_end_commit",
      "external": false,
      "loc": "fs/jbd2/journal.c:770",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_fc_end_commit_fallback",
        "fs/jbd2/journal.c:jbd2_fc_end_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584394208,
      "name": "__jbd2_fc_end_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
int __jbd2_fc_end_commit(journal_t * journal, tid_t tid, bool fallback)
```

```json
{
  "name": "__jbd2_fc_end_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585045120,
      "name": "__jbd2_fc_end_commit",
      "external": false,
      "loc": "fs/jbd2/journal.c:767",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_fc_end_commit_fallback",
        "fs/jbd2/journal.c:jbd2_fc_end_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585045120,
      "name": "__jbd2_fc_end_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
int __jbd2_fc_end_commit(journal_t * journal, tid_t tid, bool fallback)
```

```json
{
  "name": "__jbd2_fc_end_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585273984,
      "name": "__jbd2_fc_end_commit",
      "external": false,
      "loc": "fs/jbd2/journal.c:766",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_fc_end_commit_fallback",
        "fs/jbd2/journal.c:jbd2_fc_end_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585273984,
      "name": "__jbd2_fc_end_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
int __jbd2_fc_end_commit(journal_t * journal, tid_t tid, bool fallback)
```

```json
{
  "name": "__jbd2_fc_end_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585504672,
      "name": "__jbd2_fc_end_commit",
      "external": false,
      "loc": "fs/jbd2/journal.c:755",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_fc_end_commit_fallback",
        "fs/jbd2/journal.c:jbd2_fc_end_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585504672,
      "name": "__jbd2_fc_end_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int __jbd2_fc_end_commit(journal_t * journal, tid_t tid, bool fallback)
```
</details>
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
