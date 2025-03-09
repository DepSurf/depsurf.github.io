# Function: <code>memblock_alloc_internal</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604788434,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1373",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_nopanic",
        "mm/memblock.c:memblock_alloc_try_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604788434,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 332
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604892036,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1457",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604892036,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 146
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604925926,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1454",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604925926,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 161
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609240326,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1469",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw",
        "mm/memblock.c:memblock_alloc_exact_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609240326,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 183
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612306735,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1431",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw",
        "mm/memblock.c:memblock_alloc_exact_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612306735,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 183
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614446553,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1432",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw",
        "mm/memblock.c:memblock_alloc_exact_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614446553,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 182
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615389471,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1467",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw",
        "mm/memblock.c:memblock_alloc_exact_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615389471,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 182
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617179458,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1474",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw",
        "mm/memblock.c:memblock_alloc_exact_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617179458,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 203
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627871072,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1492",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw",
        "mm/memblock.c:memblock_alloc_exact_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627871072,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 268
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619636080,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1514",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw",
        "mm/memblock.c:memblock_alloc_exact_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619636080,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 268
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid, bool exact_nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621939488,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1572",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw",
        "mm/memblock.c:memblock_alloc_exact_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621939488,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 268
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510965128,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1454",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510965128,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243451632,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1454",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243451632,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 232
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302618560,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1454",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302618560,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 256
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270691496,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1454",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270691496,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 162
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604831386,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1454",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604831386,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 161
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604800447,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1454",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604800447,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 161
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604908570,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1454",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604908570,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 161
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
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```

```json
{
  "name": "memblock_alloc_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604930107,
      "name": "memblock_alloc_internal",
      "external": false,
      "loc": "mm/memblock.c:1454",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_alloc_try_nid",
        "mm/memblock.c:memblock_alloc_try_nid_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604930107,
      "name": "memblock_alloc_internal",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 161
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void * memblock_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool exact_nid</code>
</li>
</ul>
</details>
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
