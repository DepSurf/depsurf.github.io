# Function: <code>i2c_smbus_write_word_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585638992,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2729",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585638992,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586048056,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2934",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038192,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586245624,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:3222",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_acpi_space_handler"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586235632,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586329440,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:189",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586329440,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586793344,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:190",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586793344,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587066592,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:191",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587066592,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587226688,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:191",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587226688,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587493488,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:189",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587493488,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587696656,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:189",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587696656,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588565072,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:189",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588565072,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588589712,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:189",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588589712,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588473808,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:189",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588473808,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589142016,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:197",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589142016,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590593744,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:198",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590593744,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592252720,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:198",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592252720,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592677968,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:198",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592677968,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593423408,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:198",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593423408,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500857984,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:189",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500857984,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233373880,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:189",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233373880,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294324400,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:189",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294324400,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277659728,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:189",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277659728,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587647904,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:189",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647904,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```

```json
{
  "name": "i2c_smbus_write_word_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587759184,
      "name": "i2c_smbus_write_word_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:189",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_write_swapped",
        "drivers/base/regmap/regmap-i2c.c:regmap_smbus_word_reg_write",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587759184,
      "name": "i2c_smbus_write_word_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
s32 i2c_smbus_write_word_data(const struct i2c_client * client, u8 command, u16 value)
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
