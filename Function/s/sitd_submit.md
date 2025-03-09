# Function: <code>sitd_submit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585381161,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2319",
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
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585777647,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2319",
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
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585966351,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2318",
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
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586050078,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2318",
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
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586494319,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2305",
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
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586758679,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2306",
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
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586916375,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2302",
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587165968,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2302",
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
      "addr": 18446744071587165968,
      "name": "sitd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1571
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587366400,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2302",
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
      "addr": 18446744071587366400,
      "name": "sitd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1571
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588217920,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2302",
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
      "addr": 18446744071588217920,
      "name": "sitd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588255584,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2294",
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
      "addr": 18446744071588255584,
      "name": "sitd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588136256,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2294",
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
      "addr": 18446744071588136256,
      "name": "sitd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588773712,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2294",
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
      "addr": 18446744071588773712,
      "name": "sitd_submit",
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590205376,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2292",
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
      "addr": 18446744071590205376,
      "name": "sitd_submit",
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591823296,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2292",
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
      "addr": 18446744071591823296,
      "name": "sitd_submit",
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592246144,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2292",
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
      "addr": 18446744071592246144,
      "name": "sitd_submit",
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592988864,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2293",
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
      "addr": 18446744071592988864,
      "name": "sitd_submit",
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500492192,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2302",
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
      "addr": 18446603336500492192,
      "name": "sitd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1604
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232946760,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2302",
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
      "addr": 3232946760,
      "name": "sitd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1644
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293857376,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2302",
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
      "addr": 13835058055293857376,
      "name": "sitd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1816
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277363558,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2302",
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
      "addr": 18446743936277363558,
      "name": "sitd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1240
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587072480,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2302",
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
      "addr": 18446744071587072480,
      "name": "sitd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1571
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587320960,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2302",
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
      "addr": 18446744071587320960,
      "name": "sitd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1571
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "sitd_submit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587427536,
      "name": "sitd_submit",
      "external": false,
      "loc": "drivers/usb/host/ehci-sched.c:2302",
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
      "addr": 18446744071587427536,
      "name": "sitd_submit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1571
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
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
int sitd_submit(struct ehci_hcd * ehci, struct urb * urb, gfp_t mem_flags)
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
