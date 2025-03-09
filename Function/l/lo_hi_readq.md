# Function: <code>lo_hi_readq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585443413,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585489355,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585497607,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585528917,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci-dbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbg.c:xhci_print_ir_set",
        "drivers/usb/host/xhci-dbg.c:xhci_print_ir_set",
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_cmd_ptrs"
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
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585844691,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585885200,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585910446,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585927379,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci-dbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_cmd_ptrs",
        "drivers/usb/host/xhci-dbg.c:xhci_print_ir_set",
        "drivers/usb/host/xhci-dbg.c:xhci_print_ir_set"
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
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586033812,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586074334,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586098619,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586115651,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci-dbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_cmd_ptrs",
        "drivers/usb/host/xhci-dbg.c:xhci_print_ir_set",
        "drivers/usb/host/xhci-dbg.c:xhci_print_ir_set"
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
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586117742,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586156070,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586181621,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586198707,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:7",
      "file": "drivers/usb/host/xhci-dbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_cmd_ptrs",
        "drivers/usb/host/xhci-dbg.c:xhci_print_ir_set",
        "drivers/usb/host/xhci-dbg.c:xhci_print_ir_set"
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
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586584272,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586601470,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586627045,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586644499,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-dbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbg.c:xhci_dbg_cmd_ptrs",
        "drivers/usb/host/xhci-dbg.c:xhci_print_ir_set",
        "drivers/usb/host/xhci-dbg.c:xhci_print_ir_set"
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
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586849155,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586864487,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586894281,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587005654,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587020310,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587050650,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587263400,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587283417,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587310176,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587463786,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587484071,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587512013,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588325837,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588346961,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588374814,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588360666,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588378545,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588404910,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588243114,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588260930,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588284425,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588890999,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588911623,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588937645,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590319441,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590341119,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590368888,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591945808,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591969688,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592002324,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592368088,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592390823,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592423077,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
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
      "addr": 18446744071593380408,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/platform/x86/intel/pmc/core_ssram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_get_pmc",
        "drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_get_pmc"
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
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593109590,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593134197,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_add_interrupter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593166831,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
__u64 lo_hi_readq(volatile const void * addr)
```

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500602212,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ]
    },
    {
      "addr": 18446603336500621192,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500654032,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500572584,
      "name": "lo_hi_readq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233063192,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 3233081552,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3233114208,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
__u64 lo_hi_readq(volatile const void * addr)
```

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294012648,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": [
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ]
    },
    {
      "addr": 13835058055294037084,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294077308,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout",
        "drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293977184,
      "name": "lo_hi_readq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277472400,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs",
        "drivers/usb/host/xhci.c:xhci_zero_64b_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277489122,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277517304,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586498892,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_pci_reg_read64",
        "drivers/nvme/host/pci.c:nvme_reset_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587169818,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587190103,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587218045,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586367468,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_pci_reg_read64",
        "drivers/nvme/host/pci.c:nvme_reset_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586928506,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586948855,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586976797,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587418346,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587438631,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587466573,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_hi_readq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587524890,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq",
        "drivers/usb/host/xhci.c:xhci_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587545607,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init",
        "drivers/usb/host/xhci-mem.c:xhci_mem_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587574198,
      "name": "lo_hi_readq",
      "external": false,
      "loc": "include/linux/io-64-nonatomic-lo-hi.h:8",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue",
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
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
__u64 lo_hi_readq(volatile const void * addr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
__u64 lo_hi_readq(volatile const void * addr)
```
</details>
</li>
</ul>
