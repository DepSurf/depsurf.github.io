# Function: <code>mmc_rca_show</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587453488,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:795",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587473088,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:671",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587453488,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587473088,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587633728,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:795",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587653168,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:671",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587633728,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587653168,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587911712,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:792",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587931248,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:691",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587911712,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587931248,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588117600,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:792",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588137152,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:691",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588117600,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588137152,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588981296,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:796",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589001232,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:691",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589011712,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:33",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588981296,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589001232,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589011712,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588992464,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:803",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589010448,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:691",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589020880,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:34",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588992464,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589010448,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589020880,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588879232,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:803",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588897856,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:697",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588907872,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:34",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588879232,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588897856,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588907872,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589581728,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:806",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589602064,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:707",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589614208,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:34",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589581728,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589602064,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071589614208,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591077200,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:814",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591099056,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:716",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591112592,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:35",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591077200,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071591099056,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071591112592,
      "name": "mmc_rca_show",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592793552,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:814",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592818224,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:716",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592834096,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:35",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592793552,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071592818224,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071592834096,
      "name": "mmc_rca_show",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593230128,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:814",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593254896,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:716",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593270704,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:35",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593230128,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071593254896,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071593270704,
      "name": "mmc_rca_show",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593984848,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:821",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594010304,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:716",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594026608,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:35",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593984848,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071594010304,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071594026608,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501371016,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:792",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501389808,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:691",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501371016,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336501389808,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233860740,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:792",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3233879092,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:691",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233860740,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3233879092,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294927104,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:792",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294950816,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:691",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294927104,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055294950816,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277981682,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:792",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277998214,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:691",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277981682,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446743936277998214,
      "name": "mmc_rca_show",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587739168,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:792",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587758720,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:691",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587739168,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587758720,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588072128,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:792",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588091680,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:691",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588072128,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588091680,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "mmc_rca_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588189664,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/mmc.c:792",
      "file": "drivers/mmc/core/mmc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588209216,
      "name": "mmc_rca_show",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:691",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588189664,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071588209216,
      "name": "mmc_rca_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
ssize_t mmc_rca_show(struct device * dev, struct device_attribute * attr, char * buf)
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
