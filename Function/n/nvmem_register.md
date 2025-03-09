# Function: <code>nvmem_register</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586864704,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:444",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/nvmem.c:rtc_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586864704,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587352528,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:444",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/nvmem.c:rtc_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587352528,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1181
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587657333,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:454",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587656256,
      "name": "nvmem_register.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
    },
    {
      "addr": 18446744071587657232,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587788581,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:603",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587786880,
      "name": "nvmem_register.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1586
    },
    {
      "addr": 18446744071587788480,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588091805,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:356",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588090464,
      "name": "nvmem_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
    },
    {
      "addr": 18446744071588091712,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588297629,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:353",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296288,
      "name": "nvmem_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
    },
    {
      "addr": 18446744071588297536,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:578",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589181584,
      "name": "nvmem_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071589179312,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1220
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:739",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591625258,
      "name": "nvmem_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589176816,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1287
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:742",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591568440,
      "name": "nvmem_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071589068832,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1714
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:748",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592691163,
      "name": "nvmem_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    },
    {
      "addr": 18446744071589787504,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1868
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:752",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594576381,
      "name": "nvmem_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
    },
    {
      "addr": 18446744071591299936,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1947
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:752",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596320994,
      "name": "nvmem_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071593051152,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1971
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:879",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596850718,
      "name": "nvmem_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071593503392,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2067
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:890",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597775641,
      "name": "nvmem_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071594253040,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2085
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501821880,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:353",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501820128,
      "name": "nvmem_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1612
    },
    {
      "addr": 18446603336501821744,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234339664,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:353",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ],
      "caller_func": [
        "drivers/mtd/mtdcore.c:add_mtd_device",
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234337872,
      "name": "nvmem_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1684
    },
    {
      "addr": 3234339556,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295220596,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:353",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295218000,
      "name": "nvmem_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2456
    },
    {
      "addr": 13835058055295220464,
      "name": "nvmem_register",
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278168176,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:353",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278166492,
      "name": "nvmem_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1578
    },
    {
      "addr": 18446743936278168070,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587901389,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:353",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587900048,
      "name": "nvmem_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
    },
    {
      "addr": 18446744071587901296,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587620669,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:353",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587619328,
      "name": "nvmem_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
    },
    {
      "addr": 18446744071587620576,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588234685,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:353",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588233344,
      "name": "nvmem_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
    },
    {
      "addr": 18446744071588234592,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```

```json
{
  "name": "nvmem_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588370013,
      "name": "nvmem_register",
      "external": true,
      "loc": "drivers/nvmem/core.c:353",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368672,
      "name": "nvmem_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
    },
    {
      "addr": 18446744071588369920,
      "name": "nvmem_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
struct nvmem_device * nvmem_register(const struct nvmem_config * config)
```
</details>
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
