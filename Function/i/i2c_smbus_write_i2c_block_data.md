# Function: <code>i2c_smbus_write_i2c_block_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585640160,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2818",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585640160,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586039376,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:3023",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039376,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586236816,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:3311",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586236816,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586330656,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:278",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586330656,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586794576,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:279",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586794576,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587067808,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:280",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587067808,
      "name": "i2c_smbus_write_i2c_block_data",
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587227904,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:280",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587227904,
      "name": "i2c_smbus_write_i2c_block_data",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587494640,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:278",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587494640,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587697808,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:278",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587697808,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588565872,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:278",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588565872,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588590512,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:278",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588590512,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588474608,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:278",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588474608,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589142816,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:286",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589142816,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590594768,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:287",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590594768,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592253840,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:287",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592253840,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592679088,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:287",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592679088,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593424528,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:287",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write_reg16",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593424528,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500859024,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:278",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/stmpe-i2c.c:i2c_block_write",
        "drivers/mfd/tc3589x.c:tc3589x_block_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500859024,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233374816,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:278",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/stmpe-i2c.c:i2c_block_write",
        "drivers/mfd/tc3589x.c:tc3589x_block_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233374816,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294325712,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:278",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_write_buf",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/stmpe-i2c.c:i2c_block_write",
        "drivers/mfd/tc3589x.c:tc3589x_block_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294325712,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277660430,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:278",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/stmpe-i2c.c:i2c_block_write",
        "drivers/mfd/tc3589x.c:tc3589x_block_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277660430,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587649056,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:278",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587649056,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```

```json
{
  "name": "i2c_smbus_write_i2c_block_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587760336,
      "name": "i2c_smbus_write_i2c_block_data",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:278",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_write",
        "drivers/mfd/da903x.c:da9034_mask_events",
        "drivers/mfd/da903x.c:da9034_unmask_events",
        "drivers/mfd/da903x.c:da9030_mask_events",
        "drivers/mfd/da903x.c:da9030_unmask_events",
        "drivers/mfd/da903x.c:da903x_writes",
        "drivers/mfd/max8997.c:max8997_bulk_write",
        "drivers/mfd/max8998.c:max8998_bulk_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587760336,
      "name": "i2c_smbus_write_i2c_block_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
s32 i2c_smbus_write_i2c_block_data(const struct i2c_client * client, u8 command, u8 length, const u8 * values)
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
