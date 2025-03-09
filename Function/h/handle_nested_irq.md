# Function: <code>handle_nested_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579753824,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:330",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_thread_fn",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/tps65912-irq.c:tps65912_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579753824,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579776672,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:330",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_thread_fn",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579776672,
      "name": "handle_nested_irq",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803440,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:329",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803440,
      "name": "handle_nested_irq",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801056,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:431",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801056,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579834736,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:454",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834736,
      "name": "handle_nested_irq",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867952,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:452",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867952,
      "name": "handle_nested_irq",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914992,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:452",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914992,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952704,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:458",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952704,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002560,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:458",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002560,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580051968,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:458",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580051968,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034560,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:458",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034560,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035936,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:461",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035936,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580168496,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:461",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580168496,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580314080,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:458",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580314080,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580527808,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:460",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580527808,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580600864,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:461",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580600864,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580665376,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:461",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_irq_handler",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580665376,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491197976,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:458",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/tc3589x.c:tc3589x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_thread",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491197976,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225218256,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:458",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/tc3589x.c:tc3589x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/tps65217.c:tps65217_irq_thread",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_thread",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225218256,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284100704,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:458",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/tc3589x.c:tc3589x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_thread",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284100704,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271740676,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:458",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq",
        "drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_irq",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/tc3589x.c:tc3589x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_thread",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271740676,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 438
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579971296,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:458",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971296,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579909120,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:458",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909120,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962832,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:458",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962832,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void handle_nested_irq(unsigned int irq)
```

```json
{
  "name": "handle_nested_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008816,
      "name": "handle_nested_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:458",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn",
        "drivers/base/regmap/regmap-irq.c:regmap_irq_thread",
        "drivers/mfd/88pm860x-core.c:pm860x_irq",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/arizona-irq.c:arizona_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm831x-irq.c:wm831x_irq_thread",
        "drivers/mfd/wm8350-irq.c:wm8350_irq",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_sih",
        "drivers/mfd/twl4030-irq.c:handle_twl4030_pih",
        "drivers/mfd/lp8788-irq.c:lp8788_irq_handler",
        "drivers/mfd/max8925-core.c:max8925_tsc_irq",
        "drivers/mfd/max8925-core.c:max8925_irq",
        "drivers/mfd/max8997-irq.c:max8997_irq_thread",
        "drivers/mfd/max8998-irq.c:max8998_irq_thread",
        "drivers/mfd/tps6586x.c:tps6586x_irq",
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008816,
      "name": "handle_nested_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
