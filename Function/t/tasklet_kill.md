# Function: <code>tasklet_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579389216,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:568",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579389216,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402304,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:568",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402304,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579422624,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:582",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422624,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409824,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:582",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409824,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579437792,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:572",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437792,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:559",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456669,
      "name": "tasklet_kill.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579453568,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:560",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490333,
      "name": "tasklet_kill.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579487200,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:560",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508189,
      "name": "tasklet_kill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579504880,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:560",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534237,
      "name": "tasklet_kill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579530928,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:587",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565197,
      "name": "tasklet_kill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579561408,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:607",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591278574,
      "name": "tasklet_kill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579542928,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:863",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591221472,
      "name": "tasklet_kill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579547584,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:862",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592100500,
      "name": "tasklet_kill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579619856,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:876",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593868070,
      "name": "tasklet_kill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579714384,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579840992,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:876",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/hsu/hsu.c:hsu_dma_remove",
        "drivers/dma/hsu/hsu.c:hsu_dma_synchronize",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840992,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890976,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:863",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/hsu/hsu.c:hsu_dma_remove",
        "drivers/dma/hsu/hsu.c:hsu_dma_synchronize",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890976,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579929552,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:863",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/hsu/hsu.c:hsu_dma_remove",
        "drivers/dma/hsu/hsu.c:hsu_dma_synchronize",
        "drivers/dma/lgm/lgm-dma.c:ldma_synchronize",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579929552,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490674488,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:560",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/amba-pl08x.c:pl08x_synchronize",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_free",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_synchronize",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_remove",
        "drivers/dma/ipu/ipu_idmac.c:ipu_remove",
        "drivers/net/ethernet/smsc/smc91x.c:smc_close",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490674488,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224745908,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:560",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/amba-pl08x.c:pl08x_synchronize",
        "drivers/dma/ipu/ipu_idmac.c:ipu_remove",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_remove",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe",
        "drivers/dma/ti/edma.c:edma_remove",
        "drivers/dma/ti/edma.c:edma_synchronize",
        "drivers/dma/ti/omap-dma.c:omap_dma_free",
        "drivers/dma/ti/omap-dma.c:omap_dma_synchronize",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224745908,
      "name": "tasklet_kill",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283497744,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:560",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283497744,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271412440,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:560",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271412440,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:560",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507901,
      "name": "tasklet_kill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579504592,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:560",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/hv/vmbus_drv.c:vmbus_exit",
        "drivers/hv/channel_mgmt.c:vmbus_add_channel_work",
        "drivers/hv/channel_mgmt.c:hv_process_channel_removal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436701,
      "name": "tasklet_kill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579433456,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:560",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507821,
      "name": "tasklet_kill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579504512,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void tasklet_kill(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_kill",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_kill",
      "external": true,
      "loc": "kernel/softirq.c:560",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540621,
      "name": "tasklet_kill.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579537152,
      "name": "tasklet_kill",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
