# Function: <code>device_remove_groups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584376142,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:463",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/bus.c:bus_remove_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382432,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584719777,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:463",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584717376,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584909968,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1029",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584906512,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584995278,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1027",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584991648,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585417172,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1031",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585404992,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585659816,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1073",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585647472,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585786075,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1147",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776896,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586016914,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1292",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586009744,
      "name": "device_remove_groups",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586164626,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1329",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586156608,
      "name": "device_remove_groups",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586923203,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1807",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586914064,
      "name": "device_remove_groups",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586999392,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:2208",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586998240,
      "name": "device_remove_groups",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586881824,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:2420",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586880672,
      "name": "device_remove_groups",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587443457,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:2476",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:__device_release_driver",
        "drivers/base/dd.c:really_probe",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587442208,
      "name": "device_remove_groups",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588764925,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:2487",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759184,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590255821,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:2724",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590247952,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590574829,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:2730",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590567984,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590933229,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:2745",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs",
        "drivers/base/core.c:device_add_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590926384,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498959712,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1329",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498950440,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231530264,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1329",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231521848,
      "name": "device_remove_groups",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292104520,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1329",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292092144,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276341354,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1329",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276333936,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585924994,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1329",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585916976,
      "name": "device_remove_groups",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585774130,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1329",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585766112,
      "name": "device_remove_groups",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586114642,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1329",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586106624,
      "name": "device_remove_groups",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void device_remove_groups(struct device * dev, const struct attribute_group * * groups)
```

```json
{
  "name": "device_remove_groups",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586222450,
      "name": "device_remove_groups",
      "external": true,
      "loc": "drivers/base/core.c:1329",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_add",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs",
        "drivers/base/core.c:device_remove_attrs"
      ],
      "caller_func": [
        "drivers/base/bus.c:bus_remove_device",
        "drivers/base/bus.c:bus_add_device",
        "drivers/base/dd.c:device_release_driver_internal",
        "drivers/leds/led-triggers.c:led_trigger_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586215232,
      "name": "device_remove_groups",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
