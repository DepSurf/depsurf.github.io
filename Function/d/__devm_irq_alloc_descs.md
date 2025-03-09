# Function: <code>__devm_irq_alloc_descs</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct cpumask * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805936,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:179",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805936,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct cpumask * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579840064,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:179",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840064,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct cpumask * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579873808,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:180",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873808,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579920848,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:180",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920848,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959184,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959184,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008976,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008976,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580058944,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058944,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580040832,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580040832,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580041680,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041680,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580174288,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580174288,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580321520,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580321520,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580536448,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580536448,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580609792,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609792,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580674304,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580674304,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491206792,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491206792,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225224924,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225224924,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284110384,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284110384,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271747186,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271747186,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579977712,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977712,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915520,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915520,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579969248,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579969248,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct irq_affinity_desc * affinity)
```

```json
{
  "name": "__devm_irq_alloc_descs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580015872,
      "name": "__devm_irq_alloc_descs",
      "external": true,
      "loc": "kernel/irq/devres.c:178",
      "file": "kernel/irq/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015872,
      "name": "__devm_irq_alloc_descs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
    }
  ]
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __devm_irq_alloc_descs(struct device * dev, int irq, unsigned int from, unsigned int cnt, int node, struct module * owner, const struct cpumask * affinity)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct cpumask * affinity</code> ➡️ <code>const struct irq_affinity_desc * affinity</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
