# Function: <code>do_proc_bulk</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int do_proc_bulk(struct usb_dev_state * ps, struct usbdevfs_bulktransfer * bulk)
```

```json
{
  "name": "do_proc_bulk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_proc_bulk",
      "external": false,
      "loc": "drivers/usb/core/devio.c:1194",
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
      "addr": 18446744071588114512,
      "name": "do_proc_bulk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 707
    },
    {
      "addr": 18446744071591551892,
      "name": "do_proc_bulk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int do_proc_bulk(struct usb_dev_state * ps, struct usbdevfs_bulktransfer * bulk)
```

```json
{
  "name": "do_proc_bulk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_proc_bulk",
      "external": false,
      "loc": "drivers/usb/core/devio.c:1194",
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
      "addr": 18446744071587995920,
      "name": "do_proc_bulk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 701
    },
    {
      "addr": 18446744071591494026,
      "name": "do_proc_bulk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
int do_proc_bulk(struct usb_dev_state * ps, struct usbdevfs_bulktransfer * bulk)
```

```json
{
  "name": "do_proc_bulk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588609824,
      "name": "do_proc_bulk",
      "external": false,
      "loc": "drivers/usb/core/devio.c:1255",
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
      "addr": 18446744071588609824,
      "name": "do_proc_bulk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
int do_proc_bulk(struct usb_dev_state * ps, struct usbdevfs_bulktransfer * bulk)
```

```json
{
  "name": "do_proc_bulk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590032592,
      "name": "do_proc_bulk",
      "external": false,
      "loc": "drivers/usb/core/devio.c:1271",
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
      "addr": 18446744071590032592,
      "name": "do_proc_bulk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1174
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
int do_proc_bulk(struct usb_dev_state * ps, struct usbdevfs_bulktransfer * bulk)
```

```json
{
  "name": "do_proc_bulk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591635376,
      "name": "do_proc_bulk",
      "external": false,
      "loc": "drivers/usb/core/devio.c:1271",
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
      "addr": 18446744071591635376,
      "name": "do_proc_bulk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1163
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
int do_proc_bulk(struct usb_dev_state * ps, struct usbdevfs_bulktransfer * bulk)
```

```json
{
  "name": "do_proc_bulk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592057984,
      "name": "do_proc_bulk",
      "external": false,
      "loc": "drivers/usb/core/devio.c:1280",
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
      "addr": 18446744071592057984,
      "name": "do_proc_bulk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1157
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
int do_proc_bulk(struct usb_dev_state * ps, struct usbdevfs_bulktransfer * bulk)
```

```json
{
  "name": "do_proc_bulk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592798288,
      "name": "do_proc_bulk",
      "external": false,
      "loc": "drivers/usb/core/devio.c:1280",
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
      "addr": 18446744071592798288,
      "name": "do_proc_bulk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1157
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
int do_proc_bulk(struct usb_dev_state * ps, struct usbdevfs_bulktransfer * bulk)
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
