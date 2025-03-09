# Function: <code>em_create_perf_table</code>

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
int em_create_perf_table(struct device * dev, struct em_perf_domain * pd, int nr_states, struct em_data_callback * cb)
```

```json
{
  "name": "em_create_perf_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "em_create_perf_table",
      "external": false,
      "loc": "kernel/power/energy_model.c:107",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_create_pd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579989152,
      "name": "em_create_perf_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071591301237,
      "name": "em_create_perf_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int em_create_perf_table(struct device * dev, struct em_perf_domain * pd, int nr_states, struct em_data_callback * cb)
```

```json
{
  "name": "em_create_perf_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "em_create_perf_table",
      "external": false,
      "loc": "kernel/power/energy_model.c:107",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_create_pd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990624,
      "name": "em_create_perf_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
    },
    {
      "addr": 18446744071591244002,
      "name": "em_create_perf_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int em_create_perf_table(struct device * dev, struct em_perf_domain * pd, int nr_states, struct em_data_callback * cb)
```

```json
{
  "name": "em_create_perf_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "em_create_perf_table",
      "external": false,
      "loc": "kernel/power/energy_model.c:107",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_create_pd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122560,
      "name": "em_create_perf_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
    },
    {
      "addr": 18446744071592132402,
      "name": "em_create_perf_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int em_create_perf_table(struct device * dev, struct em_perf_domain * pd, int nr_states, struct em_data_callback * cb, long unsigned int flags)
```

```json
{
  "name": "em_create_perf_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "em_create_perf_table",
      "external": false,
      "loc": "kernel/power/energy_model.c:109",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_create_pd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263504,
      "name": "em_create_perf_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
    },
    {
      "addr": 18446744071593902998,
      "name": "em_create_perf_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int em_create_perf_table(struct device * dev, struct em_perf_domain * pd, int nr_states, struct em_data_callback * cb, long unsigned int flags)
```

```json
{
  "name": "em_create_perf_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580469216,
      "name": "em_create_perf_table",
      "external": false,
      "loc": "kernel/power/energy_model.c:106",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_create_pd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469216,
      "name": "em_create_perf_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 752
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
int em_create_perf_table(struct device * dev, struct em_perf_domain * pd, int nr_states, struct em_data_callback * cb, long unsigned int flags)
```

```json
{
  "name": "em_create_perf_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580540672,
      "name": "em_create_perf_table",
      "external": false,
      "loc": "kernel/power/energy_model.c:106",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_create_pd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540672,
      "name": "em_create_perf_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
int em_create_perf_table(struct device * dev, struct em_perf_domain * pd, int nr_states, struct em_data_callback * cb, long unsigned int flags)
```

```json
{
  "name": "em_create_perf_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580602480,
      "name": "em_create_perf_table",
      "external": false,
      "loc": "kernel/power/energy_model.c:106",
      "file": "kernel/power/energy_model.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/energy_model.c:em_create_pd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602480,
      "name": "em_create_perf_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
int em_create_perf_table(struct device * dev, struct em_perf_domain * pd, int nr_states, struct em_data_callback * cb)
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
