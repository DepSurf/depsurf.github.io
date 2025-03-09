# Function: <code>gart_unmap_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, struct dma_attrs * attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579264688,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:265",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264688,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579264064,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:264",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264064,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579279568,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:264",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279568,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276320,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:265",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276320,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579294928,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:265",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294928,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579306960,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:266",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306960,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331520,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:251",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331520,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579346784,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:248",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346784,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579351120,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:248",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579351120,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579380560,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:247",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380560,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579387328,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:247",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387328,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390752,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:247",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390752,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452048,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:247",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452048,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579526272,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:245",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526272,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628688,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:245",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628688,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579642704,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:245",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642704,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579676560,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:245",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg",
        "arch/x86/kernel/amd_gart_64.c:gart_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579676560,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579347024,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:248",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347024,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579279232,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:248",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279232,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579346944,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:248",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346944,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "gart_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579355392,
      "name": "gart_unmap_page",
      "external": false,
      "loc": "arch/x86/kernel/amd_gart_64.c:248",
      "file": "arch/x86/kernel/amd_gart_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_free_coherent",
        "arch/x86/kernel/amd_gart_64.c:gart_unmap_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355392,
      "name": "gart_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dma_attrs * attrs</code> ➡️ <code>long unsigned int attrs</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void gart_unmap_page(struct device * dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
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
