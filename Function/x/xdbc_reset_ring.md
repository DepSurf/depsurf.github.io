# Function: <code>xdbc_reset_ring</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void xdbc_reset_ring(struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_reset_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587099056,
      "name": "xdbc_reset_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:198",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587099056,
      "name": "xdbc_reset_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void xdbc_reset_ring(struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_reset_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587363904,
      "name": "xdbc_reset_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:198",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587363904,
      "name": "xdbc_reset_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void xdbc_reset_ring(struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_reset_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587565744,
      "name": "xdbc_reset_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:198",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587565744,
      "name": "xdbc_reset_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void xdbc_reset_ring(struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_reset_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588427093,
      "name": "xdbc_reset_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:197",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588425872,
      "name": "xdbc_reset_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void xdbc_reset_ring(struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_reset_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588457317,
      "name": "xdbc_reset_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:192",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456384,
      "name": "xdbc_reset_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xdbc_reset_ring(struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_reset_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588339621,
      "name": "xdbc_reset_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:192",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588338912,
      "name": "xdbc_reset_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xdbc_reset_ring(struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_reset_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588999077,
      "name": "xdbc_reset_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:199",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588997888,
      "name": "xdbc_reset_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void xdbc_reset_ring(struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_reset_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590433440,
      "name": "xdbc_reset_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:199",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590433440,
      "name": "xdbc_reset_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void xdbc_reset_ring(struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_reset_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592071968,
      "name": "xdbc_reset_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:199",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592071968,
      "name": "xdbc_reset_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void xdbc_reset_ring(struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_reset_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592494896,
      "name": "xdbc_reset_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:199",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592494896,
      "name": "xdbc_reset_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void xdbc_reset_ring(struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_reset_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593239280,
      "name": "xdbc_reset_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:199",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593239280,
      "name": "xdbc_reset_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void xdbc_reset_ring(struct xdbc_ring * ring)
```

```json
{
  "name": "xdbc_reset_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587628208,
      "name": "xdbc_reset_ring",
      "external": false,
      "loc": "drivers/usb/early/xhci-dbc.c:198",
      "file": "drivers/usb/early/xhci-dbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_mem_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587628208,
      "name": "xdbc_reset_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void xdbc_reset_ring(struct xdbc_ring * ring)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void xdbc_reset_ring(struct xdbc_ring * ring)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xdbc_reset_ring(struct xdbc_ring * ring)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xdbc_reset_ring(struct xdbc_ring * ring)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xdbc_reset_ring(struct xdbc_ring * ring)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void xdbc_reset_ring(struct xdbc_ring * ring)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void xdbc_reset_ring(struct xdbc_ring * ring)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void xdbc_reset_ring(struct xdbc_ring * ring)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
