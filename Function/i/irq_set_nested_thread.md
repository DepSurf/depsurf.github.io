# Function: <code>irq_set_nested_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583189145,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584529624,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584592334,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584605070,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584625886,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584633709,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584638983,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/mfd/tps65912-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65912-irq.c:tps65912_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584647840,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584669214,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584676206,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584682174,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584684718,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584694126,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584701004,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:583",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583491561,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584877656,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584940558,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584953973,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584978398,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584986192,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584996730,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585017086,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585023966,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585029822,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585032286,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585041950,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585048712,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:612",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583630921,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585071256,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585123870,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585137605,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585161934,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585169703,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585180170,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585201070,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585207950,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585213806,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585216238,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585225774,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585232536,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:629",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583669561,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585153624,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585205150,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585219189,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585243342,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585251246,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585262423,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585283182,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585290014,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585295870,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585298222,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585307518,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585314184,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:679",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583924265,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585580600,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585633310,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585646869,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585671070,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585679006,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585690519,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585711454,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585718286,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585724110,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585726462,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585735838,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585742536,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:708",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584118242,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585824920,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585877038,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585891173,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585916958,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585924961,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585936381,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585957422,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585964318,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585970126,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585972478,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585981854,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585988632,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:710",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584201570,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585959144,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586013486,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586026917,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586053102,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586061217,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586072557,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586093870,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586100894,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586106750,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586109118,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586118590,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586125368,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:711",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584390823,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586201754,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586254930,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586270442,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586288370,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586296414,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586307706,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586329266,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586336258,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586342082,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344450,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586352978,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586360242,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:724",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584526407,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586350058,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586403154,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586418682,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586436578,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586444622,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586455882,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586477394,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586484402,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586490242,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586492626,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586501026,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586508210,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void irq_set_nested_thread(unsigned int irq, bool nest)
```

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585194537,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587120714,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587178146,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587194458,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587213170,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221486,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587233126,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq"
      ]
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587254866,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587262914,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587268306,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587270994,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587279474,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587288190,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:772",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587232080,
      "name": "irq_set_nested_thread",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void irq_set_nested_thread(unsigned int irq, bool nest)
```

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585352441,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587206314,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587261538,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587271554,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587287746,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587293806,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587303430,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq"
      ]
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587322690,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587328818,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587333666,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587336194,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587342834,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587349518,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:785",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587302384,
      "name": "irq_set_nested_thread",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void irq_set_nested_thread(unsigned int irq, bool nest)
```

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585236345,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587092266,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587149970,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587159842,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587175058,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587181214,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587190662,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq"
      ]
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587209730,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587215266,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587220066,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587222562,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587225874,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587231694,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:787",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587189616,
      "name": "irq_set_nested_thread",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void irq_set_nested_thread(unsigned int irq, bool nest)
```

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585691669,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:789",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587663946,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:789",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587726354,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:789",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587733906,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:789",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587742171,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:789",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587752214,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:789",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq"
      ]
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:789",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587772146,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:789",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587777874,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:789",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587783666,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:789",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587787122,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:789",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587790786,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:789",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587798726,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:789",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587751120,
      "name": "irq_set_nested_thread",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586859683,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:793",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589010552,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:793",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589070782,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:793",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589079342,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:793",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589088107,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:793",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589097016,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:793",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:793",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589118430,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:793",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589124686,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:793",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589130718,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:793",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589134526,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:793",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589138526,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:793",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589146997,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:793",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588005827,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:795",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590538232,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:795",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590603486,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:795",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590611790,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:795",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590623547,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:795",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590631927,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:795",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:795",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590657902,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:795",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590667374,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:795",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590674414,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:795",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590678750,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:795",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590683886,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:795",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590696291,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:795",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588280627,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:808",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590867256,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:808",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590943822,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:808",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590952894,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:808",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590964521,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:808",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590973063,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:808",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:808",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590998862,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:808",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591008318,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:808",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591015486,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:808",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591019822,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:808",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591024942,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:808",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591037395,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:808",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588573475,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:790",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591210760,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:790",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591287630,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:790",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591296702,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:790",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591308361,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:790",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591317031,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:790",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:790",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591342878,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:790",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591352302,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:790",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591359486,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:790",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591363870,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:790",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591368990,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:790",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591381811,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:790",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496703764,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499189000,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499251000,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499262692,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/stmpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/stmpe.c:stmpe_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499268588,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/tc3589x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc3589x.c:tc3589x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499280820,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499300512,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499308928,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499321460,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499323588,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499347708,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499358736,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499364788,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499367988,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499377784,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499388136,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230000900,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231721896,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231757076,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231779696,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/stmpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/stmpe.c:stmpe_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231784652,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/tc3589x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc3589x.c:tc3589x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231804328,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231845636,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231853468,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3231854400,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/tps65217.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65217.c:tps65217_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231868124,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3231870328,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231896084,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231907412,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231913272,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231916156,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231924652,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 3231940448,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290796352,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292395660,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292435332,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292449140,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/stmpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/stmpe.c:stmpe_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292456212,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/tc3589x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc3589x.c:tc3589x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292472208,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292515604,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292526500,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292541744,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292544904,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292574276,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292589316,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292597316,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292601556,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292613028,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292626472,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275470332,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276483338,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276511268,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276520640,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/stmpe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/stmpe.c:stmpe_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276525336,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/tc3589x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tc3589x.c:tc3589x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276535822,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276551142,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276558714,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276569126,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276570898,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6030-irq.c:twl6030_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276589624,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276598458,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276603832,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276606678,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276614714,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276623066,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584483335,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586111946,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586172250,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586189506,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584421463,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585957898,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585991530,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586008786,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584478071,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586298026,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586351122,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586366650,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586384546,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586392590,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586403850,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586425362,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586432370,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586438210,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586440594,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586448994,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586456178,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
  "name": "irq_set_nested_thread",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584584183,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_unmap",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586409482,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/base/regmap/regmap-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-irq.c:regmap_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586462802,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/88pm860x-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586478330,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/arizona-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/arizona-irq.c:arizona_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586496226,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm831x-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm831x-irq.c:wm831x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586504270,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/wm8350-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/wm8350-irq.c:wm8350_irq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586515530,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl4030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_init_irq",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup",
        "drivers/mfd/twl4030-irq.c:twl4030_sih_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586537042,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/lp8788-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/lp8788-irq.c:lp8788_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586544050,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8925-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8925-core.c:max8925_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586549890,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8997-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8997-irq.c:max8997_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586552274,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/max8998-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/max8998-irq.c:max8998_irq_domain_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586560674,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/tps6586x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps6586x.c:tps6586x_irq_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586567858,
      "name": "irq_set_nested_thread",
      "external": false,
      "loc": "include/linux/irq.h:742",
      "file": "drivers/mfd/rc5t583-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/rc5t583-irq.c:rc5t583_irq_init"
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void irq_set_nested_thread(unsigned int irq, bool nest)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void irq_set_nested_thread(unsigned int irq, bool nest)
```
</details>
</li>
</ul>
