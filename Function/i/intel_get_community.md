# Function: <code>intel_get_community</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct intel_community * intel_get_community(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_get_community",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583912576,
      "name": "intel_get_community",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:120",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912576,
      "name": "intel_get_community",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_get_community",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591385477,
      "name": "intel_get_community",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:91",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg"
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
  "name": "intel_get_community",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591327908,
      "name": "intel_get_community",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:101",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_get_community",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592350551,
      "name": "intel_get_community",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:101",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_get_community",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594212139,
      "name": "intel_get_community",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:101",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_get_community",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587991459,
      "name": "intel_get_community",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:108",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg"
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
  "name": "intel_get_community",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588266019,
      "name": "intel_get_community",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:110",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set_pull",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set_pull",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct intel_community * intel_get_community(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_get_community",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588560211,
      "name": "intel_get_community",
      "external": true,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:111",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_locked",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_acpi_mode",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_owned_by_host",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_padcfg"
      ],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_resume",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_suspend",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_init_hw",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_irq_handler",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_ack",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_dbg_show",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_output",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_direction_input",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_clear_triggering",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588550688,
      "name": "intel_get_community",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct intel_community * intel_get_community(struct intel_pinctrl * pctrl, unsigned int pin)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct intel_community * intel_get_community(struct intel_pinctrl * pctrl, unsigned int pin)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
struct intel_community * intel_get_community(struct intel_pinctrl * pctrl, unsigned int pin)
```
</details>
</li>
</ul>
