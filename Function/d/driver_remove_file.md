# Function: <code>driver_remove_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584401488,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:120",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_add_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/usb/core/driver.c:usb_register_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584401488,
      "name": "driver_remove_file",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584736832,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:120",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584736832,
      "name": "driver_remove_file",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584926704,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:120",
      "file": "drivers/base/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584926704,
      "name": "driver_remove_file",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585011824,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:120",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011824,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585434064,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:120",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585434064,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585677136,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:118",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585677136,
      "name": "driver_remove_file",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585807392,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:118",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585807392,
      "name": "driver_remove_file",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586040608,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:118",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586040608,
      "name": "driver_remove_file",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586188240,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:118",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586188240,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586949792,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:119",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949792,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587034864,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:119",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587034864,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586918656,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:119",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586918656,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587481072,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:119",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587481072,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588802592,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:188",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588802592,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590299472,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:194",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590299472,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590619680,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:194",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590619680,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590978784,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:194",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590978784,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498987096,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:118",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498987096,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231555732,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:118",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231555732,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292140096,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:118",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292140096,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276362858,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:118",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276362858,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585948608,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:118",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585948608,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585797664,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:118",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585797664,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586138256,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:118",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586138256,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void driver_remove_file(struct device_driver * drv, const struct driver_attribute * attr)
```

```json
{
  "name": "driver_remove_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586246944,
      "name": "driver_remove_file",
      "external": true,
      "loc": "drivers/base/driver.c:118",
      "file": "drivers/base/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_remove_driver",
        "drivers/base/bus.c:bus_add_driver",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_deregister",
        "drivers/usb/core/driver.c:usb_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586246944,
      "name": "driver_remove_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
