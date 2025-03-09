# Function: <code>gpiochip_allocate_mask</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584125600,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:348",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125600,
      "name": "gpiochip_allocate_mask.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584209968,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:349",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209968,
      "name": "gpiochip_allocate_mask.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584398656,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:349",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584398656,
      "name": "gpiochip_allocate_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584529360,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:359",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584529360,
      "name": "gpiochip_allocate_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585189728,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:368",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189728,
      "name": "gpiochip_allocate_mask",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585348912,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:413",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585348912,
      "name": "gpiochip_allocate_mask",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585233104,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:411",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585233104,
      "name": "gpiochip_allocate_mask",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585688400,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:433",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585688400,
      "name": "gpiochip_allocate_mask",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586855392,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:434",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586855392,
      "name": "gpiochip_allocate_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588000384,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:435",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588000384,
      "name": "gpiochip_allocate_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588275072,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:454",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588275072,
      "name": "gpiochip_allocate_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * gc)
```

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588567712,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:533",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588567712,
      "name": "gpiochip_allocate_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496705328,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:359",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496705328,
      "name": "gpiochip_allocate_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229998120,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:359",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229998120,
      "name": "gpiochip_allocate_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
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
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290792224,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:359",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290792224,
      "name": "gpiochip_allocate_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * chip)
```

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275467818,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:359",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275467818,
      "name": "gpiochip_allocate_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584486288,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:359",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486288,
      "name": "gpiochip_allocate_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584424416,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:359",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584424416,
      "name": "gpiochip_allocate_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584481024,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:359",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584481024,
      "name": "gpiochip_allocate_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiochip_allocate_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584587120,
      "name": "gpiochip_allocate_mask",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:359",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584587120,
      "name": "gpiochip_allocate_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * gc)
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * chip)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * chip)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
long unsigned int * gpiochip_allocate_mask(struct gpio_chip * chip)
```
</details>
</li>
</ul>
