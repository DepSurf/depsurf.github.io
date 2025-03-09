# Function: <code>i2c_client_get_device_id</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
const struct i2c_device_id * i2c_client_get_device_id(const struct i2c_client * client)
```

```json
{
  "name": "i2c_client_get_device_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592232928,
      "name": "i2c_client_get_device_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2245",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/adp5520.c:adp5520_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592232928,
      "name": "i2c_client_get_device_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
const struct i2c_device_id * i2c_client_get_device_id(const struct i2c_client * client)
```

```json
{
  "name": "i2c_client_get_device_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592658784,
      "name": "i2c_client_get_device_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2358",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe",
        "drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe",
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/adp5520.c:adp5520_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592658784,
      "name": "i2c_client_get_device_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
const struct i2c_device_id * i2c_client_get_device_id(const struct i2c_client * client)
```

```json
{
  "name": "i2c_client_get_device_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593403952,
      "name": "i2c_client_get_device_id",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2376",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/tps65910.c:tps65910_i2c_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/da903x.c:da903x_probe",
        "drivers/mfd/da9052-i2c.c:da9052_i2c_probe",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/adp5520.c:adp5520_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593403952,
      "name": "i2c_client_get_device_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
const struct i2c_device_id * i2c_client_get_device_id(const struct i2c_client * client)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
