# Function: <code>__journal_abort_soft</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581931664,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2065",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581931664,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582118048,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2100",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118048,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582208288,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2070",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208288,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582293696,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2093",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582293696,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582442768,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2109",
      "file": "fs/jbd2/journal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442768,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2112",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582632752,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071582639075,
      "name": "__journal_abort_soft.cold.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2112",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582734496,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071582740819,
      "name": "__journal_abort_soft.cold.51",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2103",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582908288,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071582914763,
      "name": "__journal_abort_soft.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2106",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583014864,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071583021339,
      "name": "__journal_abort_soft.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494706024,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2106",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494706024,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228143416,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2106",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228143416,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288527072,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2106",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288527072,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274058702,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2106",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274058702,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2106",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983600,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071582990075,
      "name": "__journal_abort_soft.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2106",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582920752,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071582927227,
      "name": "__journal_abort_soft.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2106",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582972208,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071582978683,
      "name": "__journal_abort_soft.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void __journal_abort_soft(journal_t * journal, int errno)
```

```json
{
  "name": "__journal_abort_soft",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__journal_abort_soft",
      "external": false,
      "loc": "fs/jbd2/journal.c:2106",
      "file": "fs/jbd2/journal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/journal.c:jbd2_write_superblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583060752,
      "name": "__journal_abort_soft",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071583067782,
      "name": "__journal_abort_soft.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __journal_abort_soft(journal_t * journal, int errno)
```
</details>
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
