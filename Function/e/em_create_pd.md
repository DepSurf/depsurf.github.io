# Function: <code>em_create_pd</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct em_perf_domain * em_create_pd(cpumask_t * span, int nr_states, struct em_data_callback * cb)
```

```json
{
  "name": "em_create_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "em_create_pd",
      "external": false,
      "loc": "kernel/power/energy_model.c:81",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010960,
      "name": "em_create_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
    },
    {
      "addr": 18446744071580011813,
      "name": "em_create_pd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int em_create_pd(struct device * dev, int nr_states, struct em_data_callback * cb, cpumask_t * cpus)
```

```json
{
  "name": "em_create_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579989616,
      "name": "em_create_pd",
      "external": false,
      "loc": "kernel/power/energy_model.c:187",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989616,
      "name": "em_create_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int em_create_pd(struct device * dev, int nr_states, struct em_data_callback * cb, cpumask_t * cpus)
```

```json
{
  "name": "em_create_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991088,
      "name": "em_create_pd",
      "external": false,
      "loc": "kernel/power/energy_model.c:187",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991088,
      "name": "em_create_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
int em_create_pd(struct device * dev, int nr_states, struct em_data_callback * cb, cpumask_t * cpus)
```

```json
{
  "name": "em_create_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580123024,
      "name": "em_create_pd",
      "external": false,
      "loc": "kernel/power/energy_model.c:182",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123024,
      "name": "em_create_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int em_create_pd(struct device * dev, int nr_states, struct em_data_callback * cb, cpumask_t * cpus, long unsigned int flags)
```

```json
{
  "name": "em_create_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "em_create_pd",
      "external": false,
      "loc": "kernel/power/energy_model.c:198",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580264128,
      "name": "em_create_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071593903143,
      "name": "em_create_pd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int em_create_pd(struct device * dev, int nr_states, struct em_data_callback * cb, cpumask_t * cpus, long unsigned int flags)
```

```json
{
  "name": "em_create_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580469984,
      "name": "em_create_pd",
      "external": false,
      "loc": "kernel/power/energy_model.c:195",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469984,
      "name": "em_create_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int em_create_pd(struct device * dev, int nr_states, struct em_data_callback * cb, cpumask_t * cpus, long unsigned int flags)
```

```json
{
  "name": "em_create_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "em_create_pd",
      "external": false,
      "loc": "kernel/power/energy_model.c:195",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541456,
      "name": "em_create_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
    },
    {
      "addr": 18446744071596503201,
      "name": "em_create_pd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int em_create_pd(struct device * dev, int nr_states, struct em_data_callback * cb, cpumask_t * cpus, long unsigned int flags)
```

```json
{
  "name": "em_create_pd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "em_create_pd",
      "external": false,
      "loc": "kernel/power/energy_model.c:195",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_dev_register_perf_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603264,
      "name": "em_create_pd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071597400888,
      "name": "em_create_pd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct em_perf_domain * em_create_pd(cpumask_t * span, int nr_states, struct em_data_callback * cb)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param added. </b>
<code>cpumask_t * cpus</code>
</li>
<li>
<b>Param removed. </b>
<code>cpumask_t * span</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct em_perf_domain *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
</ul>
</details>
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
