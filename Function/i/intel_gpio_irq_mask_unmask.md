# Function: <code>intel_gpio_irq_mask_unmask</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void intel_gpio_irq_mask_unmask(struct irq_data * d, bool mask)
```

```json
{
  "name": "intel_gpio_irq_mask_unmask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583911696,
      "name": "intel_gpio_irq_mask_unmask",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:910",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583911696,
      "name": "intel_gpio_irq_mask_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void intel_gpio_irq_mask_unmask(struct irq_data * d, bool mask)
```

```json
{
  "name": "intel_gpio_irq_mask_unmask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585339856,
      "name": "intel_gpio_irq_mask_unmask",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1035",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585339856,
      "name": "intel_gpio_irq_mask_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
void intel_gpio_irq_mask_unmask(struct irq_data * d, bool mask)
```

```json
{
  "name": "intel_gpio_irq_mask_unmask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585223760,
      "name": "intel_gpio_irq_mask_unmask",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1045",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585223760,
      "name": "intel_gpio_irq_mask_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void intel_gpio_irq_mask_unmask(struct irq_data * d, bool mask)
```

```json
{
  "name": "intel_gpio_irq_mask_unmask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gpio_irq_mask_unmask",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1042",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679072,
      "name": "intel_gpio_irq_mask_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    },
    {
      "addr": 18446744071592350208,
      "name": "intel_gpio_irq_mask_unmask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
void intel_gpio_irq_mask_unmask(struct gpio_chip * gc, irq_hw_number_t hwirq, bool mask)
```

```json
{
  "name": "intel_gpio_irq_mask_unmask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gpio_irq_mask_unmask",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1047",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586844064,
      "name": "intel_gpio_irq_mask_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071594211774,
      "name": "intel_gpio_irq_mask_unmask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void intel_gpio_irq_mask_unmask(struct gpio_chip * gc, irq_hw_number_t hwirq, bool mask)
```

```json
{
  "name": "intel_gpio_irq_mask_unmask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gpio_irq_mask_unmask",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1059",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587987408,
      "name": "intel_gpio_irq_mask_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071596205021,
      "name": "intel_gpio_irq_mask_unmask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void intel_gpio_irq_mask_unmask(struct gpio_chip * gc, irq_hw_number_t hwirq, bool mask)
```

```json
{
  "name": "intel_gpio_irq_mask_unmask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gpio_irq_mask_unmask",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1071",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588261952,
      "name": "intel_gpio_irq_mask_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071596730041,
      "name": "intel_gpio_irq_mask_unmask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void intel_gpio_irq_mask_unmask(struct gpio_chip * gc, irq_hw_number_t hwirq, bool mask)
```

```json
{
  "name": "intel_gpio_irq_mask_unmask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_gpio_irq_mask_unmask",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1039",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588554336,
      "name": "intel_gpio_irq_mask_unmask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071597638423,
      "name": "intel_gpio_irq_mask_unmask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void intel_gpio_irq_mask_unmask(struct irq_data * d, bool mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void intel_gpio_irq_mask_unmask(struct irq_data * d, bool mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void intel_gpio_irq_mask_unmask(struct irq_data * d, bool mask)
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip * gc</code>
</li>
<li>
<b>Param added. </b>
<code>irq_hw_number_t hwirq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct irq_data * d</code>
</li>
<li>
<b>Param reordered. </b>
<code>d, mask</code> ➡️ <code>gc, hwirq, mask</code>
</li>
</ul>
</details>
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
