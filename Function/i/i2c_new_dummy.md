# Function: <code>i2c_new_dummy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585646544,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1150",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585646544,
      "name": "i2c_new_dummy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043056,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1277",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/i2c/i2c-core.c:i2c_new_secondary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043056,
      "name": "i2c_new_dummy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586240560,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1415",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/i2c/i2c-core.c:i2c_new_secondary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586240560,
      "name": "i2c_new_dummy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586319776,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:861",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_secondary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586319776,
      "name": "i2c_new_dummy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586783520,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:878",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_secondary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586783520,
      "name": "i2c_new_dummy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587056432,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:857",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_secondary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587056432,
      "name": "i2c_new_dummy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587216512,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:869",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_secondary_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587216512,
      "name": "i2c_new_dummy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587485144,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:915",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_secondary_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/tps80031.c:tps80031_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/max14577.c:max14577_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77693.c:max77693_i2c_probe",
        "drivers/mfd/max77843.c:max77843_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8925-i2c.c:max8925_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8997.c:max8997_i2c_probe",
        "drivers/mfd/max8998.c:max8998_i2c_probe",
        "drivers/mfd/ab3100-core.c:ab3100_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587485072,
      "name": "i2c_new_dummy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587688336,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:920",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587688336,
      "name": "i2c_new_dummy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500848936,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:920",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500848936,
      "name": "i2c_new_dummy",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233366012,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:920",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233366012,
      "name": "i2c_new_dummy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294313248,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:920",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294313248,
      "name": "i2c_new_dummy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277652962,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:920",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277652962,
      "name": "i2c_new_dummy",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639584,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:920",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639584,
      "name": "i2c_new_dummy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587750784,
      "name": "i2c_new_dummy",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:920",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587750784,
      "name": "i2c_new_dummy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```
</details>
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
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct i2c_client * i2c_new_dummy(struct i2c_adapter * adapter, u16 address)
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
