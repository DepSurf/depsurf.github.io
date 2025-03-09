# Function: <code>migrate_vma_collect_hole</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581240768,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate.c:2146",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581240768,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386880,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate.c:2158",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386880,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581471120,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate.c:2138",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471120,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650080,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate.c:2156",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650080,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581877572,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate.c:2163",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867344,
      "name": "migrate_vma_collect_hole",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581912048,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate.c:2313",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581912048,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581942160,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate.c:2297",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942160,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582247904,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate.c:2226",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582247904,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582736992,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate_device.c:34",
      "file": "mm/migrate_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582736992,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583267488,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate_device.c:35",
      "file": "mm/migrate_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583267488,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583487840,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate_device.c:35",
      "file": "mm/migrate_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583487840,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, int depth, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583681216,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate_device.c:35",
      "file": "mm/migrate_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681216,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286558144,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate.c:2156",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286558144,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581618816,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate.c:2156",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581618816,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581560144,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate.c:2156",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581560144,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581610128,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate.c:2156",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581610128,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "migrate_vma_collect_hole",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581676320,
      "name": "migrate_vma_collect_hole",
      "external": false,
      "loc": "mm/migrate.c:2156",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676320,
      "name": "migrate_vma_collect_hole",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int depth</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, end, walk</code> ➡️ <code>start, end, depth, walk</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
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
int migrate_vma_collect_hole(long unsigned int start, long unsigned int end, struct mm_walk * walk)
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
