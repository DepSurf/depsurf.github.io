# Function: <code>intel_gpio_irq_init</code>

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
  "name": "intel_gpio_irq_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583918305,
      "name": "intel_gpio_irq_init",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1433",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume"
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
  "name": "intel_gpio_irq_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585343722,
      "name": "intel_gpio_irq_init",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1643",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq"
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
  "name": "intel_gpio_irq_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585227990,
      "name": "intel_gpio_irq_init",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1698",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void intel_gpio_irq_init(struct intel_pinctrl * pctrl)
```

```json
{
  "name": "intel_gpio_irq_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585675504,
      "name": "intel_gpio_irq_init",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1213",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585675504,
      "name": "intel_gpio_irq_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void intel_gpio_irq_init(struct intel_pinctrl * pctrl)
```

```json
{
  "name": "intel_gpio_irq_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586840304,
      "name": "intel_gpio_irq_init",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1236",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586840304,
      "name": "intel_gpio_irq_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void intel_gpio_irq_init(struct intel_pinctrl * pctrl)
```

```json
{
  "name": "intel_gpio_irq_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587982736,
      "name": "intel_gpio_irq_init",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1248",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587982736,
      "name": "intel_gpio_irq_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void intel_gpio_irq_init(struct intel_pinctrl * pctrl)
```

```json
{
  "name": "intel_gpio_irq_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588257440,
      "name": "intel_gpio_irq_init",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1259",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588257440,
      "name": "intel_gpio_irq_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void intel_gpio_irq_init(struct intel_pinctrl * pctrl)
```

```json
{
  "name": "intel_gpio_irq_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588549184,
      "name": "intel_gpio_irq_init",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1225",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_init_hw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588549184,
      "name": "intel_gpio_irq_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void intel_gpio_irq_init(struct intel_pinctrl * pctrl)
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
