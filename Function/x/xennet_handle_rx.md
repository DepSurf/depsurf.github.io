# Function: <code>xennet_handle_rx</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool xennet_handle_rx(struct netfront_queue * queue, unsigned int * eoi)
```

```json
{
  "name": "xennet_handle_rx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_handle_rx",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1495",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll_controller",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588405632,
      "name": "xennet_handle_rx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    },
    {
      "addr": 18446744071592547217,
      "name": "xennet_handle_rx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
bool xennet_handle_rx(struct netfront_queue * queue, unsigned int * eoi)
```

```json
{
  "name": "xennet_handle_rx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_handle_rx",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1532",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll_controller",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589799520,
      "name": "xennet_handle_rx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071594426389,
      "name": "xennet_handle_rx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool xennet_handle_rx(struct netfront_queue * queue, unsigned int * eoi)
```

```json
{
  "name": "xennet_handle_rx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_handle_rx",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1532",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll_controller",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591452816,
      "name": "xennet_handle_rx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071596268373,
      "name": "xennet_handle_rx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool xennet_handle_rx(struct netfront_queue * queue, unsigned int * eoi)
```

```json
{
  "name": "xennet_handle_rx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_handle_rx",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1532",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll_controller",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591868288,
      "name": "xennet_handle_rx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071596798173,
      "name": "xennet_handle_rx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
bool xennet_handle_rx(struct netfront_queue * queue, unsigned int * eoi)
```

```json
{
  "name": "xennet_handle_rx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_handle_rx",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1533",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll_controller",
        "drivers/net/xen-netfront.c:xennet_rx_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592608080,
      "name": "xennet_handle_rx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    },
    {
      "addr": 18446744071597721779,
      "name": "xennet_handle_rx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool xennet_handle_rx(struct netfront_queue * queue, unsigned int * eoi)
```
</details>
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
