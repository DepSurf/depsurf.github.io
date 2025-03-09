# Function: <code>alloc_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585355408,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:939",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446744071585407792,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:664",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585355408,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585407792,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585751744,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:925",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446744071585803824,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:664",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585751744,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585803824,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585939936,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:925",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446744071585992496,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:664",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585939936,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071585992496,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586023840,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:925",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446744071586076096,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:664",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586023840,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071586076096,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586468048,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446744071586520544,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586468048,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071586520544,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586732048,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446744071586781248,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586732048,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586781248,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586877488,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446744071586928416,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586877488,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071586928416,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136048,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446744071587188000,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136048,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587188000,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587336448,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446744071587388288,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587336448,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587388288,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588205314,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588251762,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
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
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588241954,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588287410,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
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
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588126706,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588170514,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
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
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588763058,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588811954,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
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
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590187058,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590235698,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
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
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591803362,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591857586,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
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
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592227474,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592277250,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
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
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592968734,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593021614,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500454224,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446603336500510096,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500454224,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446603336500510096,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232910968,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 3232965176,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232910968,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 3232965176,
      "name": "alloc_buffer",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293824720,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 13835058055293890496,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293824720,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 13835058055293890496,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277341994,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446743936277393190,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277341994,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446743936277393190,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587042528,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446744071587094368,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587042528,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587094368,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587291008,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446744071587342848,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587291008,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587342848,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
```

```json
{
  "name": "alloc_buffer",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587399296,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:915",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ehci-hcd.c:debug_registers_open",
        "drivers/usb/host/ehci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ehci-hcd.c:debug_bandwidth_open",
        "drivers/usb/host/ehci-hcd.c:debug_async_open"
      ]
    },
    {
      "addr": 18446744071587449680,
      "name": "alloc_buffer",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:665",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/ohci-hcd.c:debug_registers_open",
        "drivers/usb/host/ohci-hcd.c:debug_periodic_open",
        "drivers/usb/host/ohci-hcd.c:debug_async_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399296,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587449680,
      "name": "alloc_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
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
struct debug_buffer * alloc_buffer(struct usb_bus * bus, ssize_t (*)(struct debug_buffer *) fill_func)
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
