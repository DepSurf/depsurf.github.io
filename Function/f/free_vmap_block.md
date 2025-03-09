# Function: <code>free_vmap_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580732544,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:876",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:vm_unmap_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580732544,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580851520,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:900",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:__purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851520,
      "name": "free_vmap_block",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580922816,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:871",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922816,
      "name": "free_vmap_block",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580967168,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:922",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580967168,
      "name": "free_vmap_block",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068832,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:920",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068832,
      "name": "free_vmap_block",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581210352,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:903",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210352,
      "name": "free_vmap_block",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581294064,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:903",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294064,
      "name": "free_vmap_block",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581372240,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1506",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581372240,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581433472,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1514",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433472,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581633888,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1615",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:purge_fragmented_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633888,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581680064,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1608",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:purge_fragmented_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680064,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581702304,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1878",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:purge_fragmented_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702304,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974080,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1930",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:purge_fragmented_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974080,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582387872,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1949",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582387872,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582894208,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:2011",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582894208,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583109712,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:2078",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:_vm_unmap_aliases",
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:reclaim_and_purge_vmap_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583109712,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291968,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:2078",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:_vm_unmap_aliases",
        "mm/vmalloc.c:vb_free",
        "mm/vmalloc.c:reclaim_and_purge_vmap_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291968,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492835920,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1514",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492835920,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226639996,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1514",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226639996,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286223328,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1514",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286223328,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272789154,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1514",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272789154,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581402320,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1514",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402320,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581344832,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1514",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581344832,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581393520,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1514",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393520,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void free_vmap_block(struct vmap_block * vb)
```

```json
{
  "name": "free_vmap_block",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581457456,
      "name": "free_vmap_block",
      "external": false,
      "loc": "mm/vmalloc.c:1514",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_ram",
        "mm/vmalloc.c:purge_fragmented_blocks_allcpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457456,
      "name": "free_vmap_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
