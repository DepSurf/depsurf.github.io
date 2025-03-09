# Function: <code>update_ref_ctr_warn</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580907852,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:416",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581005670,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:404",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581060521,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:413",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void update_ref_ctr_warn(struct uprobe * uprobe, struct mm_struct * mm, short int d)
```

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581241448,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:407",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241448,
      "name": "update_ref_ctr_warn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void update_ref_ctr_warn(struct uprobe * uprobe, struct mm_struct * mm, short int d)
```

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591323555,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:407",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591323555,
      "name": "update_ref_ctr_warn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void update_ref_ctr_warn(struct uprobe * uprobe, struct mm_struct * mm, short int d)
```

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591265444,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:407",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591265444,
      "name": "update_ref_ctr_warn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void update_ref_ctr_warn(struct uprobe * uprobe, struct mm_struct * mm, short int d)
```

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592188363,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:407",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592188363,
      "name": "update_ref_ctr_warn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void update_ref_ctr_warn(struct uprobe * uprobe, struct mm_struct * mm, short int d)
```

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593963427,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:401",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593963427,
      "name": "update_ref_ctr_warn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582325245,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:404",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582526600,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:402",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582695512,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:402",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
      ],
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
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492413496,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:413",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
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
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226297224,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:413",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285679668,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:413",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581029369,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:413",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580975449,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:413",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581020569,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:413",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "update_ref_ctr_warn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581081911,
      "name": "update_ref_ctr_warn",
      "external": false,
      "loc": "kernel/events/uprobes.c:413",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:update_ref_ctr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void update_ref_ctr_warn(struct uprobe * uprobe, struct mm_struct * mm, short int d)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void update_ref_ctr_warn(struct uprobe * uprobe, struct mm_struct * mm, short int d)
```
</details>
</li>
</ul>
