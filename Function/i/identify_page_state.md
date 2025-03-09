# Function: <code>identify_page_state</code>

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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581221808,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1025",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581221808,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581352496,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1025",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352496,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1058",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581500560,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071581509964,
      "name": "identify_page_state.cold.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1060",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586528,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071581595827,
      "name": "identify_page_state.cold.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1057",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581697360,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071581706926,
      "name": "identify_page_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1061",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581770800,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071581780362,
      "name": "identify_page_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1084",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581992304,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071582002325,
      "name": "identify_page_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1175",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582041872,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071591337936,
      "name": "identify_page_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1235",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582068176,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071591280547,
      "name": "identify_page_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582378272,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1377",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582378272,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582878752,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1462",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582878752,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583428288,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1523",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583428288,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583649392,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1651",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583649392,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583844208,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1662",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583844208,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493228312,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1061",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493228312,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286744320,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1061",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286744320,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1061",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739536,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071581749098,
      "name": "identify_page_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1061",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678176,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071581687722,
      "name": "identify_page_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1061",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730848,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071581740410,
      "name": "identify_page_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```

```json
{
  "name": "identify_page_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "identify_page_state",
      "external": false,
      "loc": "mm/memory-failure.c:1061",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799136,
      "name": "identify_page_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071581808666,
      "name": "identify_page_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int identify_page_state(long unsigned int pfn, struct page * p, long unsigned int page_flags)
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
