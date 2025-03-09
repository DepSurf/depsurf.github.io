# Function: <code>serdev_controller_alloc</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585176288,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:345",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585176288,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585411856,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:388",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585411856,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585535536,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:477",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585535536,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:477",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585756239,
      "name": "serdev_controller_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071585755232,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:477",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585898498,
      "name": "serdev_controller_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585897472,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:478",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586636885,
      "name": "serdev_controller_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071586636064,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:478",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591461971,
      "name": "serdev_controller_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071586745072,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:478",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591403544,
      "name": "serdev_controller_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071586628320,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:476",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592454344,
      "name": "serdev_controller_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071587174960,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:476",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594322762,
      "name": "serdev_controller_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588487536,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589923856,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:476",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589923856,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590233120,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:487",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590233120,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
struct serdev_controller * serdev_controller_alloc(struct device * host, struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590573824,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:478",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590573824,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498716232,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:477",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498716232,
      "name": "serdev_controller_alloc",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231343400,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:477",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231343400,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291867408,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:477",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291867408,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276230190,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:477",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276230190,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:477",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585659490,
      "name": "serdev_controller_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585658464,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:477",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585848898,
      "name": "serdev_controller_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585847872,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```

```json
{
  "name": "serdev_controller_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "serdev_controller_alloc",
      "external": true,
      "loc": "drivers/tty/serdev/core.c:477",
      "file": "drivers/tty/serdev/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serdev/serdev-ttyport.c:serdev_tty_port_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585956514,
      "name": "serdev_controller_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585955488,
      "name": "serdev_controller_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * host</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, size</code> ➡️ <code>host, parent, size</code>
</li>
</ul>
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
struct serdev_controller * serdev_controller_alloc(struct device * parent, size_t size)
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
