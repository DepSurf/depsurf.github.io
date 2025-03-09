# Function: <code>gpio_v2_line_config_debounced</code>

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
  "name": "gpio_v2_line_config_debounced",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585373604,
      "name": "gpio_v2_line_config_debounced",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:741",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup"
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
  "name": "gpio_v2_line_config_debounced",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585257972,
      "name": "gpio_v2_line_config_debounced",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:741",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup"
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
bool gpio_v2_line_config_debounced(struct gpio_v2_line_config * lc, unsigned int line_idx)
```

```json
{
  "name": "gpio_v2_line_config_debounced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_v2_line_config_debounced",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:741",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585713232,
      "name": "gpio_v2_line_config_debounced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071592354754,
      "name": "gpio_v2_line_config_debounced.cold",
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
bool gpio_v2_line_config_debounced(struct gpio_v2_line_config * lc, unsigned int line_idx)
```

```json
{
  "name": "gpio_v2_line_config_debounced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_v2_line_config_debounced",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:905",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_validate",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586883152,
      "name": "gpio_v2_line_config_debounced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071594216899,
      "name": "gpio_v2_line_config_debounced.cold",
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
bool gpio_v2_line_config_debounced(struct gpio_v2_line_config * lc, unsigned int line_idx)
```

```json
{
  "name": "gpio_v2_line_config_debounced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_v2_line_config_debounced",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:976",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_validate",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588032992,
      "name": "gpio_v2_line_config_debounced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071596205782,
      "name": "gpio_v2_line_config_debounced.cold",
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
bool gpio_v2_line_config_debounced(struct gpio_v2_line_config * lc, unsigned int line_idx)
```

```json
{
  "name": "gpio_v2_line_config_debounced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_v2_line_config_debounced",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:975",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_validate",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588307296,
      "name": "gpio_v2_line_config_debounced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071596730849,
      "name": "gpio_v2_line_config_debounced.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool gpio_v2_line_config_debounced(struct gpio_v2_line_config * lc, unsigned int line_idx)
```

```json
{
  "name": "gpio_v2_line_config_debounced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_v2_line_config_debounced",
      "external": false,
      "loc": "drivers/gpio/gpiolib-cdev.c:1064",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_validate",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588600944,
      "name": "gpio_v2_line_config_debounced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071597639219,
      "name": "gpio_v2_line_config_debounced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
bool gpio_v2_line_config_debounced(struct gpio_v2_line_config * lc, unsigned int line_idx)
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
