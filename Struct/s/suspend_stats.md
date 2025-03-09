# Struct: <code>suspend_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    u64 last_hw_sleep;
    u64 total_hw_sleep;
    u64 max_hw_sleep;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    u64 last_hw_sleep;
    u64 total_hw_sleep;
    u64 max_hw_sleep;
    enum suspend_stat_step[2] failed_steps;
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
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
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
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct suspend_stats {
    int success;
    int fail;
    int failed_freeze;
    int failed_prepare;
    int failed_suspend;
    int failed_suspend_late;
    int failed_suspend_noirq;
    int failed_resume;
    int failed_resume_early;
    int failed_resume_noirq;
    int last_failed_dev;
    char[80] failed_devs;
    int last_failed_errno;
    int[2] errno;
    int last_failed_step;
    enum suspend_stat_step[2] failed_steps;
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 last_hw_sleep</code>
</li>
<li>
<b>Field added. </b>
<code>u64 total_hw_sleep</code>
</li>
<li>
<b>Field added. </b>
<code>u64 max_hw_sleep</code>
</li>
</ul>
</details>
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
