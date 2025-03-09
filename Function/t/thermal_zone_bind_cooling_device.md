# Function: <code>thermal_zone_bind_cooling_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585688864,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1258",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:passive_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585688864,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1167
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586085312,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:1264",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:passive_store",
        "drivers/thermal/thermal_core.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586085312,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1187
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586276144,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:638",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276144,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1187
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586373888,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:674",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586373888,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1102
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586838320,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:674",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586838320,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1108
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587130640,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:671",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587130640,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1077
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587307056,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:675",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587307056,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1078
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587577456,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:681",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587577456,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1095
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587780816,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:681",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587780816,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1095
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588629280,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:669",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588629280,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1095
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588648864,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:737",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588648864,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1095
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588533184,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:671",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588533184,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1104
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589207152,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:618",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589207152,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1104
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590671264,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:620",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590671264,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1079
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592340128,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:611",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592340128,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592767328,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:606",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592767328,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1005
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip_index, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593524720,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:761",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593524720,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500980184,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:681",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception",
        "drivers/thermal/of-thermal.c:of_thermal_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500980184,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 984
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233493604,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:681",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception",
        "drivers/thermal/of-thermal.c:of_thermal_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233493604,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294460960,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:681",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception",
        "drivers/thermal/of-thermal.c:of_thermal_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294460960,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1428
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277737706,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:681",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception",
        "drivers/thermal/of-thermal.c:of_thermal_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277737706,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 810
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587411792,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:681",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587411792,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1095
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587180000,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:681",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587180000,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1095
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587736960,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:681",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587736960,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1095
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device * tz, int trip, struct thermal_cooling_device * cdev, long unsigned int upper, long unsigned int lower, unsigned int weight)
```

```json
{
  "name": "thermal_zone_bind_cooling_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587850112,
      "name": "thermal_zone_bind_cooling_device",
      "external": true,
      "loc": "drivers/thermal/thermal_core.c:681",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb",
        "drivers/thermal/thermal_core.c:__bind",
        "drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587850112,
      "name": "thermal_zone_bind_cooling_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1095
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int trip_index</code>
</li>
<li>
<b>Param removed. </b>
<code>int trip</code>
</li>
</ul>
</details>
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
