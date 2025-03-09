# Function: <code>i2c_match_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585631172,
      "name": "i2c_match_id",
      "external": false,
      "loc": "drivers/i2c/i2c-core.c:491",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/i2c/i2c-core.c:i2c_device_match"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586029366,
      "name": "i2c_match_id",
      "external": false,
      "loc": "drivers/i2c/i2c-core.c:589",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/i2c/i2c-core.c:i2c_device_match"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586226208,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:683",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core.c:i2c_device_probe",
        "drivers/i2c/i2c-core.c:i2c_device_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586226208,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586314517,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:83",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586314352,
      "name": "i2c_match_id.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071586314432,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586777205,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:84",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586777040,
      "name": "i2c_match_id.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071586777120,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587050899,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:86",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587050432,
      "name": "i2c_match_id.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071587050512,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587211096,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:86",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587210640,
      "name": "i2c_match_id.part.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071587210720,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587476653,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:78",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587476160,
      "name": "i2c_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071587476240,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587679805,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:78",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587679312,
      "name": "i2c_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071587679392,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588550855,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:78",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588546832,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588576405,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:79",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588572384,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588460064,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:101",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588455904,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589128189,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:101",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589123968,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590577398,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:101",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590574432,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592232954,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:101",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_client_get_device_id",
        "drivers/i2c/i2c-core-base.c:i2c_client_get_device_id",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592230528,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592658810,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:102",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_client_get_device_id",
        "drivers/i2c/i2c-core-base.c:i2c_client_get_device_id",
        "drivers/i2c/i2c-core-base.c:i2c_device_match",
        "drivers/i2c/i2c-core-base.c:i2c_device_match",
        "drivers/i2c/i2c-core-base.c:i2c_get_match_data",
        "drivers/i2c/i2c-core-base.c:i2c_get_match_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592654896,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593403978,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:105",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_client_get_device_id",
        "drivers/i2c/i2c-core-base.c:i2c_client_get_device_id",
        "drivers/i2c/i2c-core-base.c:i2c_device_match",
        "drivers/i2c/i2c-core-base.c:i2c_device_match",
        "drivers/i2c/i2c-core-base.c:i2c_get_match_data",
        "drivers/i2c/i2c-core-base.c:i2c_get_match_data"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593400048,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500837528,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:78",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500836640,
      "name": "i2c_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446603336500836744,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233355740,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:78",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233354856,
      "name": "i2c_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 3233354944,
      "name": "i2c_match_id",
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
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294299808,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:78",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294298496,
      "name": "i2c_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    },
    {
      "addr": 13835058055294299024,
      "name": "i2c_match_id",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277644126,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:78",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277643272,
      "name": "i2c_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446743936277643362,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587631053,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:78",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587630560,
      "name": "i2c_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071587630640,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```

```json
{
  "name": "i2c_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587742173,
      "name": "i2c_match_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:78",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_device_probe",
        "drivers/i2c/i2c-core-base.c:i2c_device_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587741680,
      "name": "i2c_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071587741760,
      "name": "i2c_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
const struct i2c_device_id * i2c_match_id(const struct i2c_device_id * id, const struct i2c_client * client)
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
