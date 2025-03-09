# Function: <code>intel_gpio_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void intel_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```

```json
{
  "name": "intel_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583211648,
      "name": "intel_gpio_set",
      "external": false,
      "loc": "drivers/gpio/gpio-intel-mid.c:126",
      "file": "drivers/gpio/gpio-intel-mid.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-intel-mid.c:intel_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211648,
      "name": "intel_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void intel_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```

```json
{
  "name": "intel_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583913696,
      "name": "intel_gpio_set",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:770",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583913696,
      "name": "intel_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void intel_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```

```json
{
  "name": "intel_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585340432,
      "name": "intel_gpio_set",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:934",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340432,
      "name": "intel_gpio_set",
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
void intel_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```

```json
{
  "name": "intel_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585224896,
      "name": "intel_gpio_set",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:944",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585224896,
      "name": "intel_gpio_set",
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
void intel_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```

```json
{
  "name": "intel_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585680256,
      "name": "intel_gpio_set",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:941",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680256,
      "name": "intel_gpio_set",
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
void intel_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```

```json
{
  "name": "intel_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586845456,
      "name": "intel_gpio_set",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:946",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586845456,
      "name": "intel_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void intel_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```

```json
{
  "name": "intel_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587988448,
      "name": "intel_gpio_set",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:958",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587988448,
      "name": "intel_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void intel_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```

```json
{
  "name": "intel_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588262992,
      "name": "intel_gpio_set",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:970",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588262992,
      "name": "intel_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void intel_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```

```json
{
  "name": "intel_gpio_set",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588555392,
      "name": "intel_gpio_set",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:938",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_direction_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588555392,
      "name": "intel_gpio_set",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void intel_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void intel_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void intel_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void intel_gpio_set(struct gpio_chip * chip, unsigned int offset, int value)
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
