# Function: <code>__replace_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580448063,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:152",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
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
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580523229,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:152",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
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
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580586543,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:152",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
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
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580616607,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
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
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580697263,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
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
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580830008,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580897392,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:164",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580897392,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580994912,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:151",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994912,
      "name": "__replace_page",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581048912,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581048912,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581231584,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581231584,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581274176,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274176,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1155
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581290816,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581290816,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1151
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581535104,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581535104,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883760,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883760,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1885
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582317040,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582317040,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1432
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582518208,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:153",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582518208,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1427
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582687136,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:153",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582687136,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1378
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492405904,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492405904,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226290276,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226290276,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285670240,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285670240,
      "name": "__replace_page",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581017760,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581017760,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963888,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963888,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1093
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581008960,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581008960,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
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
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```

```json
{
  "name": "__replace_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581070224,
      "name": "__replace_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:154",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070224,
      "name": "__replace_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1060
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __replace_page(struct vm_area_struct * vma, long unsigned int addr, struct page * old_page, struct page * new_page)
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
