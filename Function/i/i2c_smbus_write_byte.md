# Function: <code>i2c_smbus_write_byte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585638608,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2653",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585638608,
      "name": "i2c_smbus_write_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586048084,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2858",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586037808,
      "name": "i2c_smbus_write_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586245652,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:3146",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_acpi_space_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235248,
      "name": "i2c_smbus_write_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586329072,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:113",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586329072,
      "name": "i2c_smbus_write_byte",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586792976,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:114",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586792976,
      "name": "i2c_smbus_write_byte",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587066224,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:115",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587066224,
      "name": "i2c_smbus_write_byte",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587226320,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:115",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587226320,
      "name": "i2c_smbus_write_byte",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587493120,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:113",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587493120,
      "name": "i2c_smbus_write_byte",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587696288,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:113",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587696288,
      "name": "i2c_smbus_write_byte",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588564704,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:113",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588564704,
      "name": "i2c_smbus_write_byte",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588589344,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:113",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588589344,
      "name": "i2c_smbus_write_byte",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588473440,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:113",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588473440,
      "name": "i2c_smbus_write_byte",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589141648,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:121",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589141648,
      "name": "i2c_smbus_write_byte",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590593200,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:122",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590593200,
      "name": "i2c_smbus_write_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592252112,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:122",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592252112,
      "name": "i2c_smbus_write_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592677360,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:122",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592677360,
      "name": "i2c_smbus_write_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593422800,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:122",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593422800,
      "name": "i2c_smbus_write_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500857536,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:113",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500857536,
      "name": "i2c_smbus_write_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233373428,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:113",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233373428,
      "name": "i2c_smbus_write_byte",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294323968,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:113",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294323968,
      "name": "i2c_smbus_write_byte",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277659440,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:113",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277659440,
      "name": "i2c_smbus_write_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587647536,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:113",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647536,
      "name": "i2c_smbus_write_byte",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```

```json
{
  "name": "i2c_smbus_write_byte",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587758816,
      "name": "i2c_smbus_write_byte",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:113",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587758816,
      "name": "i2c_smbus_write_byte",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
s32 i2c_smbus_write_byte(const struct i2c_client * client, u8 value)
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
