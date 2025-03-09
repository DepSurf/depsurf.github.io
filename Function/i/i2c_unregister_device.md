# Function: <code>i2c_unregister_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585632048,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1100",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:__unregister_dummy",
        "drivers/i2c/i2c-core.c:__unregister_client",
        "drivers/i2c/i2c-core.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core.c:i2c_sysfs_delete_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_remove",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_remove",
        "drivers/mfd/max8997.c:max8997_i2c_remove",
        "drivers/mfd/max8997.c:max8997_i2c_remove",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_remove",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_remove",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585632048,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586030128,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1225",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_remove",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core.c:__unregister_dummy",
        "drivers/i2c/i2c-core.c:__unregister_client",
        "drivers/i2c/i2c-core.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core.c:i2c_sysfs_delete_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586030128,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586228224,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1363",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core.c:__unregister_dummy",
        "drivers/i2c/i2c-core.c:__unregister_client",
        "drivers/i2c/i2c-core.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core.c:i2c_sysfs_delete_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586228224,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586312224,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:809",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586312224,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586779413,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:820",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586778672,
      "name": "i2c_unregister_device.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071586778768,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587052415,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:799",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587051632,
      "name": "i2c_unregister_device.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071587051728,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587211999,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:811",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/mfd/tps80031.c:tps80031_remove",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587211696,
      "name": "i2c_unregister_device.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071587211792,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587477391,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:833",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587477200,
      "name": "i2c_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071587477296,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587680543,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:838",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587680352,
      "name": "i2c_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071587680448,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588549889,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:823",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max77836_init",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:delete_device_store",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588547184,
      "name": "i2c_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071588547280,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588575441,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:951",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max77836_init",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:delete_device_store",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588572736,
      "name": "i2c_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071588572832,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588458977,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:994",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:delete_device_store",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588456256,
      "name": "i2c_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071588456368,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589127091,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:995",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:delete_device_store",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589124320,
      "name": "i2c_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071589124432,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590570672,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:997",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:delete_device_store",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590570672,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592224592,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:998",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:delete_device_store",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592224592,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592649072,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1013",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:delete_device_store",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592649072,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593394224,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1021",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/gpu/drm/drm_encoder_slave.c:drm_i2c_encoder_destroy",
        "drivers/gpu/drm/drm_encoder_slave.c:drm_i2c_encoder_init",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:delete_device_store",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593394224,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500839356,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:838",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500839040,
      "name": "i2c_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446603336500839200,
      "name": "i2c_unregister_device",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233356252,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:838",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233356052,
      "name": "i2c_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 3233356120,
      "name": "i2c_unregister_device",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294300932,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:838",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294300672,
      "name": "i2c_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 13835058055294300800,
      "name": "i2c_unregister_device",
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277644708,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:838",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277644496,
      "name": "i2c_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446743936277644568,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587631791,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:838",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587631600,
      "name": "i2c_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071587631696,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void i2c_unregister_device(struct i2c_client * client)
```

```json
{
  "name": "i2c_unregister_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587742911,
      "name": "i2c_unregister_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:838",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_remove",
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/mfd/twl-core.c:twl_remove",
        "drivers/mfd/max14577.c:max14577_i2c_remove",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_remove",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_remove",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/mfd/palmas.c:palmas_i2c_remove",
        "drivers/i2c/i2c-core-base.c:__unregister_dummy",
        "drivers/i2c/i2c-core-base.c:i2c_do_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_delete_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_release_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587742720,
      "name": "i2c_unregister_device.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071587742816,
      "name": "i2c_unregister_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void i2c_unregister_device(struct i2c_client * client)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void i2c_unregister_device(struct i2c_client * client)
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
