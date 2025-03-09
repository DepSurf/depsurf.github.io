# Function: <code>usb_phy_roothub_power_off</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586632048,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:152",
      "file": "drivers/usb/core/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586632048,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586781120,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:153",
      "file": "drivers/usb/core/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586781120,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587037168,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:181",
      "file": "drivers/usb/core/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587037168,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587237488,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587237488,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588091477,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588091216,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588133429,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588133168,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588015605,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588015344,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588631637,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588631376,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590047221,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590046912,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591651541,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591651184,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592074181,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592073824,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592814453,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592814096,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500334696,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500334696,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232794504,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232794504,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293643632,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293643632,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277227644,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277227644,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586943568,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586943568,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586884736,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586884736,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587192048,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192048,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```

```json
{
  "name": "usb_phy_roothub_power_off",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587299120,
      "name": "usb_phy_roothub_power_off",
      "external": true,
      "loc": "drivers/usb/core/phy.c:202",
      "file": "drivers/usb/core/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/phy.c:usb_phy_roothub_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587299120,
      "name": "usb_phy_roothub_power_off",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void usb_phy_roothub_power_off(struct usb_phy_roothub * phy_roothub)
```
</details>
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
