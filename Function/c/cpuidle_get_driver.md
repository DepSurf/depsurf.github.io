# Function: <code>cpuidle_get_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585906320,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:318",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_ref",
        "drivers/cpuidle/driver.c:cpuidle_driver_unref"
      ],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585906320,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586306773,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:318",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586305888,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586514501,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:319",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586513744,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586640117,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:320",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586639376,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587121493,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:288",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587120864,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587421061,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:288",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587420432,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587601669,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:288",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587601040,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587878437,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:288",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587877840,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588084405,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:312",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588083584,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588945280,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:318",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588945280,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588957520,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:318",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588957520,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588845920,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:322",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588845920,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589544240,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:322",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589544240,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591037200,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:322",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591037200,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592748416,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:322",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592748416,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593183072,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:326",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593183072,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593936896,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:326",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593936896,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501327584,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:312",
      "file": "drivers/cpuidle/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref",
        "drivers/cpuidle/sysfs.c:show_current_driver",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501327584,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233819096,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:312",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233817880,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294873804,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:312",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/cpuidle/sysfs.c:show_current_driver",
        "drivers/cpuidle/cpuidle-pseries.c:pseries_cpuidle_cpu_dead",
        "drivers/cpuidle/cpuidle-pseries.c:pseries_cpuidle_cpu_online",
        "drivers/cpuidle/cpuidle-powernv.c:powernv_cpuidle_cpu_dead",
        "drivers/cpuidle/cpuidle-powernv.c:powernv_cpuidle_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294872288,
      "name": "cpuidle_get_driver",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587706197,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:312",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705376,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587484485,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:312",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587483664,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588040549,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:312",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588039728,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct cpuidle_driver * cpuidle_get_driver()
```

```json
{
  "name": "cpuidle_get_driver",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588156341,
      "name": "cpuidle_get_driver",
      "external": true,
      "loc": "drivers/cpuidle/driver.c:312",
      "file": "drivers/cpuidle/driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:cpuidle_driver_unref",
        "drivers/cpuidle/driver.c:cpuidle_driver_ref"
      ],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_driver.c:__acpi_processor_start",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/cpuidle/sysfs.c:show_current_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588155456,
      "name": "cpuidle_get_driver",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cpuidle_driver * cpuidle_get_driver()
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
