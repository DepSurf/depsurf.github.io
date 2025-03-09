# Function: <code>fault_dirty_shared_page</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580836944,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2067",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580836944,
      "name": "fault_dirty_shared_page.isra.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580882144,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2273",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580882144,
      "name": "fault_dirty_shared_page.isra.67",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580975536,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2390",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580975536,
      "name": "fault_dirty_shared_page.isra.76",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581110576,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2432",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581110576,
      "name": "fault_dirty_shared_page.isra.81",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581190080,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2168",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581190080,
      "name": "fault_dirty_shared_page.isra.76",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581261840,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2222",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581261840,
      "name": "fault_dirty_shared_page.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581320512,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2231",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581320512,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581514432,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2560",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_shared_fault",
        "mm/memory.c:wp_page_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514432,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581559408,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2737",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_shared_fault",
        "mm/memory.c:wp_page_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559408,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581582864,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2798",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582864,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581848208,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2893",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581848208,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582240624,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2986",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240624,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582731088,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2966",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582731088,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582948176,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2965",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582948176,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583124656,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2989",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583124656,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492730928,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2231",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492730928,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226560268,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2231",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226560268,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286073680,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2231",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286073680,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272718810,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2231",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272718810,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581289360,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2231",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289360,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581235664,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2231",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235664,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581280560,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2231",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280560,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
```

```json
{
  "name": "fault_dirty_shared_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344512,
      "name": "fault_dirty_shared_page",
      "external": false,
      "loc": "mm/memory.c:2231",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344512,
      "name": "fault_dirty_shared_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
vm_fault_t fault_dirty_shared_page(struct vm_fault * vmf)
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
