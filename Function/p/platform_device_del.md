# Function: <code>platform_device_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584406864,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:412",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584406864,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584742256,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:432",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584742256,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584932272,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:447",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584932272,
      "name": "platform_device_del",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585019254,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:447",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585018096,
      "name": "platform_device_del.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071585018240,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585441574,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:447",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585440416,
      "name": "platform_device_del.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071585440560,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585684630,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:446",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585683120,
      "name": "platform_device_del.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071585683264,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585814812,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:447",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813280,
      "name": "platform_device_del.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071585813408,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586048236,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:487",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586046640,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071586046768,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586196332,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:565",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586194592,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071586194720,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586958892,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:626",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586955824,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071586955952,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587044632,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:778",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587040880,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071587041008,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586928456,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:777",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586924688,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071586924816,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587490904,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:741",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587487360,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071592489740,
      "name": "platform_device_del.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587487504,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588813697,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:746",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588809824,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071594359429,
      "name": "platform_device_del.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588809968,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590312001,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:746",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590307792,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071596246838,
      "name": "platform_device_del.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590307952,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590632481,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:746",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590628240,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071596775202,
      "name": "platform_device_del.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590628400,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590991713,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:746",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_add_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590987456,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071597684452,
      "name": "platform_device_del.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590987616,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498996904,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:565",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498994720,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446603336498994864,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231564288,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:565",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231562916,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 3231563048,
      "name": "platform_device_del",
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292154412,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:565",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292151040,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 13835058055292151232,
      "name": "platform_device_del",
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276370942,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:565",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276369524,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446743936276369656,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585956540,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:565",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585954800,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071585954928,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585805756,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:565",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585804016,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071585804144,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586146348,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:565",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586144608,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071586144736,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void platform_device_del(struct platform_device * pdev)
```

```json
{
  "name": "platform_device_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586255052,
      "name": "platform_device_del",
      "external": true,
      "loc": "drivers/base/platform.c:565",
      "file": "drivers/base/platform.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_core.c:serial8250_init",
        "drivers/base/platform.c:__platform_create_bundle",
        "drivers/base/platform.c:platform_device_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586253296,
      "name": "platform_device_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071586253424,
      "name": "platform_device_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
