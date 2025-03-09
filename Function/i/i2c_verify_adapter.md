# Function: <code>i2c_verify_adapter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585628096,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1334",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585628096,
      "name": "i2c_verify_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586028999,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1502",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:acpi_i2c_match_adapter"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586023520,
      "name": "i2c_verify_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586226055,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1638",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_acpi_match_adapter"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586220384,
      "name": "i2c_verify_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586309456,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1084",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_match_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586309456,
      "name": "i2c_verify_adapter",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586772976,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1101",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586772976,
      "name": "i2c_verify_adapter",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587045648,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1080",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587045648,
      "name": "i2c_verify_adapter",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587205744,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1092",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587205744,
      "name": "i2c_verify_adapter",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587471232,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1181",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587471232,
      "name": "i2c_verify_adapter",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587674352,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1186",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587674352,
      "name": "i2c_verify_adapter",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588541936,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1148",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588541936,
      "name": "i2c_verify_adapter",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588566944,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1276",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588566944,
      "name": "i2c_verify_adapter",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588450160,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1310",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588450160,
      "name": "i2c_verify_adapter",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589118144,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1311",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589118144,
      "name": "i2c_verify_adapter",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590566112,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1313",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590566112,
      "name": "i2c_verify_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592221216,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1307",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592221216,
      "name": "i2c_verify_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592649918,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1351",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_find_adapter_by_fwnode"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592645680,
      "name": "i2c_verify_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593395070,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1361",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_find_adapter_by_fwnode"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593390832,
      "name": "i2c_verify_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500832096,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1186",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle",
        "drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500832096,
      "name": "i2c_verify_adapter",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233349804,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1186",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233349804,
      "name": "i2c_verify_adapter",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294290144,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1186",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294290144,
      "name": "i2c_verify_adapter",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277638296,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1186",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-of.c:of_find_i2c_adapter_by_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277638296,
      "name": "i2c_verify_adapter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587625600,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1186",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587625600,
      "name": "i2c_verify_adapter",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```

```json
{
  "name": "i2c_verify_adapter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587736720,
      "name": "i2c_verify_adapter",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1186",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_adapter_by_handle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587736720,
      "name": "i2c_verify_adapter",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct i2c_adapter * i2c_verify_adapter(struct device * dev)
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
