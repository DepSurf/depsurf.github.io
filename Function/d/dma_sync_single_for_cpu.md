# Function: <code>dma_sync_single_for_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584128368,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:103",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
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
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584464160,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:261",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585725782,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:261",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584646400,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:311",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585914374,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:311",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584729480,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:354",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585996144,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:354",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585143960,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:352",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586440176,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:352",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585378143,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:352",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586704790,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:352",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585501560,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:380",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586862398,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:380",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585719862,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:383",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587120986,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:383",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585860614,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587321370,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586594790,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588173894,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591073714,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow"
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
void dma_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580123632,
      "name": "dma_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/mapping.c:258",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123632,
      "name": "dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void dma_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127936,
      "name": "dma_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/mapping.c:260",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127936,
      "name": "dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void dma_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270928,
      "name": "dma_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/mapping.c:325",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270928,
      "name": "dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void dma_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442144,
      "name": "dma_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/mapping.c:321",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442144,
      "name": "dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void dma_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580686352,
      "name": "dma_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/mapping.c:328",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686352,
      "name": "dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void dma_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580762768,
      "name": "dma_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/mapping.c:332",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580762768,
      "name": "dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void dma_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_sync_single_for_cpu",
      "external": true,
      "loc": "kernel/dma/mapping.c:332",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_dma_sync_single_range_for_cpu",
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597410067,
      "name": "dma_sync_single_for_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580847264,
      "name": "dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498050056,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor.c:mv_xor_channel_add"
      ]
    },
    {
      "addr": 18446603336498593892,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499998792,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/net/ethernet/broadcom/bgmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500014508,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500438968,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498050056,
      "name": "dma_sync_single_for_cpu.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230814504,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/dma/mv_xor.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor.c:mv_chan_xor_self_test"
      ]
    },
    {
      "addr": 3231226408,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 3231493724,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/iommu/exynos-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/exynos-iommu.c:exynos_iommu_unmap",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_unmap",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_unmap",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_map",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_map",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_map",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3232545504,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3232591408,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/net/ethernet/ti/davinci_cpdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3232893048,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 3233950912,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci.c:sdhci_request_done",
        "drivers/mmc/host/sdhci.c:sdhci_request_done"
      ],
      "caller_func": []
    },
    {
      "addr": 3234030388,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/firmware/qcom_scm-32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/qcom_scm-32.c:qcom_scm_call",
        "drivers/firmware/qcom_scm-32.c:qcom_scm_call"
      ],
      "caller_func": []
    },
    {
      "addr": 3234086628,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/firmware/tegra/ivc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/tegra/ivc.c:tegra_ivc_notified",
        "drivers/firmware/tegra/ivc.c:tegra_ivc_read_advance",
        "drivers/firmware/tegra/ivc.c:tegra_ivc_read_advance"
      ],
      "caller_func": []
    },
    {
      "addr": 3234185308,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/staging/emxx_udc/emxx_udc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_dma_unmap_single"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230814504,
      "name": "dma_sync_single_for_cpu.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291817048,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293788992,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276191400,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277328214,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278049718,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/mmc/host/mmc_spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmc_spi.c:mmc_spi_command_send"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585621622,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587027450,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585486678,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585811014,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587275930,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_cpu",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585918630,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587382698,
      "name": "dma_sync_single_for_cpu",
      "external": false,
      "loc": "include/linux/dma-mapping.h:376",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void dma_sync_single_for_cpu(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
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
