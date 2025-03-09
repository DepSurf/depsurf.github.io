# Function: <code>do_huge_pmd_wp_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_huge_pmd_wp_page(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580910912,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1151",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580910912,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2915
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
int do_huge_pmd_wp_page(struct fault_env * fe, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035008,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:936",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035008,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3647
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
int do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581110208,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1015",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110208,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3625
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
int do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581158560,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1218",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581158560,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3272
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
int do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581282800,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1242",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581282800,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4493
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
int do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431440,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1239",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431440,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2944
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581514928,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1253",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514928,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2963
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581624576,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1309",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581624576,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3106
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581695440,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1315",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695440,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3072
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581913552,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1255",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913552,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 862
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581960432,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1275",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960432,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986352,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1281",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986352,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582288416,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1283",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582288416,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582772096,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1260",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582772096,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1665
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583306720,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1309",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583306720,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 983
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583526336,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1294",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583526336,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 961
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583720720,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1511",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720720,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1019
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493139432,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1315",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493139432,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2716
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286624288,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1315",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286624288,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4752
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581664176,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1315",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664176,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3072
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581603920,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1315",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581603920,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2901
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581655488,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1315",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655488,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3072
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "do_huge_pmd_wp_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581721888,
      "name": "do_huge_pmd_wp_page",
      "external": true,
      "loc": "mm/huge_memory.c:1315",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721888,
      "name": "do_huge_pmd_wp_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3056
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fault_env * fe</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Param removed. </b>
<code>pmd_t * pmd</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, vma, address, pmd, orig_pmd</code> ➡️ <code>fe, orig_pmd</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>pmd_t orig_pmd</code>
</li>
</ul>
</details>
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
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
vm_fault_t do_huge_pmd_wp_page(struct vm_fault * vmf, pmd_t orig_pmd)
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
