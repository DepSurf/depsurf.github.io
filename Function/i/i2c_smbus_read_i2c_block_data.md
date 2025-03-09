# Function: <code>i2c_smbus_read_i2c_block_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585639600,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2798",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585639600,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586038784,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:3003",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038784,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586236224,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:3291",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586236224,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586330048,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:258",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586330048,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586793952,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:259",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586793952,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:260",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587069031,
      "name": "i2c_smbus_read_i2c_block_data.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587067184,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:260",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587229127,
      "name": "i2c_smbus_read_i2c_block_data.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587227280,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:258",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587495989,
      "name": "i2c_smbus_read_i2c_block_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587494048,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:258",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587699156,
      "name": "i2c_smbus_read_i2c_block_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587697216,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:258",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588567741,
      "name": "i2c_smbus_read_i2c_block_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588565632,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:258",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591579023,
      "name": "i2c_smbus_read_i2c_block_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588590272,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:258",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591521848,
      "name": "i2c_smbus_read_i2c_block_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071588474368,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:266",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592631090,
      "name": "i2c_smbus_read_i2c_block_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071589142576,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:267",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594514574,
      "name": "i2c_smbus_read_i2c_block_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071590594480,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592253520,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:267",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592253520,
      "name": "i2c_smbus_read_i2c_block_data",
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592678768,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:267",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592678768,
      "name": "i2c_smbus_read_i2c_block_data",
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593424208,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:267",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593424208,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500858448,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:258",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/stmpe-i2c.c:i2c_block_read",
        "drivers/mfd/tc3589x.c:tc3589x_block_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500858448,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233374328,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:258",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/stmpe-i2c.c:i2c_block_read",
        "drivers/mfd/tc3589x.c:tc3589x_block_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233374328,
      "name": "i2c_smbus_read_i2c_block_data",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294324912,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:258",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_read_buf",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/stmpe-i2c.c:i2c_block_read",
        "drivers/mfd/tc3589x.c:tc3589x_block_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294324912,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277660016,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:258",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/stmpe-i2c.c:i2c_block_read",
        "drivers/mfd/tc3589x.c:tc3589x_block_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277660016,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:258",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587650404,
      "name": "i2c_smbus_read_i2c_block_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587648464,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```

```json
{
  "name": "i2c_smbus_read_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_smbus_read_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:258",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read",
        "drivers/mfd/da903x.c:da9034_read_status",
        "drivers/mfd/da903x.c:da9034_read_events",
        "drivers/mfd/da903x.c:da9030_read_events",
        "drivers/mfd/da903x.c:da903x_reads",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_read",
        "drivers/mfd/max8997.c:max8997_bulk_read",
        "drivers/mfd/max8998.c:max8998_bulk_read",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587761684,
      "name": "i2c_smbus_read_i2c_block_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587759744,
      "name": "i2c_smbus_read_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
s32 i2c_smbus_read_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, u8 * values)
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
