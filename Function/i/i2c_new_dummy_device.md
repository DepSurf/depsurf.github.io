# Function: <code>i2c_new_dummy_device</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587484960,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:891",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_secondary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587484960,
      "name": "i2c_new_dummy_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587688224,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:896",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
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
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587688224,
      "name": "i2c_new_dummy_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588556889,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:881",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/max14577.c:max77836_init",
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
      "addr": 18446744071588553744,
      "name": "i2c_new_dummy_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588582457,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1009",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
        "drivers/mfd/twl-core.c:twl_probe",
        "drivers/mfd/max14577.c:max77836_init",
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
      "addr": 18446744071588579200,
      "name": "i2c_new_dummy_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588465977,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1053",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
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
        "drivers/mfd/max8998.c:max8998_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588462848,
      "name": "i2c_new_dummy_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589134086,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1054",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
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
        "drivers/mfd/max8998.c:max8998_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130944,
      "name": "i2c_new_dummy_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590583782,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1056",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
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
        "drivers/mfd/max8998.c:max8998_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590580336,
      "name": "i2c_new_dummy_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592241686,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1050",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
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
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592237680,
      "name": "i2c_new_dummy_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592666822,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1094",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
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
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592662784,
      "name": "i2c_new_dummy_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593412214,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1102",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
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
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593408064,
      "name": "i2c_new_dummy_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500849424,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:896",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy"
      ],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
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
        "drivers/mfd/palmas.c:palmas_i2c_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500848800,
      "name": "i2c_new_dummy_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233365852,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:896",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
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
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233365852,
      "name": "i2c_new_dummy_device",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294313072,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:896",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
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
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294313072,
      "name": "i2c_new_dummy_device",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277652830,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:896",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
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
        "drivers/mfd/palmas.c:palmas_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277652830,
      "name": "i2c_new_dummy_device",
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
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639472,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:896",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
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
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639472,
      "name": "i2c_new_dummy_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```

```json
{
  "name": "i2c_new_dummy_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587750672,
      "name": "i2c_new_dummy_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:896",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm860x_probe",
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
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587750672,
      "name": "i2c_new_dummy_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```
</details>
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
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct i2c_client * i2c_new_dummy_device(struct i2c_adapter * adapter, u16 address)
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
