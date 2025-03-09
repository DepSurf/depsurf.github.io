# Function: <code>allocate_power</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585701180,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586097936,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586097936,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1886
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586298416,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586298416,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1886
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586397360,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586397360,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1921
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586860656,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586860656,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1929
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587154256,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587154256,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1874
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587334768,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587334768,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1885
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587605392,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587605392,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1945
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587808928,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808928,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1945
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588656880,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/gov_power_allocator.c:332",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588656880,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1063
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588684640,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/gov_power_allocator.c:382",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588684640,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1129
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588566912,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/gov_power_allocator.c:383",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588566912,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1361
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589241264,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/gov_power_allocator.c:383",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589241264,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1358
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590706848,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/gov_power_allocator.c:383",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590706848,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1440
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592377856,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/gov_power_allocator.c:382",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592377856,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1407
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592805856,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/gov_power_allocator.c:381",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592805856,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1407
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593555120,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/gov_power_allocator.c:398",
      "file": "drivers/thermal/gov_power_allocator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/gov_power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593555120,
      "name": "allocate_power.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1093
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501015368,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501015368,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1904
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233527344,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233527344,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2208
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294496336,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294496336,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2332
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277763266,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277763266,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1566
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587439904,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587439904,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1945
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587208112,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587208112,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1945
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587765072,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587765072,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1945
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
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```

```json
{
  "name": "allocate_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587878336,
      "name": "allocate_power",
      "external": false,
      "loc": "drivers/thermal/power_allocator.c:332",
      "file": "drivers/thermal/power_allocator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/power_allocator.c:power_allocator_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587878336,
      "name": "allocate_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1990
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```
</details>
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
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int allocate_power(struct thermal_zone_device * tz, int control_temp)
```
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
