# Function: <code>vunmap_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580738112,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:104",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:remove_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738112,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580855776,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:105",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855776,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 886
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580926016,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:105",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926016,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 886
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580970272,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:121",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580970272,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581072800,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:119",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072800,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 982
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
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581208624,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:119",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208624,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581292304,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:119",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292304,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581367803,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:122",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366896,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
    },
    {
      "addr": 18446744071581383462,
      "name": "vunmap_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581426624,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:122",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426624,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492828216,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:122",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492828216,
      "name": "vunmap_page_range",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226632740,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:122",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:free_unmap_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226632740,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286213056,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:122",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286213056,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1704
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
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272782788,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:122",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272782788,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581395472,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:122",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395472,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581336464,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:122",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581336464,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
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
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581386672,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:122",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386672,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```

```json
{
  "name": "vunmap_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581450992,
      "name": "vunmap_page_range",
      "external": false,
      "loc": "mm/vmalloc.c:122",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:unmap_kernel_range",
        "mm/vmalloc.c:unmap_kernel_range_noflush",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581450992,
      "name": "vunmap_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void vunmap_page_range(long unsigned int addr, long unsigned int end)
```
</details>
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
