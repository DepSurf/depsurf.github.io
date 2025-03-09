# Function: <code>do_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580675985,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3114",
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
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580790943,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3313",
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
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580855489,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3344",
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
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580900414,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3548",
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
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580997316,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3717",
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
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581131175,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3762",
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
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581212531,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3525",
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581284960,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3574",
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
      "addr": 18446744071581284960,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1599
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343680,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3599",
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
      "addr": 18446744071581343680,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1590
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581540352,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3960",
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
      "addr": 18446744071581540352,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581583552,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:4120",
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
      "addr": 18446744071581583552,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581605632,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:4128",
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
      "addr": 18446744071581605632,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871680,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:4275",
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
      "addr": 18446744071581871680,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582267248,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:4608",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_marker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582267248,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582758912,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:4611",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_marker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758912,
      "name": "do_fault",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582974912,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:4641",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_marker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582974912,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583152448,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:4859",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_marker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583152448,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 840
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492749440,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3599",
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
      "addr": 18446603336492749440,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226580660,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3599",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226580660,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286107712,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3599",
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
      "addr": 13835058055286107712,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2324
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272732788,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3599",
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
      "addr": 18446743936272732788,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1236
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581312528,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3599",
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
      "addr": 18446744071581312528,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1590
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581256240,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3599",
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
      "addr": 18446744071581256240,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1505
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581303728,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3599",
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
      "addr": 18446744071581303728,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1590
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
vm_fault_t do_fault(struct vm_fault * vmf)
```

```json
{
  "name": "do_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581367696,
      "name": "do_fault",
      "external": false,
      "loc": "mm/memory.c:3599",
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
      "addr": 18446744071581367696,
      "name": "do_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1620
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
vm_fault_t do_fault(struct vm_fault * vmf)
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
