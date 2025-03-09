# Function: <code>dwc2_force_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585667968,
      "name": "dwc2_force_mode",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:307",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/core.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667968,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585855904,
      "name": "dwc2_force_mode",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:402",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_mode_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585855904,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
bool dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585942416,
      "name": "dwc2_force_mode",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:402",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_mode_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585942416,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
bool dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586385520,
      "name": "dwc2_force_mode",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:403",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_mode_if_needed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586385520,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586645136,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:573",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586645136,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586794000,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:573",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586794000,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587050158,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:573",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054307,
      "name": "dwc2_force_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587050096,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587250496,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:573",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587250496,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588106544,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:588",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588106544,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588148304,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:588",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588148304,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588029744,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:532",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588029744,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:532",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592576264,
      "name": "dwc2_force_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071588647840,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:532",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/drd.c:dwc2_drd_resume",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594456232,
      "name": "dwc2_force_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071590064576,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:502",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/drd.c:dwc2_drd_resume",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596275235,
      "name": "dwc2_force_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071591672128,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:502",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/drd.c:dwc2_drd_resume",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596805081,
      "name": "dwc2_force_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071592094992,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:502",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/platform.c:dwc2_suspend",
        "drivers/usb/dwc2/drd.c:dwc2_drd_resume",
        "drivers/usb/dwc2/drd.c:dwc2_drd_init",
        "drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597728688,
      "name": "dwc2_force_mode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071592835424,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500358456,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:573",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500358456,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232818612,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:573",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232818612,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293667376,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:573",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293667376,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277241868,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:573",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277241868,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586956576,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:573",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586956576,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587205056,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:573",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587205056,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```

```json
{
  "name": "dwc2_force_mode",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587312128,
      "name": "dwc2_force_mode",
      "external": true,
      "loc": "drivers/usb/dwc2/core.c:573",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_force_dr_mode",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams",
        "drivers/usb/dwc2/params.c:dwc2_get_hwparams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587312128,
      "name": "dwc2_force_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
```
</details>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void dwc2_force_mode(struct dwc2_hsotg * hsotg, bool host)
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
