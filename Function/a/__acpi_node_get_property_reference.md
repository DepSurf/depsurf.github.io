# Function: <code>__acpi_node_get_property_reference</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct acpi_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584071603,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:559",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584071603,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
int __acpi_node_get_property_reference(struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct acpi_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584135984,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:575",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584135984,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct acpi_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584407472,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:580",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584407472,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct acpi_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584632560,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:580",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584632560,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584730432,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:653",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584730432,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584932240,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:671",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584932240,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585068048,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:671",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585068048,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585773088,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:671",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585773088,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585891392,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:664",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585891392,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585768416,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:664",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585768416,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586251328,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:664",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586251328,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587492688,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:671",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587492688,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588764560,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:882",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588764560,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 635
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589053440,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:882",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589053440,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 737
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589358976,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:913",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589358976,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497471680,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:671",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497471680,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584997536,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:671",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584997536,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584913120,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:671",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584913120,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585019632,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:671",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585019632,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```

```json
{
  "name": "__acpi_node_get_property_reference",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585125808,
      "name": "__acpi_node_get_property_reference",
      "external": true,
      "loc": "drivers/acpi/property.c:671",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup",
        "drivers/pwm/core.c:acpi_pwm_get",
        "drivers/acpi/property.c:acpi_fwnode_get_reference_args",
        "drivers/acpi/property.c:acpi_graph_get_remote_endpoint"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585125808,
      "name": "__acpi_node_get_property_reference",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int __acpi_node_get_property_reference(struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct acpi_reference_args * args)
```
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct acpi_reference_args * args</code> ➡️ <code>struct fwnode_reference_args * args</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle * fwnode, const char * propname, size_t index, size_t num_args, struct fwnode_reference_args * args)
```
</details>
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
