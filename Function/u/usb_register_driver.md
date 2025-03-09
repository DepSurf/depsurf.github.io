# Function: <code>usb_register_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585217984,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:937",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585217984,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585611056,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:947",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585611056,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585798592,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:950",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585798592,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585885648,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:950",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585885648,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586326112,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:950",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586326112,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586583232,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:950",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586583232,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586733360,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:947",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586733360,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586993984,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:942",
      "file": "drivers/usb/core/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586993984,
      "name": "usb_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586988512,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:943",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192742,
      "name": "usb_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587185920,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1035",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588044499,
      "name": "usb_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588036720,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1046",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591547626,
      "name": "usb_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588085600,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1042",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591489968,
      "name": "usb_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587968400,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1042",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592567631,
      "name": "usb_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071588579872,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1043",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594446648,
      "name": "usb_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071589991760,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591586976,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1043",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591586976,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592008800,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1043",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592008800,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592748944,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:1050",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592748944,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500269056,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:943",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500269056,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232740936,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:943",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232740936,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293566832,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:943",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293566832,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277181122,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:943",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277181122,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:943",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586898822,
      "name": "usb_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586892000,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:943",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586839942,
      "name": "usb_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071586833120,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:943",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587147302,
      "name": "usb_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587140480,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int usb_register_driver(struct usb_driver * new_driver, struct module * owner, const char * mod_name)
```

```json
{
  "name": "usb_register_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_register_driver",
      "external": true,
      "loc": "drivers/usb/core/driver.c:943",
      "file": "drivers/usb/core/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb.c:usb_init",
        "drivers/usb/core/hub.c:usb_hub_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587254374,
      "name": "usb_register_driver.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071587248304,
      "name": "usb_register_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
