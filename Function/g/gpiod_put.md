# Function: <code>gpiod_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583198640,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2409",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_put_array"
      ],
      "caller_func": [
        "drivers/gpio/devres.c:devm_gpiod_release",
        "drivers/clk/clk-gpio.c:clk_register_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583198640,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583506268,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3414",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/devres.c:devm_gpiod_release",
        "drivers/clk/clk-gpio.c:clk_register_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583505072,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583645820,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3535",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/devres.c:devm_gpiod_release",
        "drivers/clk/clk-gpio.c:clk_register_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583644992,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583684284,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3566",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/devres.c:devm_gpiod_release",
        "drivers/clk/clk-gpio.c:clk_register_gpio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583684240,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583939804,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3915",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/devres.c:devm_gpiod_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939760,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584128871,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4192",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/devres.c:devm_gpiod_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128832,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584213080,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4562",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584213040,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584401951,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4638",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584401888,
      "name": "gpiod_put",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584537615,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4903",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537552,
      "name": "gpiod_put",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585199585,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:5381",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_ena_gpio_free",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del",
        "drivers/nvmem/core.c:nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201696,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585357889,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4203",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_ena_gpio_free",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del",
        "drivers/nvmem/core.c:nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585357968,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585240993,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4182",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_ena_gpio_free",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del",
        "drivers/nvmem/core.c:nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585243568,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585696705,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4241",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_ena_gpio_free",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del",
        "drivers/nvmem/core.c:nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585699232,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586861969,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4365",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_ena_gpio_free",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del",
        "drivers/nvmem/core.c:nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586865712,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588009457,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4391",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_ena_gpio_free",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del",
        "drivers/nvmem/core.c:nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588011120,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588282993,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4430",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_ena_gpio_free",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del",
        "drivers/nvmem/core.c:nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588283088,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588576225,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4629",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_ena_gpio_free",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del",
        "drivers/nvmem/core.c:nvmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588577376,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496723464,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4903",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496723368,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230013960,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4903",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_ena_gpio_free",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230013876,
      "name": "gpiod_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290813612,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4903",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_ena_gpio_free",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290813504,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275481208,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4903",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_ena_gpio_free",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275481128,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584494543,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4903",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584494480,
      "name": "gpiod_put",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584432671,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4903",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584432608,
      "name": "gpiod_put",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584489279,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4903",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584489216,
      "name": "gpiod_put",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_put(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584595503,
      "name": "gpiod_put",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4903",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_release",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_register",
        "drivers/net/phy/fixed_phy.c:fixed_phy_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584595440,
      "name": "gpiod_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
