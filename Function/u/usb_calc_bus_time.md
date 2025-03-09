# Function: <code>usb_calc_bus_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585186944,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1195",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585186944,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585579072,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1187",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585579072,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585766720,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1188",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585766720,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585853488,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1191",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585853488,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586293328,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1180",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586293328,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586550656,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1182",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586550656,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586699504,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1180",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ehci-hcd.c:qh_append_tds",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586699504,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586954400,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1085",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954400,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587153104,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1085",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587153104,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588002608,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1086",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:iso_stream_init",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002608,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588055280,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1087",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:iso_stream_init",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588055280,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587938096,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1087",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:iso_stream_init",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587938096,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588548480,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1094",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:iso_stream_init",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588548480,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589958576,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1094",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:iso_stream_init",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589958576,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591547792,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1094",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:iso_stream_init",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591547792,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591969408,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1098",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:iso_stream_init",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591969408,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592709248,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1073",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_qh_init",
        "drivers/usb/host/ehci-hcd.c:iso_stream_init",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592709248,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500229552,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1085",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500229552,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232707976,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1085",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232707976,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293521008,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1085",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_set_even_odd_frame",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293521008,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277150602,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1085",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_hc_set_even_odd_frame",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277150602,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586859184,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1085",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586859184,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586800624,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1085",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586800624,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587107664,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1085",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587107664,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
long int usb_calc_bus_time(int speed, int is_input, int isoc, int bytecount)
```

```json
{
  "name": "usb_calc_bus_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587215168,
      "name": "usb_calc_bus_time",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:1085",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create",
        "drivers/usb/host/ehci-hcd.c:iso_stream_find",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue",
        "drivers/usb/host/uhci-hcd.c:uhci_alloc_qh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587215168,
      "name": "usb_calc_bus_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
