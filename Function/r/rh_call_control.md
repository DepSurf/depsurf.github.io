# Function: <code>rh_call_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585196049,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:486",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
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
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585588275,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:485",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
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
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585775891,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:486",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
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
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585862825,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:487",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
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
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586302680,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:474",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
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
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586559608,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:474",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
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
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586708388,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:474",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586960416,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:477",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586960416,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2700
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587159424,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:477",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587159424,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2700
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588009264,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:478",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588009264,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2588
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588061472,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:478",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588061472,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2603
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587943520,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:478",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587943520,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2667
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588554032,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:478",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588554032,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2661
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589962848,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:478",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589962848,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1941
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591554128,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:478",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591554128,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1957
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591975760,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:478",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591975760,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2068
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592715744,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:457",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592715744,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2082
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500235792,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:477",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500235792,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2284
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232711424,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:477",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232711424,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2004
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293530384,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:477",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293530384,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2600
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277157962,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:477",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277157962,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1814
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586865504,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:477",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586865504,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2700
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586805136,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:477",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586805136,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2688
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587113984,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:477",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587113984,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2700
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
```

```json
{
  "name": "rh_call_control",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587219104,
      "name": "rh_call_control",
      "external": false,
      "loc": "drivers/usb/core/hcd.c:477",
      "file": "drivers/usb/core/hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587219104,
      "name": "rh_call_control",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2577
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
int rh_call_control(struct usb_hcd * hcd, struct urb * urb)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
