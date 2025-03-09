# Function: <code>init_unavailable_range</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
u64 init_unavailable_range(long unsigned int spfn, long unsigned int epfn)
```

```json
{
  "name": "init_unavailable_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609234494,
      "name": "init_unavailable_range",
      "external": false,
      "loc": "mm/page_alloc.c:6920",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:init_unavailable_mem",
        "mm/page_alloc.c:init_unavailable_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609234494,
      "name": "init_unavailable_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 192
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
u64 init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node)
```

```json
{
  "name": "init_unavailable_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591683011,
      "name": "init_unavailable_range",
      "external": false,
      "loc": "mm/page_alloc.c:6275",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init",
        "mm/page_alloc.c:memmap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591683011,
      "name": "init_unavailable_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node)
```

```json
{
  "name": "init_unavailable_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614441461,
      "name": "init_unavailable_range",
      "external": false,
      "loc": "mm/page_alloc.c:6477",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init",
        "mm/page_alloc.c:memmap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614441461,
      "name": "init_unavailable_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 186
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
void init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node)
```

```json
{
  "name": "init_unavailable_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615383253,
      "name": "init_unavailable_range",
      "external": false,
      "loc": "mm/page_alloc.c:6660",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init",
        "mm/page_alloc.c:memmap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615383253,
      "name": "init_unavailable_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 225
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
void init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node)
```

```json
{
  "name": "init_unavailable_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617170500,
      "name": "init_unavailable_range",
      "external": false,
      "loc": "mm/page_alloc.c:6781",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init",
        "mm/page_alloc.c:memmap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617170500,
      "name": "init_unavailable_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 216
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
void init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node)
```

```json
{
  "name": "init_unavailable_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627859712,
      "name": "init_unavailable_range",
      "external": false,
      "loc": "mm/page_alloc.c:6954",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init",
        "mm/page_alloc.c:memmap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627859712,
      "name": "init_unavailable_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 536
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
void init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node)
```

```json
{
  "name": "init_unavailable_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619609712,
      "name": "init_unavailable_range",
      "external": false,
      "loc": "mm/mm_init.c:807",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:memmap_init",
        "mm/mm_init.c:memmap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619609712,
      "name": "init_unavailable_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 536
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
void init_unavailable_range(long unsigned int spfn, long unsigned int epfn, int zone, int node)
```

```json
{
  "name": "init_unavailable_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621913792,
      "name": "init_unavailable_range",
      "external": false,
      "loc": "mm/mm_init.c:818",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:memmap_init",
        "mm/mm_init.c:memmap_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621913792,
      "name": "init_unavailable_range",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 611
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
u64 init_unavailable_range(long unsigned int spfn, long unsigned int epfn)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int zone</code>
</li>
<li>
<b>Param added. </b>
<code>int node</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>u64</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
