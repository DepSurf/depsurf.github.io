# Function: <code>sfp_bus_put</code>

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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586426288,
      "name": "sfp_bus_put",
      "external": false,
      "loc": "drivers/net/phy/sfp-bus.c:331",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_register_upstream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586426288,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586571776,
      "name": "sfp_bus_put",
      "external": false,
      "loc": "drivers/net/phy/sfp-bus.c:331",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_register_upstream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586571776,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586823280,
      "name": "sfp_bus_put",
      "external": false,
      "loc": "drivers/net/phy/sfp-bus.c:331",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_register_upstream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586823280,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586969376,
      "name": "sfp_bus_put",
      "external": false,
      "loc": "drivers/net/phy/sfp-bus.c:331",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_register_upstream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586969376,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587794259,
      "name": "sfp_bus_put",
      "external": true,
      "loc": "drivers/net/phy/sfp-bus.c:449",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_sfp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587793920,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587852307,
      "name": "sfp_bus_put",
      "external": true,
      "loc": "drivers/net/phy/sfp-bus.c:463",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_sfp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587851968,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587731715,
      "name": "sfp_bus_put",
      "external": true,
      "loc": "drivers/net/phy/sfp-bus.c:480",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_sfp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587731376,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588325219,
      "name": "sfp_bus_put",
      "external": true,
      "loc": "drivers/net/phy/sfp-bus.c:485",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_sfp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588324880,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589715694,
      "name": "sfp_bus_put",
      "external": true,
      "loc": "drivers/net/phy/sfp-bus.c:491",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_sfp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589715296,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591332750,
      "name": "sfp_bus_put",
      "external": true,
      "loc": "drivers/net/phy/sfp-bus.c:440",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_sfp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591332320,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591694270,
      "name": "sfp_bus_put",
      "external": true,
      "loc": "drivers/net/phy/sfp-bus.c:450",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_sfp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591693840,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592437294,
      "name": "sfp_bus_put",
      "external": true,
      "loc": "drivers/net/phy/sfp-bus.c:450",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_sfp_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592436864,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499960736,
      "name": "sfp_bus_put",
      "external": false,
      "loc": "drivers/net/phy/sfp-bus.c:331",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_register_upstream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499960736,
      "name": "sfp_bus_put",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232499632,
      "name": "sfp_bus_put",
      "external": false,
      "loc": "drivers/net/phy/sfp-bus.c:331",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_register_upstream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232499632,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293286080,
      "name": "sfp_bus_put",
      "external": false,
      "loc": "drivers/net/phy/sfp-bus.c:331",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_register_upstream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293286080,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277039752,
      "name": "sfp_bus_put",
      "external": false,
      "loc": "drivers/net/phy/sfp-bus.c:331",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_register_upstream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277039752,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586726384,
      "name": "sfp_bus_put",
      "external": false,
      "loc": "drivers/net/phy/sfp-bus.c:331",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_register_upstream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586726384,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586593600,
      "name": "sfp_bus_put",
      "external": false,
      "loc": "drivers/net/phy/sfp-bus.c:331",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_register_upstream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586593600,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586923936,
      "name": "sfp_bus_put",
      "external": false,
      "loc": "drivers/net/phy/sfp-bus.c:331",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_register_upstream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586923936,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void sfp_bus_put(struct sfp_bus * bus)
```

```json
{
  "name": "sfp_bus_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587030384,
      "name": "sfp_bus_put",
      "external": false,
      "loc": "drivers/net/phy/sfp-bus.c:331",
      "file": "drivers/net/phy/sfp-bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/sfp-bus.c:sfp_unregister_socket",
        "drivers/net/phy/sfp-bus.c:sfp_register_socket",
        "drivers/net/phy/sfp-bus.c:sfp_unregister_upstream",
        "drivers/net/phy/sfp-bus.c:sfp_register_upstream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587030384,
      "name": "sfp_bus_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void sfp_bus_put(struct sfp_bus * bus)
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
