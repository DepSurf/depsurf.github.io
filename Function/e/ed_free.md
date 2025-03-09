# Function: <code>ed_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585397160,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:135",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
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
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585793411,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:135",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
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
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585982163,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:133",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
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
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586065909,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:133",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
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
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586510357,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:134",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
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
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586784503,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:134",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
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
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586941639,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:130",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ed_free(struct ohci_hcd * hc, struct ed * ed)
```

```json
{
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587189248,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587189248,
      "name": "ed_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ed_free(struct ohci_hcd * hc, struct ed * ed)
```

```json
{
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587389536,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587389536,
      "name": "ed_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588261486,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:ed_get"
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
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588297134,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:ed_get"
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
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588179373,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:ed_get"
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
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588819309,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:ed_get"
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
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590238962,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:ed_get"
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
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591858012,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:ed_get"
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
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592280764,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:ed_get"
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
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593022076,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ed_get",
        "drivers/usb/host/ohci-hcd.c:ed_get"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void ed_free(struct ohci_hcd * hc, struct ed * ed)
```

```json
{
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500511536,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500511536,
      "name": "ed_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void ed_free(struct ohci_hcd * hc, struct ed * ed)
```

```json
{
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232968124,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232968124,
      "name": "ed_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void ed_free(struct ohci_hcd * hc, struct ed * ed)
```

```json
{
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293888208,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293888208,
      "name": "ed_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void ed_free(struct ohci_hcd * hc, struct ed * ed)
```

```json
{
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277395522,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277395522,
      "name": "ed_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void ed_free(struct ohci_hcd * hc, struct ed * ed)
```

```json
{
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587095616,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587095616,
      "name": "ed_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void ed_free(struct ohci_hcd * hc, struct ed * ed)
```

```json
{
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587344096,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587344096,
      "name": "ed_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void ed_free(struct ohci_hcd * hc, struct ed * ed)
```

```json
{
  "name": "ed_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587450928,
      "name": "ed_free",
      "external": false,
      "loc": "drivers/usb/host/ohci-mem.c:153",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:ohci_endpoint_disable",
        "drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587450928,
      "name": "ed_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void ed_free(struct ohci_hcd * hc, struct ed * ed)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void ed_free(struct ohci_hcd * hc, struct ed * ed)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void ed_free(struct ohci_hcd * hc, struct ed * ed)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
