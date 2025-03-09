# Function: <code>intel_get_padcfg</code>

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
void * intel_get_padcfg(struct intel_pinctrl * pctrl, unsigned int pin, unsigned int reg)
```

```json
{
  "name": "intel_get_padcfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583913072,
      "name": "intel_get_padcfg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:153",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_resume",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583913072,
      "name": "intel_get_padcfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void * intel_get_padcfg(struct intel_pinctrl * pctrl, unsigned int pin, unsigned int reg)
```

```json
{
  "name": "intel_get_padcfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_get_padcfg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:124",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340160,
      "name": "intel_get_padcfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071591385345,
      "name": "intel_get_padcfg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void * intel_get_padcfg(struct intel_pinctrl * pctrl, unsigned int pin, unsigned int reg)
```

```json
{
  "name": "intel_get_padcfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_get_padcfg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:134",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585224480,
      "name": "intel_get_padcfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071591327775,
      "name": "intel_get_padcfg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void * intel_get_padcfg(struct intel_pinctrl * pctrl, unsigned int pin, unsigned int reg)
```

```json
{
  "name": "intel_get_padcfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_get_padcfg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:134",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679840,
      "name": "intel_get_padcfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071592350323,
      "name": "intel_get_padcfg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void * intel_get_padcfg(struct intel_pinctrl * pctrl, unsigned int pin, unsigned int reg)
```

```json
{
  "name": "intel_get_padcfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_get_padcfg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:134",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586844960,
      "name": "intel_get_padcfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    },
    {
      "addr": 18446744071594211908,
      "name": "intel_get_padcfg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void * intel_get_padcfg(struct intel_pinctrl * pctrl, unsigned int pin, unsigned int reg)
```

```json
{
  "name": "intel_get_padcfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587987872,
      "name": "intel_get_padcfg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:141",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587987872,
      "name": "intel_get_padcfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void * intel_get_padcfg(struct intel_pinctrl * pctrl, unsigned int pin, unsigned int reg)
```

```json
{
  "name": "intel_get_padcfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588262416,
      "name": "intel_get_padcfg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:143",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set_pull",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588262416,
      "name": "intel_get_padcfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void * intel_get_padcfg(struct intel_pinctrl * pctrl, unsigned int pin, unsigned int reg)
```

```json
{
  "name": "intel_get_padcfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588554816,
      "name": "intel_get_padcfg",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:144",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_restore_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_suspend_noirq",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588554816,
      "name": "intel_get_padcfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void * intel_get_padcfg(struct intel_pinctrl * pctrl, unsigned int pin, unsigned int reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void * intel_get_padcfg(struct intel_pinctrl * pctrl, unsigned int pin, unsigned int reg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void * intel_get_padcfg(struct intel_pinctrl * pctrl, unsigned int pin, unsigned int reg)
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
