# Function: <code>do_huge_pmd_anonymous_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_huge_pmd_anonymous_page(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, unsigned int flags)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907872,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:808",
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
      "addr": 18446744071580907872,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1407
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
int do_huge_pmd_anonymous_page(struct fault_env * fe)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581024816,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:581",
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
      "addr": 18446744071581024816,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1561
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
int do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099904,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:654",
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
      "addr": 18446744071581099904,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1620
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
int do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581148704,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:669",
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
      "addr": 18446744071581148704,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1639
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
int do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269216,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:669",
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
      "addr": 18446744071581269216,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1797
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
int do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581418064,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:666",
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
      "addr": 18446744071581418064,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1960
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504128,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:685",
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
      "addr": 18446744071581504128,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1841
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581613568,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:701",
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
      "addr": 18446744071581613568,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2009
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684480,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:707",
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
      "addr": 18446744071581684480,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1951
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902752,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:716",
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
      "addr": 18446744071581902752,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 915
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581948928,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:709",
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
      "addr": 18446744071581948928,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1166
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974640,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:724",
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
      "addr": 18446744071581974640,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 965
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582277312,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:724",
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
      "addr": 18446744071582277312,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 999
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582761216,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:719",
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
      "addr": 18446744071582761216,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 855
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583295168,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:779",
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
      "addr": 18446744071583295168,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583514272,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:779",
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
      "addr": 18446744071583514272,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 810
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583708064,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:994",
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
      "addr": 18446744071583708064,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493131848,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:707",
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
      "addr": 18446603336493131848,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286610800,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:707",
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
      "addr": 13835058055286610800,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2848
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581653216,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:707",
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
      "addr": 18446744071581653216,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1951
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581593440,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:707",
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
      "addr": 18446744071581593440,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1913
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581644528,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:707",
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
      "addr": 18446744071581644528,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1951
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
```

```json
{
  "name": "do_huge_pmd_anonymous_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581710944,
      "name": "do_huge_pmd_anonymous_page",
      "external": true,
      "loc": "mm/huge_memory.c:707",
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
      "addr": 18446744071581710944,
      "name": "do_huge_pmd_anonymous_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1938
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
<b>Param removed. </b>
<code>unsigned int flags</code>
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
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
vm_fault_t do_huge_pmd_anonymous_page(struct vm_fault * vmf)
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
