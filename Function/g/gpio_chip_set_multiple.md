# Function: <code>gpio_chip_set_multiple</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583196950,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1419",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_priv"
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
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583506962,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2377",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
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
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583646514,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2567",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
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
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583684727,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2571",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
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
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583941287,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2824",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
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
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584130899,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3000",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpio_chip_set_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584206656,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3127",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584206656,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void gpio_chip_set_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584395376,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3215",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395376,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void gpio_chip_set_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584531024,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3569",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531024,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void gpio_chip_set_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585195568,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3978",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585195568,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void gpio_chip_set_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585353680,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2803",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585353680,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585248167,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2780",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585236368,
      "name": "gpio_chip_set_multiple.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585704142,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2820",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585691696,
      "name": "gpio_chip_set_multiple.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void gpio_chip_set_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586861360,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2941",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586861360,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588020459,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3011",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588007216,
      "name": "gpio_chip_set_multiple.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588294857,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3052",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588281840,
      "name": "gpio_chip_set_multiple.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588588678,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3245",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588574896,
      "name": "gpio_chip_set_multiple.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void gpio_chip_set_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496706808,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3569",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496706808,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void gpio_chip_set_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230006364,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3569",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230006364,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void gpio_chip_set_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290802512,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3569",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290802512,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void gpio_chip_set_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275475044,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3569",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275475044,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void gpio_chip_set_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584487952,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3569",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584487952,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void gpio_chip_set_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584426080,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3569",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584426080,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void gpio_chip_set_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584482688,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3569",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584482688,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void gpio_chip_set_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_set_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584588784,
      "name": "gpio_chip_set_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3569",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584588784,
      "name": "gpio_chip_set_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void gpio_chip_set_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip * gc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gpio_chip * chip</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void gpio_chip_set_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void gpio_chip_set_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void gpio_chip_set_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
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
