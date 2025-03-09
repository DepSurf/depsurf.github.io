# Function: <code>gpio_v2_line_config_output_value</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gpio_v2_line_config_output_value",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585379140,
      "name": "gpio_v2_line_config_output_value",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:875",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked"
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
  "name": "gpio_v2_line_config_output_value",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585261989,
      "name": "gpio_v2_line_config_output_value",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:875",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int gpio_v2_line_config_output_value(struct gpio_v2_line_config * lc, unsigned int line_idx)
```

```json
{
  "name": "gpio_v2_line_config_output_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_v2_line_config_output_value",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:875",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585713456,
      "name": "gpio_v2_line_config_output_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071592354814,
      "name": "gpio_v2_line_config_output_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int gpio_v2_line_config_output_value(struct gpio_v2_line_config * lc, unsigned int line_idx)
```

```json
{
  "name": "gpio_v2_line_config_output_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_v2_line_config_output_value",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:1051",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586883408,
      "name": "gpio_v2_line_config_output_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071594216959,
      "name": "gpio_v2_line_config_output_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int gpio_v2_line_config_output_value(struct gpio_v2_line_config * lc, unsigned int line_idx)
```

```json
{
  "name": "gpio_v2_line_config_output_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_v2_line_config_output_value",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:1119",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588033280,
      "name": "gpio_v2_line_config_output_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071596205842,
      "name": "gpio_v2_line_config_output_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int gpio_v2_line_config_output_value(struct gpio_v2_line_config * lc, unsigned int line_idx)
```

```json
{
  "name": "gpio_v2_line_config_output_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_v2_line_config_output_value",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:1118",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588307808,
      "name": "gpio_v2_line_config_output_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071596730917,
      "name": "gpio_v2_line_config_output_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int gpio_v2_line_config_output_value(struct gpio_v2_line_config * lc, unsigned int line_idx)
```

```json
{
  "name": "gpio_v2_line_config_output_value",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_v2_line_config_output_value",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:1206",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588601456,
      "name": "gpio_v2_line_config_output_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071597639287,
      "name": "gpio_v2_line_config_output_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int gpio_v2_line_config_output_value(struct gpio_v2_line_config * lc, unsigned int line_idx)
```
</details>
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
