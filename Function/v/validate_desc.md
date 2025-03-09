# Function: <code>validate_desc</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2306",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_is_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_debounce",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115632,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071584136568,
      "name": "validate_desc.cold.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2334",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_debounce",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584198896,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071584222200,
      "name": "validate_desc.cold.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2398",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_is_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_debounce",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387424,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071584410858,
      "name": "validate_desc.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2730",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_is_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_debounce",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523600,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071584547295,
      "name": "validate_desc.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585204053,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3097",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_config",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread",
        "drivers/gpio/gpiolib.c:lineevent_ioctl",
        "drivers/gpio/gpiolib.c:linehandle_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189232,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585219058,
      "name": "validate_desc.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585360549,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1901",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_config",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585348256,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071591385621,
      "name": "validate_desc.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585244181,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1878",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_config",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232464,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071591328025,
      "name": "validate_desc.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585699765,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1900",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_config",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687760,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071592350693,
      "name": "validate_desc.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586866981,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1961",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_config",
        "drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns",
        "drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586854464,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071594212275,
      "name": "validate_desc.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588013749,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2031",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_config",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns",
        "drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587998592,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588288405,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2070",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_config",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns",
        "drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588273280,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588582167,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2253",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_config",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_disable_hw_timestamp_ns",
        "drivers/gpio/gpiolib.c:gpiod_enable_hw_timestamp_ns",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588565472,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496700432,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2730",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_is_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_debounce",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496700432,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229997352,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2730",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_is_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_debounce",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229997352,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290790304,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2730",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_is_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_debounce",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290790304,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275466970,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2730",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_is_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_debounce",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275466970,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2730",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_is_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_debounce",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584480528,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071584504223,
      "name": "validate_desc.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2730",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_is_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_debounce",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584418656,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071584442351,
      "name": "validate_desc.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2730",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_is_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_debounce",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475264,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071584498959,
      "name": "validate_desc.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```

```json
{
  "name": "validate_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "validate_desc",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2730",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/gpio/gpiolib.c:gpiod_set_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_consumer_name",
        "drivers/gpio/gpiolib.c:gpiod_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_get_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_value",
        "drivers/gpio/gpiolib.c:gpiod_toggle_active_low",
        "drivers/gpio/gpiolib.c:gpiod_is_active_low",
        "drivers/gpio/gpiolib.c:gpiod_set_transitory",
        "drivers/gpio/gpiolib.c:gpiod_set_debounce",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw",
        "drivers/gpio/gpiolib.c:gpiod_direction_input",
        "drivers/gpio/gpiolib.c:gpiod_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581392,
      "name": "validate_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071584605231,
      "name": "validate_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int validate_desc(const struct gpio_desc * desc, const char * func)
```
</details>
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
