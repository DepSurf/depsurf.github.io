# Function: <code>port_over_current_notify</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586691751,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5171",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586944000,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5218",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587142736,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5263",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
void port_over_current_notify(struct usb_port * port_dev)
```

```json
{
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587966608,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5387",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587966608,
      "name": "port_over_current_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void port_over_current_notify(struct usb_port * port_dev)
```

```json
{
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588026368,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5402",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:port_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588026368,
      "name": "port_over_current_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587934229,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5526",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588544405,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5539",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589953878,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5546",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591538535,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5556",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591960214,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5627",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592699862,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5628",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500221052,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5263",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232700080,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5263",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293512032,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5263",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277143540,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5263",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586848816,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5263",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586791024,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5263",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587097296,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5263",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
  "name": "port_over_current_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587204544,
      "name": "port_over_current_notify",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5263",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:port_event"
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
void port_over_current_notify(struct usb_port * port_dev)
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
void port_over_current_notify(struct usb_port * port_dev)
```
</details>
</li>
</ul>
