# Function: <code>copy_to_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580446832,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:240",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580446832,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580521872,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:242",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521872,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580585856,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:242",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580585856,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580615904,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:250",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615904,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580696544,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:250",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580696544,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580828752,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:250",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828752,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580895552,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:260",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895552,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580993072,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:248",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993072,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581047072,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:257",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047072,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581228480,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:251",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228480,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581271088,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:251",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581271088,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288912,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:251",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288912,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581533200,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:251",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581533200,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581881792,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:245",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881792,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582314768,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:247",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582314768,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582515936,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:246",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582515936,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582683584,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:246",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582683584,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492403400,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:257",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492403400,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226288488,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:257",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226288488,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285666944,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:257",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285666944,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581015920,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:257",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581015920,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962048,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:257",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962048,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581007120,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:257",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581007120,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
```

```json
{
  "name": "copy_to_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068496,
      "name": "copy_to_page",
      "external": false,
      "loc": "kernel/events/uprobes.c:257",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:arch_uprobe_copy_ixol",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068496,
      "name": "copy_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
void copy_to_page(struct page * page, long unsigned int vaddr, const void * src, int len)
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
