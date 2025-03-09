# Function: <code>hvm_get_parameter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583886768,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:38",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071584085293,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:38",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886768,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584217520,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:38",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071584416760,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:38",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584217520,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584398944,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:38",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071584599160,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:38",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584398944,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584481344,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:38",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071584681693,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:38",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584481344,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584891616,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585094189,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584891616,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585125860,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585327947,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585122736,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071585125937,
      "name": "hvm_get_parameter.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585236676,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585451403,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585233616,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071585236787,
      "name": "hvm_get_parameter.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585448822,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585667233,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585445760,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071585448934,
      "name": "hvm_get_parameter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585589254,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585808209,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585586192,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071585589366,
      "name": "hvm_get_parameter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586310566,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071586539342,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586308816,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071586311151,
      "name": "hvm_get_parameter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586429446,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071586650558,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586427472,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071591450091,
      "name": "hvm_get_parameter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586313586,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071586534500,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586311568,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071591391844,
      "name": "hvm_get_parameter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586833298,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071587072916,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586831168,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071592436080,
      "name": "hvm_get_parameter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588118113,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_late_init"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071588376316,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588115456,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071594304063,
      "name": "hvm_get_parameter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071628042399,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589798626,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
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
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619807919,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590103970,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
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
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622116399,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590443410,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498252880,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446603336498528964,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498252880,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585351670,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585569201,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585348128,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071585351749,
      "name": "hvm_get_parameter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585539654,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585758609,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585536592,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071585539766,
      "name": "hvm_get_parameter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```

```json
{
  "name": "hvm_get_parameter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585647638,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ]
    },
    {
      "addr": 18446744071585866513,
      "name": "hvm_get_parameter",
      "external": false,
      "loc": "include/xen/hvm.h:39",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_console_resume",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init",
        "drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585644576,
      "name": "hvm_get_parameter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071585647750,
      "name": "hvm_get_parameter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int hvm_get_parameter(int idx, uint64_t * value)
```
</details>
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
int hvm_get_parameter(int idx, uint64_t * value)
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
