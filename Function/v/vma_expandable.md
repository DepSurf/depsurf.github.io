# Function: <code>vma_expandable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580721362,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:451",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:SyS_mremap"
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
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580837265,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:455",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:SyS_mremap"
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
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580903511,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:471",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:SyS_mremap"
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
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580947979,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:489",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:SyS_mremap"
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
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581048779,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:503",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:SyS_mremap"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
```

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581181440,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:499",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581181440,
      "name": "vma_expandable",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
```

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581263728,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:557",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581263728,
      "name": "vma_expandable",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
```

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581338288,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:575",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581338288,
      "name": "vma_expandable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
```

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581397568,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:575",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397568,
      "name": "vma_expandable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581602545,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:643",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581649736,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:791",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581670972,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:796",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581940258,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:875",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582349221,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:866",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582850697,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:868",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
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
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583066712,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:887",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
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
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583248743,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:954",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
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
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492804812,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:575",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__arm64_sys_mremap"
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
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226617540,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:575",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__se_sys_mremap"
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
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286180948,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:575",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__se_sys_mremap"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272769780,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:575",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__se_sys_mremap"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
```

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581366416,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:575",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366416,
      "name": "vma_expandable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
```

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581309920,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:575",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309920,
      "name": "vma_expandable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
```

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357616,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:575",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357616,
      "name": "vma_expandable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
```

```json
{
  "name": "vma_expandable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581421536,
      "name": "vma_expandable",
      "external": false,
      "loc": "mm/mremap.c:575",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__ia32_sys_mremap",
        "mm/mremap.c:__x64_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581421536,
      "name": "vma_expandable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
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
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int vma_expandable(struct vm_area_struct * vma, long unsigned int delta)
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
