# Struct: <code>lb_env</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum group_type src_grp_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum group_type src_grp_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum group_type src_grp_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum migration_type migration_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum migration_type migration_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum migration_type migration_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum migration_type migration_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum migration_type migration_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum migration_type migration_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum migration_type migration_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum migration_type migration_type;
    struct list_head tasks;
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
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum group_type src_grp_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum group_type src_grp_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum group_type src_grp_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum group_type src_grp_type;
    struct list_head tasks;
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
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum group_type src_grp_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum group_type src_grp_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum group_type src_grp_type;
    struct list_head tasks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct lb_env {
    struct sched_domain * sd;
    struct rq * src_rq;
    int src_cpu;
    int dst_cpu;
    struct rq * dst_rq;
    struct cpumask * dst_grpmask;
    int new_dst_cpu;
    enum cpu_idle_type idle;
    long int imbalance;
    struct cpumask * cpus;
    unsigned int flags;
    unsigned int loop;
    unsigned int loop_break;
    unsigned int loop_max;
    enum fbq_type fbq_type;
    enum group_type src_grp_type;
    struct list_head tasks;
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum group_type src_grp_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum migration_type migration_type</code>
</li>
<li>
<b>Field removed. </b>
<code>enum group_type src_grp_type</code>
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
