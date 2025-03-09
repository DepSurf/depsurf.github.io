# Function: <code>gpio_set_config_with_argument_optional</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpio_set_config_with_argument_optional(struct gpio_desc * desc, enum pin_config_param mode, u32 argument)
```

```json
{
  "name": "gpio_set_config_with_argument_optional",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585362165,
      "name": "gpio_set_config_with_argument_optional",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2137",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpio_set_debounce_timeout"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585354064,
      "name": "gpio_set_config_with_argument_optional",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int gpio_set_config_with_argument_optional(struct gpio_desc * desc, enum pin_config_param mode, u32 argument)
```

```json
{
  "name": "gpio_set_config_with_argument_optional",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585245717,
      "name": "gpio_set_config_with_argument_optional",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2114",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpio_set_debounce_timeout"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241072,
      "name": "gpio_set_config_with_argument_optional",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int gpio_set_config_with_argument_optional(struct gpio_desc * desc, enum pin_config_param mode, u32 argument)
```

```json
{
  "name": "gpio_set_config_with_argument_optional",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585701461,
      "name": "gpio_set_config_with_argument_optional",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2133",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpio_set_debounce_timeout"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585696784,
      "name": "gpio_set_config_with_argument_optional",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
  "name": "gpio_set_config_with_argument_optional",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586862110,
      "name": "gpio_set_config_with_argument_optional",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2194",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpio_set_debounce_timeout",
        "drivers/gpio/gpiolib.c:gpio_set_bias"
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
  "name": "gpio_set_config_with_argument_optional",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588009614,
      "name": "gpio_set_config_with_argument_optional",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2264",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpio_set_debounce_timeout",
        "drivers/gpio/gpiolib.c:gpio_set_bias"
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
  "name": "gpio_set_config_with_argument_optional",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588284350,
      "name": "gpio_set_config_with_argument_optional",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2305",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpio_set_debounce_timeout",
        "drivers/gpio/gpiolib.c:gpio_set_bias"
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
  "name": "gpio_set_config_with_argument_optional",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588585518,
      "name": "gpio_set_config_with_argument_optional",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2499",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpio_set_debounce_timeout",
        "drivers/gpio/gpiolib.c:gpio_set_bias"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int gpio_set_config_with_argument_optional(struct gpio_desc * desc, enum pin_config_param mode, u32 argument)
```
</details>
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
int gpio_set_config_with_argument_optional(struct gpio_desc * desc, enum pin_config_param mode, u32 argument)
```
</details>
</li>
</ul>
