# Function: <code>intel_pad_locked</code>

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
bool intel_pad_locked(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583912848,
      "name": "intel_pad_locked",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:222",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pad_usable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912848,
      "name": "intel_pad_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int intel_pad_locked(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pad_locked",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:212",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585341824,
      "name": "intel_pad_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071591385449,
      "name": "intel_pad_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int intel_pad_locked(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pad_locked",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:222",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585226112,
      "name": "intel_pad_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071591327880,
      "name": "intel_pad_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int intel_pad_locked(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pad_locked",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:222",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681520,
      "name": "intel_pad_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071592350457,
      "name": "intel_pad_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
int intel_pad_locked(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pad_locked",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:222",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586846816,
      "name": "intel_pad_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071594212050,
      "name": "intel_pad_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int intel_pad_locked(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pad_locked",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:229",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587989968,
      "name": "intel_pad_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071596205179,
      "name": "intel_pad_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int intel_pad_locked(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pad_locked",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:231",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264528,
      "name": "intel_pad_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071596730199,
      "name": "intel_pad_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int intel_pad_locked(struct intel_pinctrl * pctrl, unsigned int pin)
```

```json
{
  "name": "intel_pad_locked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pad_locked",
      "external": false,
      "loc": "drivers/pinctrl/intel/pinctrl-intel.c:232",
      "file": "drivers/pinctrl/intel/pinctrl-intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588556928,
      "name": "intel_pad_locked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071597638581,
      "name": "intel_pad_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
bool intel_pad_locked(struct intel_pinctrl * pctrl, unsigned int pin)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
bool intel_pad_locked(struct intel_pinctrl * pctrl, unsigned int pin)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int intel_pad_locked(struct intel_pinctrl * pctrl, unsigned int pin)
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
