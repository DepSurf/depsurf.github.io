# Function: <code>prepare_uprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580447616,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:579",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:uprobe_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580447616,
      "name": "prepare_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580522704,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:581",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:register_for_each_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580522704,
      "name": "prepare_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580586032,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:582",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:register_for_each_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580586032,
      "name": "prepare_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580617971,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:590",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580698755,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:590",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580831141,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:589",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580898336,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:805",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:register_for_each_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898336,
      "name": "prepare_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995936,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:793",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:register_for_each_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995936,
      "name": "prepare_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050096,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:845",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:register_for_each_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050096,
      "name": "prepare_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581234981,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:839",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581277611,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:839",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581293563,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:837",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581538475,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:838",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581888505,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:832",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582321401,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:835",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582522713,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:832",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582691641,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:832",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492409032,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:845",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226292820,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:845",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
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
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285671776,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:845",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:register_for_each_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285671776,
      "name": "prepare_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581018944,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:845",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:register_for_each_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581018944,
      "name": "prepare_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580965040,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:845",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:register_for_each_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580965040,
      "name": "prepare_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581010144,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:845",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:register_for_each_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010144,
      "name": "prepare_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```

```json
{
  "name": "prepare_uprobe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071344,
      "name": "prepare_uprobe",
      "external": false,
      "loc": "kernel/events/uprobes.c:845",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:register_for_each_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071344,
      "name": "prepare_uprobe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
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
int prepare_uprobe(struct uprobe * uprobe, struct file * file, struct mm_struct * mm, long unsigned int vaddr)
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
