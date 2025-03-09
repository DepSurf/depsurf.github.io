# Function: <code>lo_hi_writeq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585443493,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:18",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585489055,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:18",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585497747,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:18",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq"
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
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585851029,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:18",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585884894,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:18",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585910536,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:18",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
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
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586039861,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:18",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586074028,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:18",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586098710,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:18",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
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
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586123133,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:18",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586155770,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:18",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586181724,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:18",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
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
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586565973,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586601164,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586627148,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586658607,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
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
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586830717,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586864172,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586894399,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586922422,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
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
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586987427,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587019999,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587050768,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587079156,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587099413,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
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
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587247604,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587283109,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587310290,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587343628,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587364261,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
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
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587448048,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587483763,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587512040,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587545996,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587566101,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
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
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588312009,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588346653,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588374840,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588409131,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588428372,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588346700,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588378237,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588404936,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588439728,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588458950,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588229411,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588260622,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588284451,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588322690,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588341484,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588872405,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588911304,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588937672,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588980207,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589000362,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590300355,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590340800,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590368915,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590413004,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590435882,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591923740,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591969369,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592002350,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592050862,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592074474,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592346870,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592390489,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592423100,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592473622,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592497242,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593088494,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593133863,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_add_interrupter",
        "drivers/usb/host/xhci-mem.c:xhci_add_interrupter",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-mem.c:xhci_remove_secondary_interrupter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593166854,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593215254,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593241626,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_handle_events",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500583192,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500620904,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500654092,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500687232,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233044560,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 3233081228,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3233114236,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 3233146204,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293987092,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294036740,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294077376,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294119388,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
void lo_hi_writeq(__u64 val, volatile void * addr)
```

```json
{
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277454942,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ]
    },
    {
      "addr": 18446743936277488814,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277517334,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277543762,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277439734,
      "name": "lo_hi_writeq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586515996,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_reset_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587154096,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587189795,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587218072,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
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
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586384572,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/nvme/host/pci.c:nvme_reset_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586912698,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586948547,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586976824,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587010780,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587402608,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587438323,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587466600,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587500556,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
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
  "name": "lo_hi_writeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587509015,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587545299,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587574225,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587608382,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587628565,
      "name": "lo_hi_writeq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:19",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void lo_hi_writeq(__u64 val, volatile void * addr)
```
</details>
</li>
</ul>
