# Function: <code>i2c_master_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int i2c_master_send(const struct i2c_client * client, const char * buf, int count)
```

```json
{
  "name": "i2c_master_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585635744,
      "name": "i2c_master_send",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2284",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_write",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/i2c/i2c-dev.c:i2cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585635744,
      "name": "i2c_master_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int i2c_master_send(const struct i2c_client * client, const char * buf, int count)
```

```json
{
  "name": "i2c_master_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586035008,
      "name": "i2c_master_send",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2489",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/i2c/i2c-dev.c:i2cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586035008,
      "name": "i2c_master_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int i2c_master_send(const struct i2c_client * client, const char * buf, int count)
```

```json
{
  "name": "i2c_master_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586232448,
      "name": "i2c_master_send",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2776",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send",
        "drivers/i2c/i2c-dev.c:i2cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586232448,
      "name": "i2c_master_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int i2c_master_send(const struct i2c_client * client, const char * buf, int count)
```

```json
{
  "name": "i2c_master_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586318576,
      "name": "i2c_master_send",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1962",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send",
        "drivers/i2c/i2c-dev.c:i2cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586318576,
      "name": "i2c_master_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int i2c_master_send(const struct i2c_client * client, const char * buf, int count)
```

```json
{
  "name": "i2c_master_send",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586782272,
      "name": "i2c_master_send",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1986",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send",
        "drivers/i2c/i2c-dev.c:i2cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586782272,
      "name": "i2c_master_send",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585819093,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585925814,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585967501,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585977371,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585982502,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587002053,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587074438,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585953045,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586062070,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586103741,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586114014,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586119238,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587163493,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587234598,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:108",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586195381,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586297238,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586339099,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586349028,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586354554,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587428757,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587501701,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586343685,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586445414,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586487259,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586497171,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586502586,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587631813,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587704837,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587115061,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587222278,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587265449,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587275477,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ab3100-core.c:ab3100_setup",
        "drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:set_register_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587281338,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588502108,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588573573,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587200163,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587294502,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587331049,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591512501,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ab3100-core.c:ab3100_setup",
        "drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:set_register_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587343610,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588530956,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588597653,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:102",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587087475,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:105",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587181910,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:105",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587217488,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:105",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587226682,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:105",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588412732,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:105",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588481796,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:105",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587659219,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:106",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587742838,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:106",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587780096,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:106",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587792388,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:106",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589081310,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:106",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589150161,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:106",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589004803,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589088832,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589127088,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589140250,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590524266,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590602241,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590527955,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590624853,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590670368,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590687018,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592173271,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592261969,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590855923,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590965877,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591011312,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591028090,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592596839,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592687425,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591199555,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591309717,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591355296,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591372506,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593341543,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593432977,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:107",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499182652,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499309796,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499361552,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499372800,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499379800,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500867352,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229797716,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/phy/samsung/phy-exynos5250-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3231716608,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3231856232,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231910360,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3231921080,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 3231932664,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3233378896,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292015768,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/char/tpm/tpm_i2c_atmel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_send"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292388160,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292527596,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292593680,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292608068,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292615664,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294330312,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276477756,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276559438,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276600986,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276611178,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276616266,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277663124,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
      ],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586291653,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586393382,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586435227,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586445139,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586450554,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587583061,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587656085,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_master_send",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586403109,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/base/regmap/regmap-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586505062,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/tps65910.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586546907,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/max8925-i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586556819,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/ab3100-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586562234,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/mfd/aat2870-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587693957,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/input/touchscreen/elants_i2c.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587767557,
      "name": "i2c_master_send",
      "external": false,
      "loc": "include/linux/i2c.h:94",
      "file": "drivers/i2c/i2c-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-dev.c:i2cdev_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int i2c_master_send(const struct i2c_client * client, const char * buf, int count)
```
</details>
</li>
</ul>
