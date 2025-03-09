# Function: <code>wait_for_connected</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585566075,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3397",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585753755,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3323",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585841271,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3343",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586280663,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3346",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3390",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3411",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3452",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3496",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
int wait_for_connected(struct usb_device * udev, struct usb_hub * hub, int * port1, u16 * portchange, u16 * portstatus)
```

```json
{
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587965888,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3510",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_port_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965888,
      "name": "wait_for_connected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int wait_for_connected(struct usb_device * udev, struct usb_hub * hub, int * port1, u16 * portchange, u16 * portstatus)
```

```json
{
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588025648,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3528",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_port_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025648,
      "name": "wait_for_connected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3604",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3608",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3614",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3633",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3653",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3655",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3496",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3496",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3496",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277138656,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3496",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3496",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3496",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3496",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
  "name": "wait_for_connected",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_connected",
      "external": false,
      "loc": "drivers/usb/core/hub.c:3496",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:usb_port_resume"
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
int wait_for_connected(struct usb_device * udev, struct usb_hub * hub, int * port1, u16 * portchange, u16 * portstatus)
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
int wait_for_connected(struct usb_device * udev, struct usb_hub * hub, int * port1, u16 * portchange, u16 * portstatus)
```
</details>
</li>
</ul>
