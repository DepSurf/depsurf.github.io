# Function: <code>irq_set_type</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
void irq_set_type(struct owl_pinctrl * pctrl, int gpio, unsigned int type)
```

```json
{
  "name": "irq_set_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496582840,
      "name": "irq_set_type",
      "external": false,
      "loc": "drivers/pinctrl/actions/pinctrl-owl.c:660",
      "file": "drivers/pinctrl/actions/pinctrl-owl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_set_type",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_set_type",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496582840,
      "name": "irq_set_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
void irq_set_type(struct owl_pinctrl * pctrl, int gpio, unsigned int type)
```

```json
{
  "name": "irq_set_type",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229897704,
      "name": "irq_set_type",
      "external": false,
      "loc": "drivers/pinctrl/actions/pinctrl-owl.c:660",
      "file": "drivers/pinctrl/actions/pinctrl-owl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_set_type",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229897704,
      "name": "irq_set_type",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void irq_set_type(struct owl_pinctrl * pctrl, int gpio, unsigned int type)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void irq_set_type(struct owl_pinctrl * pctrl, int gpio, unsigned int type)
```
</details>
</li>
</ul>
