# Function: <code>__handle_mm_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580675186,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3339",
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
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580789535,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3566",
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
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580853909,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3606",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580898848,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3831",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898848,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4125
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
int __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581000992,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:4001",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581000992,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1465
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
int __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581138112,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:4046",
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
      "addr": 18446744071581138112,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1441
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581211040,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3836",
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
      "addr": 18446744071581211040,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4728
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287200,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3885",
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
      "addr": 18446744071581287200,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1949
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345920,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3910",
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
      "addr": 18446744071581345920,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1949
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581550144,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:4285",
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
      "addr": 18446744071581550144,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1978
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581593280,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:4445",
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
      "addr": 18446744071581593280,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1971
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581613840,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:4472",
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
      "addr": 18446744071581613840,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1895
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:4618",
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
      "addr": 18446744071581880880,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1777
    },
    {
      "addr": 18446744071592199647,
      "name": "__handle_mm_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:4958",
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
      "addr": 18446744071582283008,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1852
    },
    {
      "addr": 18446744071593976415,
      "name": "__handle_mm_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:4985",
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
      "addr": 18446744071582775552,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1821
    },
    {
      "addr": 18446744071596032608,
      "name": "__handle_mm_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:4989",
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
      "addr": 18446744071582991808,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1811
    },
    {
      "addr": 18446744071596554555,
      "name": "__handle_mm_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:5215",
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
      "addr": 18446744071583173568,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1932
    },
    {
      "addr": 18446744071597458622,
      "name": "__handle_mm_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492751632,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3910",
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
      "addr": 18446603336492751632,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2004
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226582248,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3910",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286110720,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3910",
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
      "addr": 13835058055286110720,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2600
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272734226,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3910",
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
      "addr": 18446743936272734226,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314768,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3910",
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
      "addr": 18446744071581314768,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1949
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581258256,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3910",
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
      "addr": 18446744071581258256,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2615
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581305968,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3910",
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
      "addr": 18446744071581305968,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1949
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```

```json
{
  "name": "__handle_mm_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369968,
      "name": "__handle_mm_fault",
      "external": false,
      "loc": "mm/memory.c:3910",
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
      "addr": 18446744071581369968,
      "name": "__handle_mm_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1947
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```
</details>
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
vm_fault_t __handle_mm_fault(struct vm_area_struct * vma, long unsigned int address, unsigned int flags)
```
</details>
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
