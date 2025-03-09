# Function: <code>itd_submit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585381144,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1939",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
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
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585777630,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1938",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
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
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585966334,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1937",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
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
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586050061,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1937",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
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
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586494302,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1924",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
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
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586759620,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1925",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
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
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586917316,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1923",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587167552,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1923",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587167552,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1784
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587367984,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1923",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587367984,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1784
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588221104,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1923",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588221104,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588258768,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588258768,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588139440,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588139440,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588777280,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777280,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590209104,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1913",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590209104,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591827136,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1913",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591827136,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592249952,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1913",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592249952,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592987856,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1914",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592987856,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500490400,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1923",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500490400,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1792
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232948404,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1923",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232948404,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1836
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293862064,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1923",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293862064,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2220
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277362132,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1923",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277362132,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1426
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587074064,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1923",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587074064,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1784
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587322544,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1923",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587322544,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1784
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "itd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587429120,
      "name": "itd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:1923",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587429120,
      "name": "itd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1784
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
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int itd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
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
