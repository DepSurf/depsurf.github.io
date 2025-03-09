# Function: <code>madvise_cold_or_pageout_pte_range</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581486448,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:300",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486448,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2780
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
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581691728,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:301",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691728,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2822
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
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581736592,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:306",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581736592,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2815
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
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581764944,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:306",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764944,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2751
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:308",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582047584,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2766
    },
    {
      "addr": 18446744071592208463,
      "name": "madvise_cold_or_pageout_pte_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:323",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478576,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3628
    },
    {
      "addr": 18446744071593986209,
      "name": "madvise_cold_or_pageout_pte_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:337",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582992112,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4370
    },
    {
      "addr": 18446744071596038346,
      "name": "madvise_cold_or_pageout_pte_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:343",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202480,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2221
    },
    {
      "addr": 18446744071596560557,
      "name": "madvise_cold_or_pageout_pte_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:324",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583438016,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2383
    },
    {
      "addr": 18446744071597466250,
      "name": "madvise_cold_or_pageout_pte_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492904688,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:300",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492904688,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2384
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
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226696160,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:300",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226696160,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286307568,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:300",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286307568,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4484
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
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272829352,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:300",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272829352,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
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
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455296,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:300",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455296,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2780
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
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581397552,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:300",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397552,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2704
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
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446496,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:300",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446496,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2780
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
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "madvise_cold_or_pageout_pte_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510960,
      "name": "madvise_cold_or_pageout_pte_range",
      "external": false,
      "loc": "mm/madvise.c:300",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510960,
      "name": "madvise_cold_or_pageout_pte_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2784
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int madvise_cold_or_pageout_pte_range(pmd_t * pmd, long unsigned int addr, long unsigned int end, struct mm_walk * walk)
```
</details>
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
