# Function: <code>dbc_ep_do_queue</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586659487,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:289",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586923251,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:290",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587080291,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:290",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587344261,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:290",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int dbc_ep_do_queue(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:289",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587544096,
      "name": "dbc_ep_do_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
    },
    {
      "addr": 18446744071587547435,
      "name": "dbc_ep_do_queue.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dbc_ep_do_queue(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:289",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588407920,
      "name": "dbc_ep_do_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
    },
    {
      "addr": 18446744071588410543,
      "name": "dbc_ep_do_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int dbc_ep_do_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:295",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588438224,
      "name": "dbc_ep_do_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    },
    {
      "addr": 18446744071591569012,
      "name": "dbc_ep_do_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int dbc_ep_do_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:295",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588321184,
      "name": "dbc_ep_do_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    },
    {
      "addr": 18446744071591512171,
      "name": "dbc_ep_do_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dbc_ep_do_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:295",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588978704,
      "name": "dbc_ep_do_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    },
    {
      "addr": 18446744071592615241,
      "name": "dbc_ep_do_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int dbc_ep_do_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:295",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590413680,
      "name": "dbc_ep_do_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
    },
    {
      "addr": 18446744071594498830,
      "name": "dbc_ep_do_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int dbc_ep_do_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:295",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592049360,
      "name": "dbc_ep_do_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
    },
    {
      "addr": 18446744071596301767,
      "name": "dbc_ep_do_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int dbc_ep_do_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:295",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592472064,
      "name": "dbc_ep_do_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
    },
    {
      "addr": 18446744071596831093,
      "name": "dbc_ep_do_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int dbc_ep_do_queue(struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:310",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593213696,
      "name": "dbc_ep_do_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
    },
    {
      "addr": 18446744071597755084,
      "name": "dbc_ep_do_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500689220,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:289",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int dbc_ep_do_queue(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233144100,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:289",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233144100,
      "name": "dbc_ep_do_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294122156,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:289",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277546706,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:289",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int dbc_ep_do_queue(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:289",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587008880,
      "name": "dbc_ep_do_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
    },
    {
      "addr": 18446744071587012219,
      "name": "dbc_ep_do_queue.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int dbc_ep_do_queue(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:289",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587498656,
      "name": "dbc_ep_do_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
    },
    {
      "addr": 18446744071587501995,
      "name": "dbc_ep_do_queue.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int dbc_ep_do_queue(struct dbc_ep * dep, struct dbc_request * req)
```

```json
{
  "name": "dbc_ep_do_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dbc_ep_do_queue",
      "external": false,
      "loc": "drivers/usb/host/xhci-dbgcap.c:289",
      "file": "drivers/usb/host/xhci-dbgcap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587606384,
      "name": "dbc_ep_do_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
    },
    {
      "addr": 18446744071587609867,
      "name": "dbc_ep_do_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int dbc_ep_do_queue(struct dbc_ep * dep, struct dbc_request * req)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct dbc_ep * dep</code>
</li>
<li>
<b>Param reordered. </b>
<code>dep, req</code> ➡️ <code>req</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int dbc_ep_do_queue(struct dbc_ep * dep, struct dbc_request * req)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int dbc_ep_do_queue(struct dbc_ep * dep, struct dbc_request * req)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int dbc_ep_do_queue(struct dbc_ep * dep, struct dbc_request * req)
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
int dbc_ep_do_queue(struct dbc_ep * dep, struct dbc_request * req)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
