# Function: <code>pinctrl_dev_get_drvdata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583157664,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:88",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157664,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583454256,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:88",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583454256,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583582000,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:88",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582000,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583620704,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:88",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620704,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583866816,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:88",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866816,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584067360,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:88",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584067360,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584151936,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:87",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584151936,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584342128,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:86",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584342128,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584476784,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:86",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476784,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585141232,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:86",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585141232,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585292368,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:87",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585292368,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585176304,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:87",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585176304,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585630064,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:87",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585630064,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586790048,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:87",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790048,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587925072,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:88",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_set_mux",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587925072,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588199232,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:87",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_set_mux",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588199232,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588491392,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:87",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_set_mux",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_set",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_function_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_group_name",
        "drivers/pinctrl/intel/pinctrl-intel.c:intel_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588491392,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496492544,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:86",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinconf_set",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinconf_get",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_set_direction",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_request_enable",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_func_groups",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_func_name",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_funcs_count",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_group_pins",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_group_name",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_groups_count",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinconf_group_set",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinconf_cfg_set",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinconf_cfg_get",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinmux_set_mux",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pmux_get_function_groups",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pmux_get_function_name",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pmux_get_functions_count",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pctrl_get_group_pins",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pctrl_get_group_name",
        "drivers/pinctrl/pinctrl-bm1880.c:bm1880_pctrl_get_groups_count",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_group_set",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_get",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_set",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pmx_get_groups",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pmx_get_func_name",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pmx_get_funcs_count",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_get_group_pins",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_get_group_name",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_get_groups_count",
        "drivers/pinctrl/meson/pinctrl-meson8-pmx.c:meson8_pmx_request_gpio",
        "drivers/pinctrl/meson/pinctrl-meson8-pmx.c:meson8_pmx_set_mux",
        "drivers/pinctrl/meson/pinctrl-meson-axg-pmx.c:meson_axg_pmx_request_gpio",
        "drivers/pinctrl/meson/pinctrl-meson-axg-pmx.c:meson_axg_pmx_set_mux",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_set",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_set_mux",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_func_groups",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_func_name",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_funcs_count",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_group_pins",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_group_name",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_groups_count",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_get",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_set",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pmx_gpio_set_direction",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pmx_set",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pmx_get_groups",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pmx_get_func_name",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pmx_get_funcs_count",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_dt_node_to_map",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_get_group_pins",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_get_group_name",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_get_groups_count",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set",
        "drivers/pinctrl/pinctrl-single.c:pcs_pinconf_get",
        "drivers/pinctrl/pinctrl-single.c:pcs_request_gpio",
        "drivers/pinctrl/pinctrl-single.c:pcs_set_mux",
        "drivers/pinctrl/pinctrl-single.c:pcs_get_function",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_free_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_pin_dbg_show",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pctl_get_group_pins",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pctl_get_group_name",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pctl_get_groups_count",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_request_enable",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set_direction",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinmux_set_mux",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_get_function_groups",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_get",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_get",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_set_mux",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_get_func_groups",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_get_func_name",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_get_funcs_count",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_dbg_show",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_get_group_pins",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_get_group_name",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_get_groups_count",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2711_pinconf_set",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinconf_set",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_gpio_set_direction",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_gpio_disable_free",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_set",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pmx_free",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_dt_node_to_map",
        "drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_pin_dbg_show",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_set",
        "drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_get",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_get_pull",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_set_pull",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_enable",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_get_function_groups",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_get_function_name",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_get_functions_count",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_get_group_pins",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_get_group_name",
        "drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_get_groups_count",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinmux_set",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinmux_get_function_groups",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinmux_get_function_name",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinmux_get_functions_count",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_dt_node_to_map",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_get_group_name",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_get_group_count",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_dbg_show",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_set",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_set",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_get",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_get",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_dt_node_to_map",
        "drivers/pinctrl/freescale/pinctrl-scu.c:imx_pinconf_set_scu",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_dt_node_to_map",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_get_group_pins",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_get_group_name",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_get_groups_count",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_gpio_set_direction",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_gpio_request_enable",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_set",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_get_groups",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_get_func_name",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_get_funcs_count",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_set",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_get",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_gpio_request_enable",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pmx_gpio_set_direction",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pmx_set",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pmx_set_by_name",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pmx_get_groups",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pmx_get_func_name",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pmx_get_funcs_count",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_get_group_pins",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_get_group_name",
        "drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_get_groups_count",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_get",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_request_gpio",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_get_function_groups",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_get_function_name",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_get_functions_count",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_request",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_get_group_pins",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_get_group_name",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_get_groups_count",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_group_set",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_set_direction",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_disable_free",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_request_enable",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_func_set_mux",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_get_function_groups",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_get_function_name",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_get_functions_count",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_node_to_map",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_get_group_pins",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_get_group_name",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_get_groups_count",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_group_dbg_show",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_get_config",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_group_set",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_group_get",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_set",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_get",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pmx_set_mux",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pmx_get_function_groups",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_dt_node_to_map",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pctrl_group_pins",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pctrl_group_name",
        "drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pctrl_group_count",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_free",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_gpio_set_direction",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_set_mux",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_set",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_get_func_groups",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_get_func_name",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_get_funcs_cnt",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_group_set",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_set",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_group_get",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_get",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pctrl_dt_node_to_map",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pctrl_get_group_pins",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pctrl_get_group_name",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pctrl_get_groups_count",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_gpio_request_enable",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_set_mux",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_set_mode",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_get_func_groups",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_get_group_pins",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_get_group_name",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_get_groups_count",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_dt_node_to_map",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_get",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_gpio_set_direction",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_gpio_set_direction",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_gpio_request_enable",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_set_mux",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_get",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pmx_set_mux",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pmx_get_func_groups",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pctrl_get_group_pins",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pctrl_get_group_name",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pctrl_get_groups_count",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pctrl_dt_node_to_map",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pinconf_get",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pinmux_gpio_set_direction",
        "drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pinmux_gpio_request_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496492544,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229799568,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:86",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinconf_set",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinconf_get",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_set_direction",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_request_enable",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_func_groups",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_func_name",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_funcs_count",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_group_pins",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_group_name",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_groups_count",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_group_set",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_get",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_set",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pmx_get_groups",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pmx_get_func_name",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_pmx_get_funcs_count",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_get_group_pins",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_get_group_name",
        "drivers/pinctrl/meson/pinctrl-meson.c:meson_get_groups_count",
        "drivers/pinctrl/meson/pinctrl-meson8-pmx.c:meson8_pmx_request_gpio",
        "drivers/pinctrl/meson/pinctrl-meson8-pmx.c:meson8_pmx_set_mux",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_set",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_set_mux",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_func_groups",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_func_name",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_funcs_count",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_group_pins",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_group_name",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_groups_count",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_get",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_set",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pmx_gpio_set_direction",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pmx_set",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pmx_get_groups",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pmx_get_func_name",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_pmx_get_funcs_count",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_dt_node_to_map",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_get_group_pins",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_get_group_name",
        "drivers/pinctrl/pinctrl-rockchip.c:rockchip_get_groups_count",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux",
        "drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map",
        "drivers/pinctrl/pinctrl-rza2.c:rza2_set_mux",
        "drivers/pinctrl/pinctrl-rza2.c:rza2_dt_node_to_map",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_group_set",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_group_get",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_set",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinconf_get",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_set_mux",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pmx_get_groups",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pmx_get_func_name",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_pmx_get_funcs_count",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_dt_node_to_map_one",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_get_group_pins",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_get_group_name",
        "drivers/pinctrl/pinctrl-rzn1.c:rzn1_get_groups_count",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set",
        "drivers/pinctrl/pinctrl-single.c:pcs_pinconf_get",
        "drivers/pinctrl/pinctrl-single.c:pcs_request_gpio",
        "drivers/pinctrl/pinctrl-single.c:pcs_set_mux",
        "drivers/pinctrl/pinctrl-single.c:pcs_get_function",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_free_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_pin_dbg_show",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_group_dbg_show",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_group_set",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinconf_group_get",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_set_mux",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_get_func_groups",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_get_func_name",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_get_funcs_count",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_get_group_pins",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_get_group_name",
        "drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_get_groups_count",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_pinconf_group_set",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_pinconf_group_get",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_pinmux_set",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_get_function_groups",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_get_function_name",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_get_functions_count",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_dt_node_to_map",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_get_group_name",
        "drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_get_groups_count",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pctl_get_group_pins",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pctl_get_group_name",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pctl_get_groups_count",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_request_enable",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set_direction",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinmux_set_mux",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_get_function_groups",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_set",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_get",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_set",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_get",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_set_mux",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_get_func_groups",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_get_func_name",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_get_funcs_count",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_dbg_show",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_get_group_pins",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_get_group_name",
        "drivers/pinctrl/actions/pinctrl-owl.c:owl_get_groups_count",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pin_config_group_set",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pin_config_group_get",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pin_config_set",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pin_config_get",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_gpio_request_enable",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pinmux_set_mux",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pinmux_get_fn_groups",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pinmux_get_fn_name",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pinmux_get_fn_count",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pinctrl_get_group_name",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pinctrl_get_groups_count",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinmux_set",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinmux_get_function_groups",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinmux_get_function_name",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinmux_get_functions_count",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_dt_node_to_map",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_get_group_name",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_get_group_count",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_dbg_show",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_set",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_set",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_get",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinconf_get",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_pmx_set",
        "drivers/pinctrl/freescale/pinctrl-imx.c:imx_dt_node_to_map",
        "drivers/pinctrl/freescale/pinctrl-imx7ulp.c:imx7ulp_pmx_gpio_set_direction",
        "drivers/pinctrl/freescale/pinctrl-vf610.c:vf610_pmx_gpio_set_direction",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_dt_node_to_map",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_get_group_pins",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_get_group_name",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_get_groups_count",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_gpio_set_direction",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_gpio_request_enable",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_set",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_get_groups",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_get_func_name",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinmux_get_funcs_count",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_set",
        "drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_set",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set_direction",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_gpio_request_free",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_gpio_request_enable",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinmux_set_mux",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_dt_node_to_map",
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_get_groups_count",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_set",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_get",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_request_gpio",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_get_function_groups",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_get_function_name",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_get_functions_count",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_request",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_get_group_pins",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_get_group_name",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_get_groups_count",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinconf_group_get",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinconf_group_set",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinconf_rw",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinmux_set_mux",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinmux_get_groups",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinmux_get_fname",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_get_functions_count",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_dt_node_to_map",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_get_group_pins",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_get_group_name",
        "drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_get_group_count",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_group_set",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_set",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_set_direction",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_disable_free",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_request_enable",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_func_set_mux",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_get_function_groups",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_get_function_name",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_get_functions_count",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_node_to_map",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_get_group_pins",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_get_group_name",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_get_groups_count",
        "drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_pinconf_group_dbg_show",
        "drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_pin_dbg_show",
        "drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_pinconf_group_set",
        "drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_pinconf_group_get",
        "drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map",
        "drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pmx_gpio_request_enable",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pmx_set_mux",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pmx_set_one_mux",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pmx_get_function_groups",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pmx_get_function_name",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pmx_get_functions_count",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_group_set",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_set",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_set",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_input_enable",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_get",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_get",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_get",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pctl_get_group_pins",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pctl_get_group_name",
        "drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pctl_get_groups_count",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_gpio_request_enable",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_set_mux",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_set_mode",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_get_func_groups",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_get_group_pins",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_get_group_name",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_get_groups_count",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_dt_node_to_map",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_get",
        "drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_gpio_set_direction",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_gpio_set_direction",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_gpio_request_enable",
        "drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_set_mux",
        "drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set",
        "drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get",
        "drivers/soc/tegra/pmc.c:tegra_io_pad_pinctrl_get_group_pins",
        "drivers/soc/tegra/pmc.c:tegra_io_pad_pinctrl_get_group_name",
        "drivers/soc/tegra/pmc.c:tegra_io_pad_pinctrl_get_groups_count",
        "drivers/rtc/rtc-omap.c:rtc_pinconf_set",
        "drivers/rtc/rtc-omap.c:rtc_pinconf_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229799568,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290697888,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:86",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinconf_set",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinconf_get",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_set_direction",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_request_enable",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_func_groups",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_func_name",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_funcs_count",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_group_pins",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_group_name",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_groups_count",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_set",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_set_mux",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_func_groups",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_func_name",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_funcs_count",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_group_pins",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_group_name",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_groups_count",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set",
        "drivers/pinctrl/pinctrl-single.c:pcs_pinconf_get",
        "drivers/pinctrl/pinctrl-single.c:pcs_request_gpio",
        "drivers/pinctrl/pinctrl-single.c:pcs_set_mux",
        "drivers/pinctrl/pinctrl-single.c:pcs_get_function",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_free_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_pin_dbg_show",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pctl_get_group_pins",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pctl_get_group_name",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pctl_get_groups_count",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_request_enable",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set_direction",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinmux_set_mux",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_get_function_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290697888,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275412612,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:86",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinconf_set",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinconf_get",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_set_direction",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_request_enable",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_func_groups",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_func_name",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_funcs_count",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_group_pins",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_group_name",
        "drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_get_groups_count",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_set",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_set_mux",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_func_groups",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_func_name",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_funcs_count",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_group_pins",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_group_name",
        "drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_get_groups_count",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_pinconf_set",
        "drivers/pinctrl/pinctrl-single.c:pcs_pinconf_get",
        "drivers/pinctrl/pinctrl-single.c:pcs_request_gpio",
        "drivers/pinctrl/pinctrl-single.c:pcs_set_mux",
        "drivers/pinctrl/pinctrl-single.c:pcs_get_function",
        "drivers/pinctrl/pinctrl-single.c:pcs_dt_free_map",
        "drivers/pinctrl/pinctrl-single.c:pcs_pin_dbg_show",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pctl_get_group_pins",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pctl_get_group_name",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pctl_get_groups_count",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_request_enable",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_gpio_set_direction",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinmux_set_mux",
        "drivers/pinctrl/pinctrl-ocelot.c:ocelot_get_function_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275412612,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584445536,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:86",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445536,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584381216,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:86",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584381216,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584428448,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:86",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584428448,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
void * pinctrl_dev_get_drvdata(struct pinctrl_dev * pctldev)
```

```json
{
  "name": "pinctrl_dev_get_drvdata",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534576,
      "name": "pinctrl_dev_get_drvdata",
      "external": true,
      "loc": "drivers/pinctrl/core.c:86",
      "file": "drivers/pinctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_group_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_set",
        "drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_group_name",
        "drivers/pinctrl/pinctrl-amd.c:amd_get_groups_count",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_set",
        "drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_set",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_mux",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_function_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_pins",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_group_name",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_get_groups_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_group_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_set_direction",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_disable_free",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_request_enable",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinmux_set_mux",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_groups",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_function_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_functions_count",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pin_dbg_show",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_group_name",
        "drivers/pinctrl/intel/pinctrl-cherryview.c:chv_get_groups_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534576,
      "name": "pinctrl_dev_get_drvdata",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
