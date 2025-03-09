# Function: <code>dma_direct_sync_sg_for_device</code>

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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993424,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:228",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993424,
      "name": "dma_direct_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035488,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:238",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035488,
      "name": "dma_direct_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580085728,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:238",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085728,
      "name": "dma_direct_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145936,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:325",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_end_cpu_access",
        "drivers/dma-buf/udmabuf.c:end_cpu_udmabuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145936,
      "name": "dma_direct_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127264,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:337",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127264,
      "name": "dma_direct_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131584,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:337",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131584,
      "name": "dma_direct_sync_sg_for_device",
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275088,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:377",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275088,
      "name": "dma_direct_sync_sg_for_device",
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580446704,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:409",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580446704,
      "name": "dma_direct_sync_sg_for_device",
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580691168,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:409",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691168,
      "name": "dma_direct_sync_sg_for_device",
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767776,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:408",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767776,
      "name": "dma_direct_sync_sg_for_device",
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:397",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_sync_sg_for_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597410309,
      "name": "dma_direct_sync_sg_for_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580853520,
      "name": "dma_direct_sync_sg_for_device",
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491287912,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:238",
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
      "addr": 18446603336491287912,
      "name": "dma_direct_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_sync_sg_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:219",
      "file": "drivers/tty/serial/imx.c",
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284213648,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:238",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_sg_for_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284213648,
      "name": "dma_direct_sync_sg_for_device",
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271804016,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:238",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271804016,
      "name": "dma_direct_sync_sg_for_device",
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054464,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:238",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054464,
      "name": "dma_direct_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579999776,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:238",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999776,
      "name": "dma_direct_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046000,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:238",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046000,
      "name": "dma_direct_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
```

```json
{
  "name": "dma_direct_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580096752,
      "name": "dma_direct_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/direct.c:238",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096752,
      "name": "dma_direct_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
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
void dma_direct_sync_sg_for_device(struct device * dev, struct scatterlist * sgl, int nents, enum dma_data_direction dir)
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
