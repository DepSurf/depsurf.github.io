# Function: <code>ohci_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585395424,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1212",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585395424,
      "name": "ohci_work.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1410
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585806333,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1213",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585791728,
      "name": "ohci_work.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585995005,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1213",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585980480,
      "name": "ohci_work.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586078507,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1213",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586064192,
      "name": "ohci_work.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1419
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586522971,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586508640,
      "name": "ohci_work.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1412
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586786973,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586781888,
      "name": "ohci_work.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586944109,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586939024,
      "name": "ohci_work.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1344
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587200896,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587195920,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587401184,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587396208,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ohci_work(struct ohci_hcd * ohci)
```

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588260416,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588260416,
      "name": "ohci_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ohci_work(struct ohci_hcd * ohci)
```

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588296064,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296064,
      "name": "ohci_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588182976,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588178768,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588822938,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588818704,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590245606,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590235936,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591864950,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591854736,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592287846,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592277520,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593029158,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593018736,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500530984,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500513272,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
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
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232981052,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232968192,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1416
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
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293912252,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293891872,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1712
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
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277410672,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277404856,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1342
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
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587107264,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587102288,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1425
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587355744,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587350768,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ohci_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587461485,
      "name": "ohci_work",
      "external": false,
      "loc": "drivers/usb/host/ohci-q.c:1217",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_restart",
        "drivers/usb/host/ohci-hcd.c:ohci_irq",
        "drivers/usb/host/ohci-hcd.c:io_watchdog_func",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_dequeue",
        "drivers/usb/host/ohci-hcd.c:ohci_rh_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587450992,
      "name": "ohci_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1425
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void ohci_work(struct ohci_hcd * ohci)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void ohci_work(struct ohci_hcd * ohci)
```
</details>
</li>
</ul>
