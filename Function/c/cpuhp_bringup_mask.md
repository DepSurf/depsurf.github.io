# Function: <code>cpuhp_bringup_mask</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void cpuhp_bringup_mask(const struct cpumask * mask, unsigned int ncpus, enum cpuhp_state target)
```

```json
{
  "name": "cpuhp_bringup_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619517344,
      "name": "cpuhp_bringup_mask",
      "external": false,
      "loc": "kernel/cpu.c:1787",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:bringup_nonboot_cpus",
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel",
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel",
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel",
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619517344,
      "name": "cpuhp_bringup_mask",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 201
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
void cpuhp_bringup_mask(const struct cpumask * mask, unsigned int ncpus, enum cpuhp_state target)
```

```json
{
  "name": "cpuhp_bringup_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621814288,
      "name": "cpuhp_bringup_mask",
      "external": false,
      "loc": "kernel/cpu.c:1822",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:bringup_nonboot_cpus",
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel",
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel",
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel",
        "kernel/cpu.c:cpuhp_bringup_cpus_parallel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621814288,
      "name": "cpuhp_bringup_mask",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 201
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void cpuhp_bringup_mask(const struct cpumask * mask, unsigned int ncpus, enum cpuhp_state target)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
