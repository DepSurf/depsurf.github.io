# Function: <code>__cpufreq_cooling_register</code>

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
struct thermal_cooling_device * __cpufreq_cooling_register(struct device_node * np, struct cpufreq_policy * policy, u32 capacitance)
```

```json
{
  "name": "__cpufreq_cooling_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501019352,
      "name": "__cpufreq_cooling_register",
      "external": false,
      "loc": "drivers/thermal/cpu_cooling.c:529",
      "file": "drivers/thermal/cpu_cooling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:of_cpufreq_cooling_register",
        "drivers/thermal/cpu_cooling.c:cpufreq_cooling_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501019352,
      "name": "__cpufreq_cooling_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1220
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
struct thermal_cooling_device * __cpufreq_cooling_register(struct device_node * np, struct cpufreq_policy * policy, u32 capacitance)
```

```json
{
  "name": "__cpufreq_cooling_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233531936,
      "name": "__cpufreq_cooling_register",
      "external": false,
      "loc": "drivers/thermal/cpu_cooling.c:529",
      "file": "drivers/thermal/cpu_cooling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:of_cpufreq_cooling_register",
        "drivers/thermal/cpu_cooling.c:cpufreq_cooling_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233531936,
      "name": "__cpufreq_cooling_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
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
struct thermal_cooling_device * __cpufreq_cooling_register(struct device_node * np, struct cpufreq_policy * policy, u32 capacitance)
```

```json
{
  "name": "__cpufreq_cooling_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294502480,
      "name": "__cpufreq_cooling_register",
      "external": false,
      "loc": "drivers/thermal/cpu_cooling.c:529",
      "file": "drivers/thermal/cpu_cooling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/thermal/cpu_cooling.c:of_cpufreq_cooling_register",
        "drivers/thermal/cpu_cooling.c:cpufreq_cooling_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294502480,
      "name": "__cpufreq_cooling_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1708
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
struct thermal_cooling_device * __cpufreq_cooling_register(struct device_node * np, struct cpufreq_policy * policy, u32 capacitance)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct thermal_cooling_device * __cpufreq_cooling_register(struct device_node * np, struct cpufreq_policy * policy, u32 capacitance)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct thermal_cooling_device * __cpufreq_cooling_register(struct device_node * np, struct cpufreq_policy * policy, u32 capacitance)
```
</details>
</li>
</ul>
