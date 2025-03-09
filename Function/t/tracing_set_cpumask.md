# Function: <code>tracing_set_cpumask</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int tracing_set_cpumask(struct trace_array * tr, cpumask_var_t tracing_cpumask_new)
```

```json
{
  "name": "tracing_set_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580694864,
      "name": "tracing_set_cpumask",
      "external": true,
      "loc": "kernel/trace/trace.c:4657",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580694864,
      "name": "tracing_set_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int tracing_set_cpumask(struct trace_array * tr, cpumask_var_t tracing_cpumask_new)
```

```json
{
  "name": "tracing_set_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685664,
      "name": "tracing_set_cpumask",
      "external": true,
      "loc": "kernel/trace/trace.c:4725",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685664,
      "name": "tracing_set_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int tracing_set_cpumask(struct trace_array * tr, cpumask_var_t tracing_cpumask_new)
```

```json
{
  "name": "tracing_set_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580689808,
      "name": "tracing_set_cpumask",
      "external": true,
      "loc": "kernel/trace/trace.c:5063",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580689808,
      "name": "tracing_set_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int tracing_set_cpumask(struct trace_array * tr, cpumask_var_t tracing_cpumask_new)
```

```json
{
  "name": "tracing_set_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865024,
      "name": "tracing_set_cpumask",
      "external": true,
      "loc": "kernel/trace/trace.c:5137",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865024,
      "name": "tracing_set_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
int tracing_set_cpumask(struct trace_array * tr, cpumask_var_t tracing_cpumask_new)
```

```json
{
  "name": "tracing_set_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581094768,
      "name": "tracing_set_cpumask",
      "external": true,
      "loc": "kernel/trace/trace.c:5138",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094768,
      "name": "tracing_set_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int tracing_set_cpumask(struct trace_array * tr, cpumask_var_t tracing_cpumask_new)
```

```json
{
  "name": "tracing_set_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402480,
      "name": "tracing_set_cpumask",
      "external": true,
      "loc": "kernel/trace/trace.c:5162",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402480,
      "name": "tracing_set_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
int tracing_set_cpumask(struct trace_array * tr, cpumask_var_t tracing_cpumask_new)
```

```json
{
  "name": "tracing_set_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_set_cpumask",
      "external": true,
      "loc": "kernel/trace/trace.c:5268",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596523711,
      "name": "tracing_set_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581497296,
      "name": "tracing_set_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int tracing_set_cpumask(struct trace_array * tr, cpumask_var_t tracing_cpumask_new)
```

```json
{
  "name": "tracing_set_cpumask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tracing_set_cpumask",
      "external": true,
      "loc": "kernel/trace/trace.c:5286",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597424463,
      "name": "tracing_set_cpumask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581608672,
      "name": "tracing_set_cpumask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int tracing_set_cpumask(struct trace_array * tr, cpumask_var_t tracing_cpumask_new)
```
</details>
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
