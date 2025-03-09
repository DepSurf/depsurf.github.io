# Function: <code>dma_common_get_sgtable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t handle, size_t size)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584471264,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "drivers/base/dma-mapping.c:228",
      "file": "drivers/base/dma-mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584471264,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t handle, size_t size)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584815904,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "drivers/base/dma-mapping.c:227",
      "file": "drivers/base/dma-mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815904,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t handle, size_t size)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585009904,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "drivers/base/dma-mapping.c:230",
      "file": "drivers/base/dma-mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585009904,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t handle, size_t size)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585095488,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "drivers/base/dma-mapping.c:208",
      "file": "drivers/base/dma-mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_get_sgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585095488,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t handle, size_t size)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585520752,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "drivers/base/dma-mapping.c:205",
      "file": "drivers/base/dma-mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_get_sgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520752,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t handle, size_t size)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944624,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:204",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_get_sgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944624,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992800,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:111",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_get_sgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992800,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034640,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:111",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_get_sgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034640,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580085136,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:111",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085136,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145120,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:111",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145120,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580129824,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/ops_helpers.c:11",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129824,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134256,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/ops_helpers.c:18",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134256,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580277424,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/ops_helpers.c:18",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580277424,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580449360,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/ops_helpers.c:18",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580449360,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580694176,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/ops_helpers.c:18",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580694176,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580770800,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/ops_helpers.c:18",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580770800,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856864,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/ops_helpers.c:18",
      "file": "kernel/dma/ops_helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856864,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491286672,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:111",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491286672,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225293800,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:111",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225293800,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284212672,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:111",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284212672,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271803246,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:111",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271803246,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580053872,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:111",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053872,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579999184,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:111",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999184,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580045408,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:111",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045408,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int dma_common_get_sgtable(struct device * dev, struct sg_table * sgt, void * cpu_addr, dma_addr_t dma_addr, size_t size, long unsigned int attrs)
```

```json
{
  "name": "dma_common_get_sgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580096160,
      "name": "dma_common_get_sgtable",
      "external": true,
      "loc": "kernel/dma/mapping.c:111",
      "file": "kernel/dma/mapping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_get_sgtable_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096160,
      "name": "dma_common_get_sgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>dma_addr_t dma_addr</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int attrs</code>
</li>
<li>
<b>Param removed. </b>
<code>dma_addr_t handle</code>
</li>
</ul>
</details>
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
