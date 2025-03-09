# Function: <code>check_ctrlrecip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585245920,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:714",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245920,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585638144,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:828",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585638144,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585825728,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:828",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585825728,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585913136,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:822",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585913136,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586353920,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:812",
      "file": "drivers/usb/core/devio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586353920,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586610608,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:808",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586610608,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586760192,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:809",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586760192,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:804",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587015200,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071587028770,
      "name": "check_ctrlrecip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:847",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587214832,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071587228946,
      "name": "check_ctrlrecip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:856",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588067840,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071588082462,
      "name": "check_ctrlrecip.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:856",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588113648,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071591551500,
      "name": "check_ctrlrecip.cold",
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:856",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587995056,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071591493683,
      "name": "check_ctrlrecip.cold",
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:857",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588608608,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071592571175,
      "name": "check_ctrlrecip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:869",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590022432,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    },
    {
      "addr": 18446744071594450843,
      "name": "check_ctrlrecip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591622864,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:869",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591622864,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592045392,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:878",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592045392,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592785456,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:878",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592785456,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500299944,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:847",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500299944,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232768556,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:847",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232768556,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293606624,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:847",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293606624,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277208360,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:847",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277208360,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:847",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586920912,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071586935026,
      "name": "check_ctrlrecip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:847",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586862080,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071586876178,
      "name": "check_ctrlrecip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:847",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587169392,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071587183506,
      "name": "check_ctrlrecip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int check_ctrlrecip(struct usb_dev_state * ps, unsigned int requesttype, unsigned int request, unsigned int index)
```

```json
{
  "name": "check_ctrlrecip",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_ctrlrecip",
      "external": false,
      "loc": "drivers/usb/core/devio.c:847",
      "file": "drivers/usb/core/devio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587276464,
      "name": "check_ctrlrecip",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071587290642,
      "name": "check_ctrlrecip.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
