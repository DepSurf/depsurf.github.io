# Function: <code>em_dev_register_perf_domain</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int em_dev_register_perf_domain(struct device * dev, unsigned int nr_states, struct em_data_callback * cb, cpumask_t * cpus, bool milliwatts)
```

```json
{
  "name": "em_dev_register_perf_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "em_dev_register_perf_domain",
      "external": true,
      "loc": "kernel/power/energy_model.c:281",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591301313,
      "name": "em_dev_register_perf_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071579989920,
      "name": "em_dev_register_perf_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int em_dev_register_perf_domain(struct device * dev, unsigned int nr_states, struct em_data_callback * cb, cpumask_t * cpus, bool milliwatts)
```

```json
{
  "name": "em_dev_register_perf_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "em_dev_register_perf_domain",
      "external": true,
      "loc": "kernel/power/energy_model.c:281",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591244078,
      "name": "em_dev_register_perf_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071579991392,
      "name": "em_dev_register_perf_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int em_dev_register_perf_domain(struct device * dev, unsigned int nr_states, struct em_data_callback * cb, cpumask_t * cpus, bool milliwatts)
```

```json
{
  "name": "em_dev_register_perf_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "em_dev_register_perf_domain",
      "external": true,
      "loc": "kernel/power/energy_model.c:276",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592132474,
      "name": "em_dev_register_perf_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071580123328,
      "name": "em_dev_register_perf_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
int em_dev_register_perf_domain(struct device * dev, unsigned int nr_states, struct em_data_callback * cb, cpumask_t * cpus, bool microwatts)
```

```json
{
  "name": "em_dev_register_perf_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "em_dev_register_perf_domain",
      "external": true,
      "loc": "kernel/power/energy_model.c:340",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593903169,
      "name": "em_dev_register_perf_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071580264480,
      "name": "em_dev_register_perf_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
int em_dev_register_perf_domain(struct device * dev, unsigned int nr_states, struct em_data_callback * cb, cpumask_t * cpus, bool microwatts)
```

```json
{
  "name": "em_dev_register_perf_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580470384,
      "name": "em_dev_register_perf_domain",
      "external": true,
      "loc": "kernel/power/energy_model.c:337",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470384,
      "name": "em_dev_register_perf_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1011
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
int em_dev_register_perf_domain(struct device * dev, unsigned int nr_states, struct em_data_callback * cb, cpumask_t * cpus, bool microwatts)
```

```json
{
  "name": "em_dev_register_perf_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580541968,
      "name": "em_dev_register_perf_domain",
      "external": true,
      "loc": "kernel/power/energy_model.c:337",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541968,
      "name": "em_dev_register_perf_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1010
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
int em_dev_register_perf_domain(struct device * dev, unsigned int nr_states, struct em_data_callback * cb, cpumask_t * cpus, bool microwatts)
```

```json
{
  "name": "em_dev_register_perf_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580603856,
      "name": "em_dev_register_perf_domain",
      "external": true,
      "loc": "kernel/power/energy_model.c:337",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603856,
      "name": "em_dev_register_perf_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1010
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
int em_dev_register_perf_domain(struct device * dev, unsigned int nr_states, struct em_data_callback * cb, cpumask_t * cpus, bool milliwatts)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool microwatts</code>
</li>
<li>
<b>Param removed. </b>
<code>bool milliwatts</code>
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
