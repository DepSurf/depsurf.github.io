# Function: <code>usb_match_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585221264,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:766",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221264,
      "name": "usb_match_id",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585614400,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:776",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585614400,
      "name": "usb_match_id",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585801936,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:779",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585801936,
      "name": "usb_match_id",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585891030,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:779",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585888304,
      "name": "usb_match_id.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585888416,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586331627,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:779",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586328816,
      "name": "usb_match_id.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071586328928,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586588715,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:779",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586586016,
      "name": "usb_match_id.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071586586128,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586737721,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:776",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586735024,
      "name": "usb_match_id.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071586735136,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586992920,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:771",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586990208,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071586990336,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587191992,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:771",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587189280,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071587189408,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588041874,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:806",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_device_match",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_device_match",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588041440,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071588041600,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588091582,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:806",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_device_match",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_device_match",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588090128,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071588090288,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587974366,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:802",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_device_match",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_device_match",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972912,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071587973072,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588585998,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:802",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_device_match",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_device_match",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588584544,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071588584704,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589996736,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:802",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_device_match",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589996736,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591592704,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:802",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_device_match",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591592704,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592014544,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:802",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_device_match",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592014544,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592754768,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:805",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_device_match",
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592754768,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500276360,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:771",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500273232,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446603336500273376,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232746724,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:771",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232743896,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 3232744028,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293576804,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:771",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293572272,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 13835058055293572464,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277187242,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:771",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277184476,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446743936277184584,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586898072,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:771",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586895360,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071586895488,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586839192,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:771",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586836480,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071586836608,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587146552,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:771",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587143840,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071587143968,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct usb_device_id * usb_match_id(struct usb_interface * interface, const struct usb_device_id * id)
```

```json
{
  "name": "usb_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587253624,
      "name": "usb_match_id",
      "external": true,
      "loc": "drivers/usb/core/driver.c:771",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ],
      "caller_func": [
        "drivers/usb/core/driver.c:usb_probe_interface"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587250928,
      "name": "usb_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071587251056,
      "name": "usb_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
