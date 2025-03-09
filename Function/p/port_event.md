# Function: <code>port_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585179104,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4984",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event"
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
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585571170,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5002",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event"
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
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585758866,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:4979",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585845280,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5000",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585845280,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1709
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586285374,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5038",
      "file": "drivers/usb/core/hub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586542560,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5108",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586542560,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1730
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
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586691200,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5207",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586691200,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1940
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5254",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586943456,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1912
    },
    {
      "addr": 18446744071586950256,
      "name": "port_event.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5299",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587142192,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1912
    },
    {
      "addr": 18446744071587148947,
      "name": "port_event.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5423",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587991648,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1263
    },
    {
      "addr": 18446744071587998387,
      "name": "port_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5438",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588051264,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1263
    },
    {
      "addr": 18446744071591540188,
      "name": "port_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5562",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587933600,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1781
    },
    {
      "addr": 18446744071591482555,
      "name": "port_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5575",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588543776,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1781
    },
    {
      "addr": 18446744071592559870,
      "name": "port_event.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5580",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589953120,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1907
    },
    {
      "addr": 18446744071594438750,
      "name": "port_event.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591537792,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5590",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591537792,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2057
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
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591959472,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5661",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591959472,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2056
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
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592699120,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5662",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592699120,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2056
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
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500220424,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5299",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500220424,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1992
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
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232699312,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5299",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232699312,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2164
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
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293511136,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5299",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293511136,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2360
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
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277142970,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5299",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277142970,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1856
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5299",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586848272,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1912
    },
    {
      "addr": 18446744071586855027,
      "name": "port_event.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5299",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790480,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1912
    },
    {
      "addr": 18446744071586796516,
      "name": "port_event.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5299",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587096752,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1912
    },
    {
      "addr": 18446744071587103507,
      "name": "port_event.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void port_event(struct usb_hub * hub, int port1)
```

```json
{
  "name": "port_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "port_event",
      "external": false,
      "loc": "drivers/usb/core/hub.c:5299",
      "file": "drivers/usb/core/hub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587204000,
      "name": "port_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1912
    },
    {
      "addr": 18446744071587210755,
      "name": "port_event.cold",
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void port_event(struct usb_hub * hub, int port1)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void port_event(struct usb_hub * hub, int port1)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void port_event(struct usb_hub * hub, int port1)
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
