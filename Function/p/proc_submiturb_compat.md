# Function: <code>proc_submiturb_compat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585255368,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:1806",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585650565,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2003",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585838342,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2003",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int proc_submiturb_compat(struct usb_dev_state * ps, void * arg)
```

```json
{
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585921312,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:1987",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585921312,
      "name": "proc_submiturb_compat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
int proc_submiturb_compat(struct usb_dev_state * ps, void * arg)
```

```json
{
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586362064,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:1996",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586362064,
      "name": "proc_submiturb_compat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
int proc_submiturb_compat(struct usb_dev_state * ps, void * arg)
```

```json
{
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586618976,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2007",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586618976,
      "name": "proc_submiturb_compat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
int proc_submiturb_compat(struct usb_dev_state * ps, void * arg)
```

```json
{
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586768144,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2007",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586768144,
      "name": "proc_submiturb_compat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587026816,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2030",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587225269,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2075",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588079048,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2075",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588123960,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2087",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588005577,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2092",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588620010,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2170",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590034915,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2186",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591637747,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2186",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592062810,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2195",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592803099,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2195",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500320284,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2075",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293631788,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2075",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586931349,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2075",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586872501,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2075",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587179829,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2075",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
  "name": "proc_submiturb_compat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587286965,
      "name": "proc_submiturb_compat",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2075",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_do_ioctl"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int proc_submiturb_compat(struct usb_dev_state * ps, void * arg)
```
</details>
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int proc_submiturb_compat(struct usb_dev_state * ps, void * arg)
```
</details>
</li>
</ul>
