# Function: <code>intel_gpio_community_irq_handler</code>

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
  "name": "intel_gpio_community_irq_handler",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583911223,
      "name": "intel_gpio_community_irq_handler",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1023",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int intel_gpio_community_irq_handler(struct intel_pinctrl * pctrl, const struct intel_community * community)
```

```json
{
  "name": "intel_gpio_community_irq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585336576,
      "name": "intel_gpio_community_irq_handler",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1156",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585336576,
      "name": "intel_gpio_community_irq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
int intel_gpio_community_irq_handler(struct intel_pinctrl * pctrl, const struct intel_community * community)
```

```json
{
  "name": "intel_gpio_community_irq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585224064,
      "name": "intel_gpio_community_irq_handler",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1166",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585224064,
      "name": "intel_gpio_community_irq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int intel_gpio_community_irq_handler(struct intel_pinctrl * pctrl, const struct intel_community * community)
```

```json
{
  "name": "intel_gpio_community_irq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585679408,
      "name": "intel_gpio_community_irq_handler",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1160",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679408,
      "name": "intel_gpio_community_irq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int intel_gpio_community_irq_handler(struct intel_pinctrl * pctrl, const struct intel_community * community)
```

```json
{
  "name": "intel_gpio_community_irq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586844480,
      "name": "intel_gpio_community_irq_handler",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1183",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586844480,
      "name": "intel_gpio_community_irq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
int intel_gpio_community_irq_handler(struct intel_pinctrl * pctrl, const struct intel_community * community)
```

```json
{
  "name": "intel_gpio_community_irq_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587983472,
      "name": "intel_gpio_community_irq_handler",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1195",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983472,
      "name": "intel_gpio_community_irq_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
  "name": "intel_gpio_community_irq_handler",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588258260,
      "name": "intel_gpio_community_irq_handler",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1211",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_gpio_community_irq_handler",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588550044,
      "name": "intel_gpio_community_irq_handler",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:1174",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int intel_gpio_community_irq_handler(struct intel_pinctrl * pctrl, const struct intel_community * community)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int intel_gpio_community_irq_handler(struct intel_pinctrl * pctrl, const struct intel_community * community)
```
</details>
</li>
</ul>
