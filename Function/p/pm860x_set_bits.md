# Function: <code>pm860x_set_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584592608,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:73",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584592608,
      "name": "pm860x_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584940832,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:73",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584940832,
      "name": "pm860x_set_bits",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585124144,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:73",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124144,
      "name": "pm860x_set_bits",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585205424,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:73",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585205424,
      "name": "pm860x_set_bits",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585633584,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:73",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585633584,
      "name": "pm860x_set_bits",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585878016,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:73",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_osc_init",
        "drivers/mfd/88pm860x-core.c:device_osc_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585878016,
      "name": "pm860x_set_bits",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586013792,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:73",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586013792,
      "name": "pm860x_set_bits",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586257456,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586257456,
      "name": "pm860x_set_bits",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586405680,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586405680,
      "name": "pm860x_set_bits",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587181360,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:device_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587181360,
      "name": "pm860x_set_bits",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587262352,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:device_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587262352,
      "name": "pm860x_set_bits",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587150784,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:device_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587150784,
      "name": "pm860x_set_bits",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587727168,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:device_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587727168,
      "name": "pm860x_set_bits",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589071648,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:device_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589071648,
      "name": "pm860x_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590604608,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:device_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590604608,
      "name": "pm860x_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590945728,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:device_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590945728,
      "name": "pm860x_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591289536,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:device_irq_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591289536,
      "name": "pm860x_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499254600,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499254600,
      "name": "pm860x_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231760236,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231760236,
      "name": "pm860x_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292439584,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292439584,
      "name": "pm860x_set_bits",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276514178,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276514178,
      "name": "pm860x_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586353648,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586353648,
      "name": "pm860x_set_bits",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```

```json
{
  "name": "pm860x_set_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586465328,
      "name": "pm860x_set_bits",
      "external": true,
      "loc": "drivers/mfd/88pm860x-i2c.c:70",
      "file": "drivers/mfd/88pm860x-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8606_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:device_8607_init",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_disable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable",
        "drivers/mfd/88pm860x-core.c:pm8606_osc_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586465328,
      "name": "pm860x_set_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int pm860x_set_bits(struct i2c_client * i2c, int reg, unsigned char mask, unsigned char data)
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
