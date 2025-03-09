# Function: <code>wp_page_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580664864,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2060",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664864,
      "name": "wp_page_copy.isra.56",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1349
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
int wp_page_copy(struct fault_env * fe, pte_t orig_pte, struct page * old_page)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580774496,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2138",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774496,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1723
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
int wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580839184,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2143",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839184,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1821
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
int wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884752,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2349",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884752,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1570
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
int wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580978560,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2466",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978560,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1914
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
int wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113456,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2508",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113456,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1840
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581192800,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2244",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192800,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1924
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581265664,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2298",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265664,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1999
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581324512,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2322",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324512,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1927
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581519360,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2651",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519360,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1610
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581564416,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2829",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564416,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1574
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581586608,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2890",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581586608,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1485
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581850544,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2985",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581850544,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1387
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582243680,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:3083",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582243680,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1792
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582739504,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:3063",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582739504,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1902
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582954976,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:3062",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582954976,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1575
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583130256,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:3117",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130256,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1575
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492731200,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2322",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492731200,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2028
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226561780,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2322",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226561780,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1696
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286077360,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2322",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286077360,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2896
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272719906,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2322",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272719906,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1446
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293360,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2322",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293360,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1927
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237776,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2322",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237776,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1847
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581284560,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2322",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284560,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1927
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
vm_fault_t wp_page_copy(struct vm_fault * vmf)
```

```json
{
  "name": "wp_page_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581348496,
      "name": "wp_page_copy",
      "external": false,
      "loc": "mm/memory.c:2322",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348496,
      "name": "wp_page_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2137
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
int wp_page_copy(struct fault_env * fe, pte_t orig_pte, struct page * old_page)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault * vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fault_env * fe</code>
</li>
<li>
<b>Param removed. </b>
<code>pte_t orig_pte</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * old_page</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
