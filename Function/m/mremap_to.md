# Function: <code>mremap_to</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580720846,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:395",
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
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580836608,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:399",
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
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580902880,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:415",
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
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580947371,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:429",
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
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581048171,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:443",
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581185168,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:439",
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
      "addr": 18446744071581185168,
      "name": "mremap_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581268048,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:497",
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
      "addr": 18446744071581268048,
      "name": "mremap_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 537
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581342640,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:498",
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
      "addr": 18446744071581342640,
      "name": "mremap_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401984,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:498",
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
      "addr": 18446744071581401984,
      "name": "mremap_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, long unsigned int flags, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581600784,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:549",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581600784,
      "name": "mremap_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 839
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, long unsigned int flags, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581647872,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:697",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581647872,
      "name": "mremap_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 837
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, long unsigned int flags, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581669168,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:702",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581669168,
      "name": "mremap_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, long unsigned int flags, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581938432,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:781",
      "file": "mm/mremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581938432,
      "name": "mremap_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582347328,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:779",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582347328,
      "name": "mremap_to.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582848496,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:781",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848496,
      "name": "mremap_to.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583064544,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:800",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583064544,
      "name": "mremap_to.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583246576,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:867",
      "file": "mm/mremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/mremap.c:__do_sys_mremap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583246576,
      "name": "mremap_to.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 685
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492804924,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:498",
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
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226617764,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:498",
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
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286180544,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:498",
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
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272769554,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:498",
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581370832,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:498",
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
      "addr": 18446744071581370832,
      "name": "mremap_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581314240,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:498",
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
      "addr": 18446744071581314240,
      "name": "mremap_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581362032,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:498",
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
      "addr": 18446744071581362032,
      "name": "mremap_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```

```json
{
  "name": "mremap_to",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581425936,
      "name": "mremap_to",
      "external": false,
      "loc": "mm/mremap.c:498",
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
      "addr": 18446744071581425936,
      "name": "mremap_to",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>addr, old_len, new_addr, new_len, locked, uf, uf_unmap_early, uf_unmap</code> ➡️ <code>addr, old_len, new_addr, new_len, locked, flags, uf, uf_unmap_early, uf_unmap</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, long unsigned int flags, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
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
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int mremap_to(long unsigned int addr, long unsigned int old_len, long unsigned int new_addr, long unsigned int new_len, bool * locked, struct vm_userfaultfd_ctx * uf, struct list_head * uf_unmap_early, struct list_head * uf_unmap)
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
