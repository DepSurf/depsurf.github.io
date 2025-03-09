# Function: <code>gpiod_get_from_of_node</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct gpio_desc * gpiod_get_from_of_node(struct device_node * node, const char * propname, int index, enum gpiod_flags dflags, const char * label)
```

```json
{
  "name": "gpiod_get_from_of_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584113984,
      "name": "gpiod_get_from_of_node",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3906",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/devres.c:devm_gpiod_get_from_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584113984,
      "name": "gpiod_get_from_of_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
struct gpio_desc * gpiod_get_from_of_node(struct device_node * node, const char * propname, int index, enum gpiod_flags dflags, const char * label)
```

```json
{
  "name": "gpiod_get_from_of_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584197440,
      "name": "gpiod_get_from_of_node",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4181",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197440,
      "name": "gpiod_get_from_of_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
struct gpio_desc * gpiod_get_from_of_node(struct device_node * node, const char * propname, int index, enum gpiod_flags dflags, const char * label)
```

```json
{
  "name": "gpiod_get_from_of_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584385840,
      "name": "gpiod_get_from_of_node",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4279",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584385840,
      "name": "gpiod_get_from_of_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
  "name": "gpiod_get_from_of_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:577",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:577",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiod_get_from_of_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:622",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:622",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpiod_get_from_of_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:622",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:622",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "gpiod_get_from_of_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:622",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:622",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "gpiod_get_from_of_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:622",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:622",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "gpiod_get_from_of_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:631",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:631",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "gpiod_get_from_of_node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:597",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct gpio_desc * gpiod_get_from_of_node(struct device_node * node, const char * propname, int index, enum gpiod_flags dflags, const char * label)
```

```json
{
  "name": "gpiod_get_from_of_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496741800,
      "name": "gpiod_get_from_of_node",
      "external": true,
      "loc": "drivers/gpio/gpiolib-of.c:316",
      "file": "drivers/gpio/gpiolib-of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496741800,
      "name": "gpiod_get_from_of_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
struct gpio_desc * gpiod_get_from_of_node(struct device_node * node, const char * propname, int index, enum gpiod_flags dflags, const char * label)
```

```json
{
  "name": "gpiod_get_from_of_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230029168,
      "name": "gpiod_get_from_of_node",
      "external": true,
      "loc": "drivers/gpio/gpiolib-of.c:316",
      "file": "drivers/gpio/gpiolib-of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230029168,
      "name": "gpiod_get_from_of_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct gpio_desc * gpiod_get_from_of_node(struct device_node * node, const char * propname, int index, enum gpiod_flags dflags, const char * label)
```

```json
{
  "name": "gpiod_get_from_of_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290835168,
      "name": "gpiod_get_from_of_node",
      "external": true,
      "loc": "drivers/gpio/gpiolib-of.c:316",
      "file": "drivers/gpio/gpiolib-of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290835168,
      "name": "gpiod_get_from_of_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
struct gpio_desc * gpiod_get_from_of_node(struct device_node * node, const char * propname, int index, enum gpiod_flags dflags, const char * label)
```

```json
{
  "name": "gpiod_get_from_of_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275494536,
      "name": "gpiod_get_from_of_node",
      "external": true,
      "loc": "drivers/gpio/gpiolib-of.c:316",
      "file": "drivers/gpio/gpiolib-of.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275494536,
      "name": "gpiod_get_from_of_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
  "name": "gpiod_get_from_of_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:577",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:577",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "gpiod_get_from_of_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:577",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:577",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "gpiod_get_from_of_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:577",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:577",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "gpiod_get_from_of_node",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:577",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gpiod_get_from_of_node",
      "external": false,
      "loc": "include/linux/gpio/consumer.h:577",
      "file": "drivers/gpio/gpiolib-devres.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct gpio_desc * gpiod_get_from_of_node(struct device_node * node, const char * propname, int index, enum gpiod_flags dflags, const char * label)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
struct gpio_desc * gpiod_get_from_of_node(struct device_node * node, const char * propname, int index, enum gpiod_flags dflags, const char * label)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct gpio_desc * gpiod_get_from_of_node(struct device_node * node, const char * propname, int index, enum gpiod_flags dflags, const char * label)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct gpio_desc * gpiod_get_from_of_node(struct device_node * node, const char * propname, int index, enum gpiod_flags dflags, const char * label)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct gpio_desc * gpiod_get_from_of_node(struct device_node * node, const char * propname, int index, enum gpiod_flags dflags, const char * label)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct gpio_desc * gpiod_get_from_of_node(struct device_node * node, const char * propname, int index, enum gpiod_flags dflags, const char * label)
```
</details>
</li>
</ul>
