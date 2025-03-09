# Function: <code>gpio_chip_get_multiple</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583940100,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2594",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
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
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584129228,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2752",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
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
int gpio_chip_get_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584206464,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2832",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584206464,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int gpio_chip_get_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584395184,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2920",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395184,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int gpio_chip_get_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584530832,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3278",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584530832,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int gpio_chip_get_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585192928,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3686",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585192928,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int gpio_chip_get_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585350752,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2512",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585350752,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int gpio_chip_get_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585234544,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2489",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585234544,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int gpio_chip_get_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585689840,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2518",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585689840,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int gpio_chip_get_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586861632,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2639",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586861632,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588017688,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2709",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588003616,
      "name": "gpio_chip_get_multiple.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int gpio_chip_get_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588277776,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2750",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588277776,
      "name": "gpio_chip_get_multiple",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588570896,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2943",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588570896,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int gpio_chip_get_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496706528,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3278",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496706528,
      "name": "gpio_chip_get_multiple",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230006140,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3278",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230006140,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int gpio_chip_get_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290802096,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3278",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290802096,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int gpio_chip_get_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275474812,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3278",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275474812,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int gpio_chip_get_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584487760,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3278",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584487760,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int gpio_chip_get_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584425888,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3278",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584425888,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int gpio_chip_get_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584482496,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3278",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584482496,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int gpio_chip_get_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
```

```json
{
  "name": "gpio_chip_get_multiple",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584588592,
      "name": "gpio_chip_get_multiple",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3278",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584588592,
      "name": "gpio_chip_get_multiple",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int gpio_chip_get_multiple(struct gpio_chip * chip, long unsigned int * mask, long unsigned int * bits)
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip * gc, long unsigned int * mask, long unsigned int * bits)
```
</details>
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
