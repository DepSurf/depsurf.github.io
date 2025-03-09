# Function: <code>intel_pad_owned_by_host</code>

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
bool intel_pad_owned_by_host(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_owned_by_host",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583912688,
      "name": "intel_pad_owned_by_host",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:173",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_usable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912688,
      "name": "intel_pad_owned_by_host",
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
bool intel_pad_owned_by_host(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_owned_by_host",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pad_owned_by_host",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:144",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585341568,
      "name": "intel_pad_owned_by_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071591385424,
      "name": "intel_pad_owned_by_host.cold",
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
bool intel_pad_owned_by_host(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_owned_by_host",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pad_owned_by_host",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:154",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585225872,
      "name": "intel_pad_owned_by_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071591327854,
      "name": "intel_pad_owned_by_host.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
bool intel_pad_owned_by_host(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_owned_by_host",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pad_owned_by_host",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:154",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680704,
      "name": "intel_pad_owned_by_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071592350348,
      "name": "intel_pad_owned_by_host.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
bool intel_pad_owned_by_host(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_owned_by_host",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pad_owned_by_host",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:154",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586845968,
      "name": "intel_pad_owned_by_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071594211932,
      "name": "intel_pad_owned_by_host.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
bool intel_pad_owned_by_host(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_owned_by_host",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587989024,
      "name": "intel_pad_owned_by_host",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:161",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587989024,
      "name": "intel_pad_owned_by_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
bool intel_pad_owned_by_host(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_owned_by_host",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588263568,
      "name": "intel_pad_owned_by_host",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:163",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588263568,
      "name": "intel_pad_owned_by_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
bool intel_pad_owned_by_host(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_owned_by_host",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588555968,
      "name": "intel_pad_owned_by_host",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:164",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588555968,
      "name": "intel_pad_owned_by_host",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
bool intel_pad_owned_by_host(struct intel_pinctrl * pctrl, unsigned int pin)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
bool intel_pad_owned_by_host(struct intel_pinctrl * pctrl, unsigned int pin)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool intel_pad_owned_by_host(struct intel_pinctrl * pctrl, unsigned int pin)
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
