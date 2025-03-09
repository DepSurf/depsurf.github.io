# Function: <code>dwc2_change_bus_speed</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585955396,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4894",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586398964,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4909",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586658372,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4974",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586812820,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4993",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587096648,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4848",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587297176,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4848",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
void dwc2_change_bus_speed(struct usb_hcd * hcd, int speed)
```

```json
{
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588152503,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4848",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588152503,
      "name": "dwc2_change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void dwc2_change_bus_speed(struct usb_hcd * hcd, int speed)
```

```json
{
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591556398,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4850",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591556398,
      "name": "dwc2_change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void dwc2_change_bus_speed(struct usb_hcd * hcd, int speed)
```

```json
{
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591498680,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4967",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591498680,
      "name": "dwc2_change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void dwc2_change_bus_speed(struct usb_hcd * hcd, int speed)
```

```json
{
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592584918,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4968",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592584918,
      "name": "dwc2_change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void dwc2_change_bus_speed(struct usb_hcd * hcd, int speed)
```

```json
{
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594465275,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4964",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594465275,
      "name": "dwc2_change_bus_speed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591700155,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4935",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592123531,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4935",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592864059,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4935",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500379560,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4848",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232836488,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4848",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293700468,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4848",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277265868,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4848",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587003256,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4848",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587251736,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4848",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
  "name": "dwc2_change_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587358504,
      "name": "dwc2_change_bus_speed",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd.c:4848",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_reset_device",
        "drivers/usb/dwc2/hcd.c:dwc2_free_dev"
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
void dwc2_change_bus_speed(struct usb_hcd * hcd, int speed)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void dwc2_change_bus_speed(struct usb_hcd * hcd, int speed)
```
</details>
</li>
</ul>
