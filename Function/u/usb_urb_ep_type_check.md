# Function: <code>usb_urb_ep_type_check</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586308272,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:202",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586308272,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586566342,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:202",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_submit_urb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586565696,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586715382,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:202",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_submit_urb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586714736,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586970651,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:201",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_submit_urb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586969680,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587169691,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:202",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_submit_urb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587168720,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588018320,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:202",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/urb.c:usb_submit_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588018320,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588070608,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:224",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588070608,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587953136,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:224",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587953136,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563776,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:224",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563776,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589974800,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:224",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589974800,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591568336,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:225",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591568336,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591990080,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:225",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591990080,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592730000,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:225",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592730000,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500248900,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:202",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_submit_urb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500248184,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232723780,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:202",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_submit_urb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232722708,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293543436,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:202",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_submit_urb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293542064,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277165234,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:202",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_submit_urb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277164282,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586875771,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:202",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_submit_urb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586874800,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586816907,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:202",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_submit_urb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586815936,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587124251,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:202",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_submit_urb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123280,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int usb_urb_ep_type_check(const struct urb * urb)
```

```json
{
  "name": "usb_urb_ep_type_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587231355,
      "name": "usb_urb_ep_type_check",
      "external": true,
      "loc": "drivers/usb/core/urb.c:202",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_submit_urb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587230384,
      "name": "usb_urb_ep_type_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int usb_urb_ep_type_check(const struct urb * urb)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
