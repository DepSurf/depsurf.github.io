# Function: <code>get_target_freq_with_cpufreq</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_target_freq_with_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591258232,
      "name": "get_target_freq_with_cpufreq",
      "external": false,
      "loc": "drivers/devfreq/governor_passive.c:77",
      "file": "drivers/devfreq/governor_passive.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int get_target_freq_with_cpufreq(struct devfreq * devfreq, long unsigned int * target_freq)
```

```json
{
  "name": "get_target_freq_with_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593013056,
      "name": "get_target_freq_with_cpufreq",
      "external": false,
      "loc": "drivers/devfreq/governor_passive.c:77",
      "file": "drivers/devfreq/governor_passive.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593013056,
      "name": "get_target_freq_with_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
int get_target_freq_with_cpufreq(struct devfreq * devfreq, long unsigned int * target_freq)
```

```json
{
  "name": "get_target_freq_with_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593464608,
      "name": "get_target_freq_with_cpufreq",
      "external": false,
      "loc": "drivers/devfreq/governor_passive.c:77",
      "file": "drivers/devfreq/governor_passive.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593464608,
      "name": "get_target_freq_with_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
int get_target_freq_with_cpufreq(struct devfreq * devfreq, long unsigned int * target_freq)
```

```json
{
  "name": "get_target_freq_with_cpufreq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594211696,
      "name": "get_target_freq_with_cpufreq",
      "external": false,
      "loc": "drivers/devfreq/governor_passive.c:77",
      "file": "drivers/devfreq/governor_passive.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594211696,
      "name": "get_target_freq_with_cpufreq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int get_target_freq_with_cpufreq(struct devfreq * devfreq, long unsigned int * target_freq)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
