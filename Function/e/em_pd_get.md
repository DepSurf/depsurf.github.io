# Function: <code>em_pd_get</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct em_perf_domain * em_pd_get(struct device * dev)
```

```json
{
  "name": "em_pd_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579990171,
      "name": "em_pd_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:230",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988320,
      "name": "em_pd_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct em_perf_domain * em_pd_get(struct device * dev)
```

```json
{
  "name": "em_pd_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579991907,
      "name": "em_pd_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:230",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990160,
      "name": "em_pd_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct em_perf_domain * em_pd_get(struct device * dev)
```

```json
{
  "name": "em_pd_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580123843,
      "name": "em_pd_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:225",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122096,
      "name": "em_pd_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct em_perf_domain * em_pd_get(struct device * dev)
```

```json
{
  "name": "em_pd_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580264775,
      "name": "em_pd_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:289",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580262992,
      "name": "em_pd_get",
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
struct em_perf_domain * em_pd_get(struct device * dev)
```

```json
{
  "name": "em_pd_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580471218,
      "name": "em_pd_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:286",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468576,
      "name": "em_pd_get",
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
struct em_perf_domain * em_pd_get(struct device * dev)
```

```json
{
  "name": "em_pd_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580542801,
      "name": "em_pd_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:286",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540032,
      "name": "em_pd_get",
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
struct em_perf_domain * em_pd_get(struct device * dev)
```

```json
{
  "name": "em_pd_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580604689,
      "name": "em_pd_get",
      "external": true,
      "loc": "kernel/power/energy_model.c:286",
      "file": "kernel/power/energy_model.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ],
      "caller_func": [
        "drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580601840,
      "name": "em_pd_get",
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct em_perf_domain * em_pd_get(struct device * dev)
```
</details>
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
