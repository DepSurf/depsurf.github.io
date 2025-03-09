# Function: <code>cpufreq_cpu_get_raw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585851232,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:241",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline_prepare",
        "drivers/cpufreq/cpufreq.c:cpufreq_resume"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq_conservative.c:dbs_cpufreq_notifier",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585851232,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586259432,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:195",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586250944,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586466392,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:195",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586455712,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586590954,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:195",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586580240,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587074202,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:201",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587063520,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587372202,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:185",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361744,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587552042,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:185",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587541616,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587816624,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:177",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587816624,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588021824,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:180",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588021824,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588889152,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:185",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588889152,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588900608,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:185",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588900608,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588789168,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:182",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588789168,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589481984,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:182",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589481984,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590955264,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:183",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590955264,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592657744,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:183",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592657744,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593088480,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:188",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593088480,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593840848,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:189",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpuhp_cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593840848,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501294636,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:180",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501284440,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233783232,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:180",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233774880,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294822284,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:180",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294810288,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587646816,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:180",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587646816,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587420688,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:180",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587420688,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587977968,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:180",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587977968,
      "name": "cpufreq_cpu_get_raw",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
```

```json
{
  "name": "cpufreq_cpu_get_raw",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093344,
      "name": "cpufreq_cpu_get_raw",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq.c:180",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_offline",
        "drivers/cpufreq/cpufreq.c:cpufreq_cpu_get",
        "drivers/cpufreq/cpufreq.c:cpufreq_generic_get",
        "drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093344,
      "name": "cpufreq_cpu_get_raw",
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
struct cpufreq_policy * cpufreq_cpu_get_raw(unsigned int cpu)
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
