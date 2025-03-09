# Function: <code>i2c_transfer_buffer_flags</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587055168,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1971",
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
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587055168,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587215296,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1971",
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
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587215296,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587481024,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2064",
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
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587481024,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587684288,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2069",
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
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587684288,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588552816,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1999",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/ab3100-core.c:ab3100_setup",
        "drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588552816,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588578240,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2129",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/ab3100-core.c:ab3100_setup",
        "drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588578240,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588461856,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2189",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588461856,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589129952,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2190",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589129952,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590579280,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2193",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590579280,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592236448,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2187",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592236448,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592661552,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2300",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592661552,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593406752,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2318",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593406752,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500844752,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2069",
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
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500844752,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233360236,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2069",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_init",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233360236,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294306336,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2069",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_read_status",
        "drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_recv",
        "drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_send",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_write",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/max8925-i2c.c:max8925_set_bits",
        "drivers/mfd/max8925-i2c.c:max8925_bulk_write",
        "drivers/mfd/max8925-i2c.c:max8925_reg_write",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294306336,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277648154,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2069",
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
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277648154,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587635536,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2069",
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
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587635536,
      "name": "i2c_transfer_buffer_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```

```json
{
  "name": "i2c_transfer_buffer_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587746736,
      "name": "i2c_transfer_buffer_flags",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2069",
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
        "drivers/mfd/ab3100-core.c:mask_and_set_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_page_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_get_register_interruptible",
        "drivers/mfd/ab3100-core.c:ab3100_set_register_interruptible",
        "drivers/mfd/aat2870-core.c:__aat2870_write",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/mfd/aat2870-core.c:__aat2870_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_read",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_send",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/i2c/i2c-dev.c:i2cdev_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587746736,
      "name": "i2c_transfer_buffer_flags",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```
</details>
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
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int i2c_transfer_buffer_flags(const struct i2c_client * client, char * buf, int count, u16 flags)
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
