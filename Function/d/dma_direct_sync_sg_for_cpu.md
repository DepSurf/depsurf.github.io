# Function: <code>dma_direct_sync_sg_for_cpu</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993584,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:265",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993584,
      "name": "dma_direct_sync_sg_for_cpu",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035632,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:277",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035632,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580085872,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:277",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085872,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146080,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:364",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_begin_cpu_access",
        "drivers/dma-buf/udmabuf.c:begin_cpu_udmabuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146080,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127472,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:360",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127472,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131776,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:360",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131776,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275280,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:400",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275280,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580446928,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:432",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580446928,
      "name": "dma_direct_sync_sg_for_cpu",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580691408,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:432",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691408,
      "name": "dma_direct_sync_sg_for_cpu",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580768016,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:431",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580768016,
      "name": "dma_direct_sync_sg_for_cpu",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:420",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597410344,
      "name": "dma_direct_sync_sg_for_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580853792,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491288304,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:277",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/imx.c:imx_uart_dma_rx_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491288304,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:250",
      "file": "drivers/tty/serial/imx.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:250",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284213920,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:277",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_sg_for_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284213920,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271804162,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:277",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271804162,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054608,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:277",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054608,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579999920,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:277",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999920,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046144,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:277",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046144,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580096896,
      "name": "dma_direct_sync_sg_for_cpu",
      "external": true,
      "loc": "kernel/dma/direct.c:277",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096896,
      "name": "dma_direct_sync_sg_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
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
