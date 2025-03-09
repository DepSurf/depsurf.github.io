# Function: <code>huge_pmd_set_accessed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void huge_pmd_set_accessed(struct mm_struct * mm, struct vm_area_struct * vma, long unsigned int address, pmd_t * pmd, pmd_t orig_pmd, int dirty)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580901376,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:988",
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
      "addr": 18446744071580901376,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void huge_pmd_set_accessed(struct fault_env * fe, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581027744,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:810",
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
      "addr": 18446744071581027744,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581102992,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:888",
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
      "addr": 18446744071581102992,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152672,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1091",
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
      "addr": 18446744071581152672,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581273696,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1103",
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
      "addr": 18446744071581273696,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422384,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1100",
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
      "addr": 18446744071581422384,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581508240,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1115",
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
      "addr": 18446744071581508240,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581617840,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1171",
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
      "addr": 18446744071581617840,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581688688,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1177",
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
      "addr": 18446744071581688688,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581906064,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1234",
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
      "addr": 18446744071581906064,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581951312,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1254",
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
      "addr": 18446744071581951312,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581976832,
      "name": "huge_pmd_set_accessed",
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
      "addr": 18446744071581976832,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void huge_pmd_set_accessed(struct vm_fault * vmf)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582279552,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1261",
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
      "addr": 18446744071582279552,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void huge_pmd_set_accessed(struct vm_fault * vmf)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582763440,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1238",
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
      "addr": 18446744071582763440,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void huge_pmd_set_accessed(struct vm_fault * vmf)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583297440,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1295",
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
      "addr": 18446744071583297440,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void huge_pmd_set_accessed(struct vm_fault * vmf)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583516512,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1280",
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
      "addr": 18446744071583516512,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void huge_pmd_set_accessed(struct vm_fault * vmf)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583710608,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1497",
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
      "addr": 18446744071583710608,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493133992,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1177",
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
      "addr": 18446603336493133992,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286615760,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1177",
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
      "addr": 13835058055286615760,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581657424,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1177",
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
      "addr": 18446744071581657424,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581597360,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1177",
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
      "addr": 18446744071581597360,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648736,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1177",
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
      "addr": 18446744071581648736,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
```

```json
{
  "name": "huge_pmd_set_accessed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581715168,
      "name": "huge_pmd_set_accessed",
      "external": true,
      "loc": "mm/huge_memory.c:1177",
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
      "addr": 18446744071581715168,
      "name": "huge_pmd_set_accessed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
<code>int dirty</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, vma, address, pmd, orig_pmd, dirty</code> ➡️ <code>fe, orig_pmd</code>
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
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
void huge_pmd_set_accessed(struct vm_fault * vmf, pmd_t orig_pmd)
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
