# Struct: <code>pstate_funcs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    void (*)(struct cpudata *, int) set;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
    int32_t (*)(struct cpudata *) get_target_pstate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
    int32_t (*)(struct cpudata *) get_target_pstate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
    void (*)(struct update_util_data *, u64, unsigned int) update_util;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)(int) get_cpu_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)(int) get_cpu_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)(int) get_max;
    int (*)(int) get_max_physical;
    int (*)(int) get_min;
    int (*)(int) get_turbo;
    int (*)() get_scaling;
    int (*)(int) get_cpu_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)(int) get_max;
    int (*)(int) get_max_physical;
    int (*)(int) get_min;
    int (*)(int) get_turbo;
    int (*)() get_scaling;
    int (*)(int) get_cpu_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)(int) get_max;
    int (*)(int) get_max_physical;
    int (*)(int) get_min;
    int (*)(int) get_turbo;
    int (*)() get_scaling;
    int (*)(int) get_cpu_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 (*)(struct cpudata *, int) get_val</code>
</li>
<li>
<b>Field added. </b>
<code>int32_t (*)(struct cpudata *) get_target_pstate</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct cpudata *, int) set</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)() get_aperf_mperf_shift</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct update_util_data *, u64, unsigned int) update_util</code>
</li>
<li>
<b>Field removed. </b>
<code>int32_t (*)(struct cpudata *) get_target_pstate</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(struct update_util_data *, u64, unsigned int) update_util</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(int) get_cpu_scaling</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)() get_max</code> ➡️ <code>int (*)(int) get_max</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)() get_max_physical</code> ➡️ <code>int (*)(int) get_max_physical</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)() get_min</code> ➡️ <code>int (*)(int) get_min</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)() get_turbo</code> ➡️ <code>int (*)(int) get_turbo</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct pstate_funcs {
    int (*)() get_max;
    int (*)() get_max_physical;
    int (*)() get_min;
    int (*)() get_turbo;
    int (*)() get_scaling;
    int (*)() get_aperf_mperf_shift;
    u64 (*)(struct cpudata *, int) get_val;
    void (*)(struct cpudata *) get_vid;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
