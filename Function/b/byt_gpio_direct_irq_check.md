# Function: <code>byt_gpio_direct_irq_check</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "byt_gpio_direct_irq_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585176624,
      "name": "byt_gpio_direct_irq_check",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:803",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "byt_gpio_direct_irq_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585325888,
      "name": "byt_gpio_direct_irq_check",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:803",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction"
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
  "name": "byt_gpio_direct_irq_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585210016,
      "name": "byt_gpio_direct_irq_check",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:803",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void byt_gpio_direct_irq_check(struct intel_pinctrl * vg, unsigned int offset)
```

```json
{
  "name": "byt_gpio_direct_irq_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592349698,
      "name": "byt_gpio_direct_irq_check",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:803",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661680,
      "name": "byt_gpio_direct_irq_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071592349677,
      "name": "byt_gpio_direct_irq_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void byt_gpio_direct_irq_check(struct intel_pinctrl * vg, unsigned int offset)
```

```json
{
  "name": "byt_gpio_direct_irq_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594211112,
      "name": "byt_gpio_direct_irq_check",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:814",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586824592,
      "name": "byt_gpio_direct_irq_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071594211088,
      "name": "byt_gpio_direct_irq_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void byt_gpio_direct_irq_check(struct intel_pinctrl * vg, unsigned int offset)
```

```json
{
  "name": "byt_gpio_direct_irq_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587965853,
      "name": "byt_gpio_direct_irq_check",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:814",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965760,
      "name": "byt_gpio_direct_irq_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071596204898,
      "name": "byt_gpio_direct_irq_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void byt_gpio_direct_irq_check(struct intel_pinctrl * vg, unsigned int offset)
```

```json
{
  "name": "byt_gpio_direct_irq_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588240373,
      "name": "byt_gpio_direct_irq_check",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:810",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588240272,
      "name": "byt_gpio_direct_irq_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071596729918,
      "name": "byt_gpio_direct_irq_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void byt_gpio_direct_irq_check(struct intel_pinctrl * vg, unsigned int offset)
```

```json
{
  "name": "byt_gpio_direct_irq_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588536094,
      "name": "byt_gpio_direct_irq_check",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-baytrail.c:729",
      "file": "drivers/pinctrl/intel/pinctrl-baytrail.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588535984,
      "name": "byt_gpio_direct_irq_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071597638267,
      "name": "byt_gpio_direct_irq_check.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void byt_gpio_direct_irq_check(struct intel_pinctrl * vg, unsigned int offset)
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
