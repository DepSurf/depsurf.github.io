# Function: <code>usb_dump_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585259905,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:426",
      "file": "drivers/usb/core/devices.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usb_device_dump"
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
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585655126,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:419",
      "file": "drivers/usb/core/devices.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usb_device_dump"
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
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585842902,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:413",
      "file": "drivers/usb/core/devices.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usb_device_dump"
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
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585929531,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:413",
      "file": "drivers/usb/core/devices.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usb_device_dump"
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
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586371339,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usb_device_dump"
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
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586628927,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usb_device_dump"
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
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586777999,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usb_device_dump"
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587033888,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033888,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1738
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587234192,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587234192,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1738
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588089088,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588089088,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588131184,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:381",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588131184,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588013376,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:368",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588013376,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588629136,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:368",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588629136,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590044560,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:364",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590044560,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591648720,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:364",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591648720,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592071408,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:364",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592071408,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592811680,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:364",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592811680,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500330576,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500330576,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1692
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232790636,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232790636,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1820
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293638928,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293638928,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1972
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277224590,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277224590,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1446
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586940272,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586940272,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1738
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586881440,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586881440,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1738
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587188752,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587188752,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1738
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
```

```json
{
  "name": "usb_dump_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587295824,
      "name": "usb_dump_desc",
      "external": false,
      "loc": "drivers/usb/core/devices.c:400",
      "file": "drivers/usb/core/devices.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devices.c:usb_device_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587295824,
      "name": "usb_dump_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1738
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
char * usb_dump_desc(char * start, char * end, struct usb_device * dev)
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
