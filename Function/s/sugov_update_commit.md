# Function: <code>sugov_update_commit</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sugov_update_commit(struct sugov_policy * sg_policy, u64 time, unsigned int next_freq)
```

```json
{
  "name": "sugov_update_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579716432,
      "name": "sugov_update_commit",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:90",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716432,
      "name": "sugov_update_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void sugov_update_commit(struct sugov_policy * sg_policy, u64 time, unsigned int next_freq)
```

```json
{
  "name": "sugov_update_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579711104,
      "name": "sugov_update_commit",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:96",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711104,
      "name": "sugov_update_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void sugov_update_commit(struct sugov_policy * sg_policy, u64 time, unsigned int next_freq)
```

```json
{
  "name": "sugov_update_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579742800,
      "name": "sugov_update_commit",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:118",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/cpufreq_schedutil.c:sugov_update_shared",
        "kernel/sched/cpufreq_schedutil.c:sugov_update_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579742800,
      "name": "sugov_update_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void sugov_update_commit(struct sugov_policy * sg_policy, u64 time, unsigned int next_freq)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void sugov_update_commit(struct sugov_policy * sg_policy, u64 time, unsigned int next_freq)
```
</details>
</li>
</ul>
