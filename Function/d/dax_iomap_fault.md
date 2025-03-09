# Function: <code>dax_iomap_fault</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int dax_iomap_fault(struct vm_area_struct * vma, struct vm_fault * vmf, struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581581728,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1125",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_fault",
        "fs/ext4/file.c:ext4_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581581728,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1868
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
int dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581642336,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1455",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581642336,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4300
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
int dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581787792,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1498",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787792,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4366
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581961360,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1721",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961360,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582049808,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1626",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582049808,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582213552,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1642",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582213552,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582294448,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1646",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294448,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582579104,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1636",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582579104,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582650224,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1651",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/fuse/dax.c:__fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582650224,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582679296,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1663",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/fuse/dax.c:__fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582679296,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583004736,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1635",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/fuse/dax.c:__fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004736,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583475296,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1595",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/fuse/dax.c:__fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583475296,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584067872,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1879",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/fuse/dax.c:__fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584067872,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584294256,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1921",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/fuse/dax.c:__fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584294256,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, unsigned int order, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584511072,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1907",
      "file": "fs/dax.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/fuse/dax.c:__fuse_dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511072,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493868328,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1646",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493868328,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287500720,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1646",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287500720,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273432628,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1646",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273432628,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582263184,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1646",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582263184,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582200960,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1646",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582200960,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582253664,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1646",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582253664,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
```

```json
{
  "name": "dax_iomap_fault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582332256,
      "name": "dax_iomap_fault",
      "external": true,
      "loc": "fs/dax.c:1646",
      "file": "fs/dax.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_dax_huge_fault",
        "fs/ext4/file.c:ext4_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582332256,
      "name": "dax_iomap_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int dax_iomap_fault(struct vm_area_struct * vma, struct vm_fault * vmf, struct iomap_ops * ops)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum page_entry_size pe_size</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, vmf, ops</code> ➡️ <code>vmf, pe_size, ops</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct iomap_ops * ops</code> ➡️ <code>const struct iomap_ops * ops</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>pfn_t * pfnp</code>
</li>
<li>
<b>Param reordered. </b>
<code>vmf, pe_size, ops</code> ➡️ <code>vmf, pe_size, pfnp, ops</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * iomap_errp</code>
</li>
<li>
<b>Param reordered. </b>
<code>vmf, pe_size, pfnp, ops</code> ➡️ <code>vmf, pe_size, pfnp, iomap_errp, ops</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int order</code>
</li>
<li>
<b>Param removed. </b>
<code>enum page_entry_size pe_size</code>
</li>
</ul>
</details>
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
vm_fault_t dax_iomap_fault(struct vm_fault * vmf, enum page_entry_size pe_size, pfn_t * pfnp, int * iomap_errp, const struct iomap_ops * ops)
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
