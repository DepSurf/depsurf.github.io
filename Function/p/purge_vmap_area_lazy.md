# Function: <code>purge_vmap_area_lazy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580734640,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:669",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:pcpu_get_vm_areas"
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
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580859143,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:687",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580923776,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:676",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923776,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580968112,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:727",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580968112,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069728,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:725",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069728,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581211248,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:705",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581211248,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581294960,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:705",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294960,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581374544,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1310",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581374544,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435792,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1314",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435792,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581634816,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1415",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634816,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581680992,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1409",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680992,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581703232,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1679",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581703232,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581975104,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1731",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975104,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582403854,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1737",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
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
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582910556,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1795",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492839192,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1314",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492839192,
      "name": "purge_vmap_area_lazy",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226642824,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1314",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226642824,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286227360,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1314",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286227360,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272791770,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1314",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272791770,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581404640,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1314",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404640,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581347152,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1314",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347152,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581395840,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1314",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395840,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void purge_vmap_area_lazy()
```

```json
{
  "name": "purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581459808,
      "name": "purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1314",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459808,
      "name": "purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void purge_vmap_area_lazy()
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void purge_vmap_area_lazy()
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
