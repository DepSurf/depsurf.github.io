# Function: <code>free_vmap_area_noflush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580733888,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:681",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:remove_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580733888,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580852752,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:699",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852752,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580922672,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:689",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922672,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580967024,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:740",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580967024,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068688,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:738",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:free_vmap_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068688,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210208,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:718",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210208,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293920,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:718",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293920,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581372080,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1323",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581372080,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581433232,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1327",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433232,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581633648,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1428",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:free_vmap_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633648,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581679280,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1422",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581679280,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581701520,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1692",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581701520,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581973296,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1744",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:free_vmap_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973296,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582387040,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1764",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582387040,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582893248,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1822",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582893248,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583108592,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1817",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:free_vmap_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583108592,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 903
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583290848,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1817",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:free_vmap_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290848,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 903
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492835536,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1327",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492835536,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226639696,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1327",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_unmap_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226639696,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286222880,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1327",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:free_vmap_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286222880,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272788868,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1327",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272788868,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402080,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1327",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402080,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581344592,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1327",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344592,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393280,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1327",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393280,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void free_vmap_area_noflush(struct vmap_area * va)
```

```json
{
  "name": "free_vmap_area_noflush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581457216,
      "name": "free_vmap_area_noflush",
      "external": false,
      "loc": "mm/vmalloc.c:1327",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:remove_vm_area",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457216,
      "name": "free_vmap_area_noflush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
