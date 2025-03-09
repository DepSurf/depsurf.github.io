# Function: <code>i2c_acpi_install_space_handler</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586242536,
      "name": "i2c_acpi_install_space_handler",
      "external": false,
      "loc": "drivers/i2c/i2c-core.c:607",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_register_adapter"
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586335664,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:610",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586335664,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586799744,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:610",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586799744,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587072992,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:624",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587072992,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587233152,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:650",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587233152,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:673",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587500579,
      "name": "i2c_acpi_install_space_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071587499904,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:702",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703708,
      "name": "i2c_acpi_install_space_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071587703008,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:694",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588572400,
      "name": "i2c_acpi_install_space_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071588571760,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:694",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591579292,
      "name": "i2c_acpi_install_space_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071588596176,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:690",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591522044,
      "name": "i2c_acpi_install_space_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071588480320,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:723",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592631286,
      "name": "i2c_acpi_install_space_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071589148704,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:739",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594514757,
      "name": "i2c_acpi_install_space_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071590600544,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592260160,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:759",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592260160,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592685488,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:748",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592685488,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593430992,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:748",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593430992,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500863360,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:702",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500863360,
      "name": "i2c_acpi_install_space_handler",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_install_space_handler",
      "external": false,
      "loc": "drivers/i2c/i2c-core.h:88",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_install_space_handler",
      "external": false,
      "loc": "drivers/i2c/i2c-core.h:88",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_install_space_handler",
      "external": false,
      "loc": "drivers/i2c/i2c-core.h:88",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:702",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587654956,
      "name": "i2c_acpi_install_space_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071587654256,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```

```json
{
  "name": "i2c_acpi_install_space_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_install_space_handler",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:702",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587766236,
      "name": "i2c_acpi_install_space_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071587765536,
      "name": "i2c_acpi_install_space_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter * adapter)
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
