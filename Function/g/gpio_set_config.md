# Function: <code>gpio_set_config</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584398531,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2597",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584534179,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2929",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpio_set_config(struct gpio_desc * desc, enum pin_config_param mode)
```

```json
{
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585206991,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3317",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585186992,
      "name": "gpio_set_config",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585360384,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2160",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585243944,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2137",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585699608,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2156",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586866039,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2217",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588013103,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2287",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588287607,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2328",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588580721,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2522",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496719172,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2929",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230010272,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2929",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290807904,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2929",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275478278,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2929",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584491107,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2929",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584429235,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2929",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584485843,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2929",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
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
  "name": "gpio_set_config",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584592067,
      "name": "gpio_set_config",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2929",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
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
int gpio_set_config(struct gpio_desc * desc, enum pin_config_param mode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int gpio_set_config(struct gpio_desc * desc, enum pin_config_param mode)
```
</details>
</li>
</ul>
