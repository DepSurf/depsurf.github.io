# Function: <code>chv_gpio_set_intr_line</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int chv_gpio_set_intr_line(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "chv_gpio_set_intr_line",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "chv_gpio_set_intr_line",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:1344",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586835216,
      "name": "chv_gpio_set_intr_line",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    },
    {
      "addr": 18446744071594211502,
      "name": "chv_gpio_set_intr_line.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "chv_gpio_set_intr_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587982008,
      "name": "chv_gpio_set_intr_line",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:1346",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "chv_gpio_set_intr_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588256616,
      "name": "chv_gpio_set_intr_line",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:1351",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type"
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
  "name": "chv_gpio_set_intr_line",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588548424,
      "name": "chv_gpio_set_intr_line",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-cherryview.c:1275",
      "file": "drivers/pinctrl/intel/pinctrl-cherryview.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int chv_gpio_set_intr_line(struct intel_pinctrl * pctrl, unsigned int pin)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int chv_gpio_set_intr_line(struct intel_pinctrl * pctrl, unsigned int pin)
```
</details>
</li>
</ul>
