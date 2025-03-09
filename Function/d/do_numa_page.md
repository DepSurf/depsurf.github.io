# Function: <code>do_numa_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580677579,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3149",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580791534,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3343",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580855867,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3382",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580901207,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3586",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580998533,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3755",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581132289,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3800",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581213955,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3590",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581274704,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3639",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274704,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581333504,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3664",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581333504,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581531312,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:4025",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581531312,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
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
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581574960,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:4185",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574960,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 747
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
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581596560,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:4193",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581596560,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 967
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
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581872496,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:4339",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581872496,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 950
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
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582270704,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:4672",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270704,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
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
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582762560,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:4675",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582762560,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1128
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
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582978128,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:4702",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978128,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1122
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
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583153472,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:4920",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583153472,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1492
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492752896,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3664",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3664",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286092656,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3664",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286092656,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3664",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581302352,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3664",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302352,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581260212,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3664",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293552,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3664",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293552,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
vm_fault_t do_numa_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_numa_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357696,
      "name": "do_numa_page",
      "external": false,
      "loc": "mm/memory.c:3664",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357696,
      "name": "do_numa_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 793
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
vm_fault_t do_numa_page(struct vm_fault * vmf)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
vm_fault_t do_numa_page(struct vm_fault * vmf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
vm_fault_t do_numa_page(struct vm_fault * vmf)
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
vm_fault_t do_numa_page(struct vm_fault * vmf)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
vm_fault_t do_numa_page(struct vm_fault * vmf)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
