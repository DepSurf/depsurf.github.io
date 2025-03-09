# Function: <code>dma_sync_sg_for_device</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_sg_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587406379,
      "name": "dma_sync_sg_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:419",
      "file": "drivers/dma-buf/heaps/heap-helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_end_cpu_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587416157,
      "name": "dma_sync_sg_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:419",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:end_cpu_udmabuf"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void dma_sync_sg_for_device(struct device * dev, struct scatterlist * sg, int nelems, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580120864,
      "name": "dma_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:300",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access",
        "drivers/dma-buf/udmabuf.c:end_cpu_udmabuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120864,
      "name": "dma_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void dma_sync_sg_for_device(struct device * dev, struct scatterlist * sg, int nelems, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580124432,
      "name": "dma_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:302",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access",
        "drivers/dma-buf/udmabuf.c:end_cpu_udmabuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124432,
      "name": "dma_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void dma_sync_sg_for_device(struct device * dev, struct scatterlist * sg, int nelems, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267360,
      "name": "dma_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:367",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access",
        "drivers/dma-buf/udmabuf.c:end_cpu_udmabuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267360,
      "name": "dma_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void dma_sync_sg_for_device(struct device * dev, struct scatterlist * sg, int nelems, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580437680,
      "name": "dma_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:363",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access",
        "drivers/dma-buf/udmabuf.c:end_cpu_udmabuf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437680,
      "name": "dma_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void dma_sync_sg_for_device(struct device * dev, struct scatterlist * sg, int nelems, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580681088,
      "name": "dma_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:370",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access",
        "drivers/dma-buf/udmabuf.c:end_cpu_udmabuf",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580681088,
      "name": "dma_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void dma_sync_sg_for_device(struct device * dev, struct scatterlist * sg, int nelems, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757600,
      "name": "dma_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:374",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access",
        "drivers/dma-buf/udmabuf.c:end_cpu_udmabuf",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757600,
      "name": "dma_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void dma_sync_sg_for_device(struct device * dev, struct scatterlist * sg, int nelems, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_sg_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580842720,
      "name": "dma_sync_sg_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:374",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_end_cpu_access",
        "drivers/dma-buf/udmabuf.c:end_cpu_udmabuf",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580842720,
      "name": "dma_sync_sg_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_sg_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498666240,
      "name": "dma_sync_sg_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:419",
      "file": "drivers/tty/serial/imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/imx.c:imx_uart_dma_rx_callback"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_sg_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231276592,
      "name": "dma_sync_sg_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:419",
      "file": "drivers/tty/serial/imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/imx.c:imx_uart_dma_rx_callback"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void dma_sync_sg_for_device(struct device * dev, struct scatterlist * sg, int nelems, enum dma_data_direction dir)
```
</details>
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
