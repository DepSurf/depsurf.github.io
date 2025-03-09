# Function: <code>proc_wait_for_resume</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587226646,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2458",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int proc_wait_for_resume(struct usb_dev_state * ps)
```

```json
{
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588067088,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2458",
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
      "addr": 18446744071588067088,
      "name": "proc_wait_for_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
int proc_wait_for_resume(struct usb_dev_state * ps)
```

```json
{
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588112384,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2470",
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
      "addr": 18446744071588112384,
      "name": "proc_wait_for_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588007691,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2475",
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
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588622608,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2553",
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
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590036784,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2569",
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
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591640074,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2569",
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
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592062555,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2578",
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
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592802844,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2578",
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
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500321704,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2458",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232784316,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2458",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293628144,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2458",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277218646,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2458",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586932726,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2458",
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
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586873878,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2458",
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
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587181206,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2458",
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
  "name": "proc_wait_for_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587288342,
      "name": "proc_wait_for_resume",
      "external": false,
      "loc": "drivers/usb/core/devio.c:2458",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int proc_wait_for_resume(struct usb_dev_state * ps)
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
int proc_wait_for_resume(struct usb_dev_state * ps)
```
</details>
</li>
</ul>
