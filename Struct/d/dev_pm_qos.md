# Struct: <code>dev_pm_qos</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_constraints min_frequency;
    struct pm_qos_constraints max_frequency;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
    struct dev_pm_qos_request * min_frequency_req;
    struct dev_pm_qos_request * max_frequency_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct freq_constraints freq;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct freq_constraints freq;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct freq_constraints freq;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct freq_constraints freq;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct freq_constraints freq;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct freq_constraints freq;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct freq_constraints freq;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct freq_constraints freq;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dev_pm_qos {
    struct pm_qos_constraints resume_latency;
    struct pm_qos_constraints latency_tolerance;
    struct pm_qos_flags flags;
    struct dev_pm_qos_request * resume_latency_req;
    struct dev_pm_qos_request * latency_tolerance_req;
    struct dev_pm_qos_request * flags_req;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct pm_qos_constraints min_frequency</code>
</li>
<li>
<b>Field added. </b>
<code>struct pm_qos_constraints max_frequency</code>
</li>
<li>
<b>Field added. </b>
<code>struct dev_pm_qos_request * min_frequency_req</code>
</li>
<li>
<b>Field added. </b>
<code>struct dev_pm_qos_request * max_frequency_req</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct pm_qos_constraints min_frequency</code>
</li>
<li>
<b>Field removed. </b>
<code>struct pm_qos_constraints max_frequency</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dev_pm_qos_request * min_frequency_req</code>
</li>
<li>
<b>Field removed. </b>
<code>struct dev_pm_qos_request * max_frequency_req</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct freq_constraints freq</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
