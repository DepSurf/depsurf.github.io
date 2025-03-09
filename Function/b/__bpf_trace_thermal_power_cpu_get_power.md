# Function: <code>__bpf_trace_thermal_power_cpu_get_power</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __bpf_trace_thermal_power_cpu_get_power(void * __data, const struct cpumask * cpus, long unsigned int freq, u32 * load, size_t load_len, u32 dynamic_power)
```

```json
{
  "name": "__bpf_trace_thermal_power_cpu_get_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500979440,
      "name": "__bpf_trace_thermal_power_cpu_get_power",
      "external": false,
      "loc": "include/trace/events/thermal.h:95",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500979440,
      "name": "__bpf_trace_thermal_power_cpu_get_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void __bpf_trace_thermal_power_cpu_get_power(void * __data, const struct cpumask * cpus, long unsigned int freq, u32 * load, size_t load_len, u32 dynamic_power)
```

```json
{
  "name": "__bpf_trace_thermal_power_cpu_get_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233492700,
      "name": "__bpf_trace_thermal_power_cpu_get_power",
      "external": false,
      "loc": "include/trace/events/thermal.h:95",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233492700,
      "name": "__bpf_trace_thermal_power_cpu_get_power",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __bpf_trace_thermal_power_cpu_get_power(void * __data, const struct cpumask * cpus, long unsigned int freq, u32 * load, size_t load_len, u32 dynamic_power)
```

```json
{
  "name": "__bpf_trace_thermal_power_cpu_get_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294448000,
      "name": "__bpf_trace_thermal_power_cpu_get_power",
      "external": false,
      "loc": "include/trace/events/thermal.h:95",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294448000,
      "name": "__bpf_trace_thermal_power_cpu_get_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void __bpf_trace_thermal_power_cpu_get_power(void * __data, const struct cpumask * cpus, long unsigned int freq, u32 * load, size_t load_len, u32 dynamic_power)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void __bpf_trace_thermal_power_cpu_get_power(void * __data, const struct cpumask * cpus, long unsigned int freq, u32 * load, size_t load_len, u32 dynamic_power)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void __bpf_trace_thermal_power_cpu_get_power(void * __data, const struct cpumask * cpus, long unsigned int freq, u32 * load, size_t load_len, u32 dynamic_power)
```
</details>
</li>
</ul>
