# Function: <code>fwnode_property_read_string_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fwnode_property_read_string_array(struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584420272,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:589",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584420272,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int fwnode_property_read_string_array(struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584755536,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:596",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584755536,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int fwnode_property_read_string_array(struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584945760,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:596",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584945760,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int fwnode_property_read_string_array(struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585030976,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:574",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585030976,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585453744,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:583",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:device_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585453744,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585696016,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:644",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585696016,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585826304,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585826304,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586061888,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586061888,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586209776,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586209776,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586973280,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973280,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587058976,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587058976,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586942816,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586942816,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587507136,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587507136,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588832384,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:401",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588832384,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590333152,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:408",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590333152,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590653168,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:412",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590653168,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591013312,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:412",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_property_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591013312,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499015040,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499015040,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231578372,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231578372,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292176784,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292176784,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276383616,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276383616,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585969984,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585969984,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585819248,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819248,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586159792,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586159792,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int fwnode_property_read_string_array(const struct fwnode_handle * fwnode, const char * propname, const char * * val, size_t nval)
```

```json
{
  "name": "fwnode_property_read_string_array",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586268496,
      "name": "fwnode_property_read_string_array",
      "external": true,
      "loc": "drivers/base/property.c:369",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_get_phy_mode",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:fwnode_property_match_string",
        "drivers/base/property.c:device_property_read_string",
        "drivers/base/property.c:device_property_read_string_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586268496,
      "name": "fwnode_property_read_string_array",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle * fwnode</code> ➡️ <code>const struct fwnode_handle * fwnode</code>
</li>
</ul>
</details>
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
