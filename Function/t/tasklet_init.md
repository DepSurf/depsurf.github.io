# Function: <code>tasklet_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579387968,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:557",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_hrtimer_init"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "net/ipv4/tcp_output.c:tcp_tasklet_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387968,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579402442,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:557",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_hrtimer_init"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "net/ipv4/tcp_output.c:tcp_tasklet_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400608,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579422762,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:571",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_hrtimer_init"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "net/core/flow.c:flow_cache_cpu_up_prep",
        "net/ipv4/tcp_output.c:tcp_tasklet_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420928,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579409959,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:571",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_hrtimer_init"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "net/core/flow.c:flow_cache_cpu_up_prep",
        "net/ipv4/tcp_output.c:tcp_tasklet_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408864,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579437927,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:561",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_hrtimer_init"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436896,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579453207,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:548",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_hrtimer_init"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452288,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579486839,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:549",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:tasklet_hrtimer_init"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485856,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503904,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:549",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503904,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579529952,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:549",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529952,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579560496,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:576",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560496,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542016,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:595",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542016,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546144,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:825",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546144,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618624,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:824",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618624,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579712464,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:838",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712464,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579838816,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:838",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579838816,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888160,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:825",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888160,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579926736,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:825",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926736,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490673640,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:549",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/virt-dma.c:vchan_init",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/net/ethernet/smsc/smc91x.c:smc_probe",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490673640,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224744636,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:549",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/virt-dma.c:vchan_init",
        "drivers/dma/mv_xor.c:mv_xor_channel_add",
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/ipu/ipu_idmac.c:ipu_probe",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "sound/core/timer.c:snd_timer_new",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224744636,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283495872,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:549",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283495872,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271411016,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:549",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271411016,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503616,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:549",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503616,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432480,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:549",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/hv/hv.c:hv_synic_alloc",
        "drivers/hv/channel_mgmt.c:vmbus_onoffer",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432480,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579503536,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:549",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579503536,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tasklet_init(struct tasklet_struct * t, void (*)(long unsigned int) func, long unsigned int data)
```

```json
{
  "name": "tasklet_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536176,
      "name": "tasklet_init",
      "external": true,
      "loc": "kernel/softirq.c:549",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "net/ipv4/tcp_output.c:tcp_tasklet_init",
        "net/xfrm/xfrm_input.c:xfrm_input_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536176,
      "name": "tasklet_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
