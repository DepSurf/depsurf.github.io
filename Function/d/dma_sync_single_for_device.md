# Function: <code>dma_sync_single_for_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584128141,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:115",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584463931,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:273",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585693318,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:273",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585724674,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:273",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584646174,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:323",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585882294,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:323",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585913266,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:323",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584729216,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:366",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585965017,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:366",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585995356,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:366",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585143688,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:364",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586408729,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:364",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586439388,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:364",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585377855,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:364",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586669410,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:364",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586703904,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:364",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585501239,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:394",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586823474,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:394",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586861441,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:394",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585719565,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:397",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587081768,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:397",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587119956,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:397",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585860317,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587282248,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587320340,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586594493,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588138136,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588177269,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_fill_host_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589569959,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591074490,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "net/xdp/xsk_buff_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow",
        "net/xdp/xsk_buff_pool.c:xp_alloc"
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
void dma_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580123440,
      "name": "dma_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:272",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_fill_host_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow",
        "net/xdp/xsk_buff_pool.c:xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123440,
      "name": "dma_sync_single_for_device",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void dma_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580127744,
      "name": "dma_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:274",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:page_pool_dma_map",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow",
        "net/xdp/xsk_buff_pool.c:xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580127744,
      "name": "dma_sync_single_for_device",
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
void dma_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270736,
      "name": "dma_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:339",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_page",
        "net/core/page_pool.c:page_pool_dma_map",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow",
        "net/xdp/xsk_buff_pool.c:xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270736,
      "name": "dma_sync_single_for_device",
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
void dma_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580441888,
      "name": "dma_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:335",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page",
        "net/core/page_pool.c:page_pool_dma_map",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow",
        "net/xdp/xsk_buff_pool.c:xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580441888,
      "name": "dma_sync_single_for_device",
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
void dma_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580686080,
      "name": "dma_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:342",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page",
        "net/core/page_pool.c:page_pool_dma_map",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow",
        "net/xdp/xsk_buff_pool.c:xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686080,
      "name": "dma_sync_single_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void dma_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580762496,
      "name": "dma_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:346",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_defragged_page",
        "net/core/page_pool.c:page_pool_dma_map",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow",
        "net/xdp/xsk_buff_pool.c:xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580762496,
      "name": "dma_sync_single_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void dma_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "dma_sync_single_for_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_sync_single_for_device",
      "external": true,
      "loc": "kernel/dma/mapping.c:346",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_ring.c:virtqueue_dma_sync_single_range_for_device",
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma",
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list",
        "net/core/page_pool.c:page_pool_alloc_frag",
        "net/core/page_pool.c:page_pool_put_page_bulk",
        "net/core/page_pool.c:page_pool_put_unrefed_page",
        "net/core/page_pool.c:page_pool_dma_map",
        "net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow",
        "net/xdp/xsk_buff_pool.c:xp_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597410094,
      "name": "dma_sync_single_for_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580847600,
      "name": "dma_sync_single_for_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498593592,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498852180,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/iommu/io-pgtable-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498910144,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/iommu/rockchip-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499998840,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/net/ethernet/broadcom/bgmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500015008,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500396776,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500438100,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231226148,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 3231448416,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/iommu/io-pgtable-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/io-pgtable-arm.c:__arm_lpae_sync_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 3231465840,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/iommu/omap-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/omap-iommu.c:_omap_iommu_detach_dev",
        "drivers/iommu/omap-iommu.c:iopgtable_clear_entry",
        "drivers/iommu/omap-iommu.c:iopgtable_clear_entry",
        "drivers/iommu/omap-iommu.c:iopte_alloc_large",
        "drivers/iommu/omap-iommu.c:iopte_alloc_page",
        "drivers/iommu/omap-iommu.c:iopte_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3231477196,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/iommu/rockchip-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map",
        "drivers/iommu/rockchip-iommu.c:rk_iommu_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231483316,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/iommu/tegra-smmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/tegra-smmu.c:tegra_smmu_set_pte",
        "drivers/iommu/tegra-smmu.c:tegra_smmu_set_pde"
      ],
      "caller_func": []
    },
    {
      "addr": 3231493812,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
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
      "addr": 3232546032,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3232592160,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/net/ethernet/ti/davinci_cpdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si"
      ],
      "caller_func": []
    },
    {
      "addr": 3232852788,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 3232891768,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
      ],
      "caller_func": []
    },
    {
      "addr": 3233950000,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci.c:sdhci_pre_dma_transfer"
      ],
      "caller_func": []
    },
    {
      "addr": 3234086872,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/firmware/tegra/ivc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/tegra/ivc.c:tegra_ivc_notified",
        "drivers/firmware/tegra/ivc.c:tegra_ivc_notified",
        "drivers/firmware/tegra/ivc.c:tegra_ivc_reset",
        "drivers/firmware/tegra/ivc.c:tegra_ivc_read_advance"
      ],
      "caller_func": []
    },
    {
      "addr": 3234185612,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/staging/emxx_udc/emxx_udc.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291816540,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293726824,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293787720,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276191214,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277285242,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277327380,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278049678,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585621325,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586988328,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587026420,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585486381,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585810717,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587236808,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587274900,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
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
  "name": "dma_sync_single_for_device",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585918333,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/tty/serial/8250/8250_dma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587343576,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587381668,
      "name": "dma_sync_single_for_device",
      "external": false,
      "loc": "include/linux/dma-mapping.h:390",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list"
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
void dma_sync_single_for_device(struct device * dev, dma_addr_t addr, size_t size, enum dma_data_direction dir)
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
