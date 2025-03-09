# Function: <code>xen_irq_lateeoi</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags)
```

```json
{
  "name": "xen_irq_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586393728,
      "name": "xen_irq_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:676",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586393728,
      "name": "xen_irq_lateeoi",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags)
```

```json
{
  "name": "xen_irq_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586277680,
      "name": "xen_irq_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:706",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586277680,
      "name": "xen_irq_lateeoi",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags)
```

```json
{
  "name": "xen_irq_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586790592,
      "name": "xen_irq_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:706",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:domU_read_console",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll_controller",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_tx_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790592,
      "name": "xen_irq_lateeoi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags)
```

```json
{
  "name": "xen_irq_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588071376,
      "name": "xen_irq_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:706",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:domU_read_console",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll_controller",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_tx_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588071376,
      "name": "xen_irq_lateeoi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags)
```

```json
{
  "name": "xen_irq_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589453296,
      "name": "xen_irq_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:708",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:domU_read_console",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll_controller",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_tx_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589453296,
      "name": "xen_irq_lateeoi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags)
```

```json
{
  "name": "xen_irq_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589753024,
      "name": "xen_irq_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:709",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:domU_read_console",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll_controller",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_tx_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589753024,
      "name": "xen_irq_lateeoi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags)
```

```json
{
  "name": "xen_irq_lateeoi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590093168,
      "name": "xen_irq_lateeoi",
      "external": true,
      "loc": "drivers/xen/events/events_base.c:698",
      "file": "drivers/xen/events/events_base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:domU_read_console",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/net/xen-netfront.c:xennet_poll_controller",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt",
        "drivers/net/xen-netfront.c:xennet_tx_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590093168,
      "name": "xen_irq_lateeoi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
void xen_irq_lateeoi(unsigned int irq, unsigned int eoi_flags)
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
