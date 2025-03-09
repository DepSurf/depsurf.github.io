# Function: <code>vunmap_range_noflush</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void vunmap_range_noflush(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vunmap_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581713072,
      "name": "vunmap_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:393",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:__pcpu_balance_workfn",
        "mm/percpu.c:pcpu_map_pages",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:vunmap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581713072,
      "name": "vunmap_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
void vunmap_range_noflush(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vunmap_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vunmap_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:421",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_map_pages",
        "mm/percpu.c:pcpu_unmap_pages",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:vunmap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592202113,
      "name": "vunmap_range_noflush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071581985008,
      "name": "vunmap_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1117
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
void vunmap_range_noflush(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vunmap_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vunmap_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:419",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_map_pages",
        "mm/percpu.c:pcpu_unmap_pages",
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:vunmap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593978930,
      "name": "vunmap_range_noflush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071582407136,
      "name": "vunmap_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap_range_noflush(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vunmap_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582916304,
      "name": "vunmap_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:447",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:vunmap_range"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_map_pages",
        "mm/percpu.c:pcpu_unmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915056,
      "name": "vunmap_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap_range_noflush(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vunmap_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583132597,
      "name": "vunmap_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:436",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:vunmap_range"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_map_pages",
        "mm/percpu.c:pcpu_unmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583131520,
      "name": "vunmap_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void vunmap_range_noflush(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "vunmap_range_noflush",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583315589,
      "name": "vunmap_range_noflush",
      "external": true,
      "loc": "mm/vmalloc.c:436",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:vunmap_range"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_map_pages",
        "mm/percpu.c:pcpu_unmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583314512,
      "name": "vunmap_range_noflush",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void vunmap_range_noflush(long unsigned int start, long unsigned int end)
```
</details>
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
