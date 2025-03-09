# Struct: <code>root_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    bool overload;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    bool overload;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    bool overload;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    bool overload;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    bool overload;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    bool overload;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    u64 visit_gen;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    u64 visit_gen;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    u64 visit_gen;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    u64 visit_gen;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    u64 visit_gen;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    u64 visit_gen;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    u64 visit_gen;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
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
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
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
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct root_domain {
    atomic_t refcount;
    atomic_t rto_count;
    struct callback_head rcu;
    cpumask_var_t span;
    cpumask_var_t online;
    int overload;
    int overutilized;
    cpumask_var_t dlo_mask;
    atomic_t dlo_count;
    struct dl_bw dl_bw;
    struct cpudl cpudl;
    struct irq_work rto_push_work;
    raw_spinlock_t rto_lock;
    int rto_loop;
    int rto_cpu;
    atomic_t rto_loop_next;
    atomic_t rto_loop_start;
    cpumask_var_t rto_mask;
    struct cpupri cpupri;
    long unsigned int max_cpu_capacity;
    struct perf_domain * pd;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int max_cpu_capacity</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct irq_work rto_push_work</code>
</li>
<li>
<b>Field added. </b>
<code>raw_spinlock_t rto_lock</code>
</li>
<li>
<b>Field added. </b>
<code>int rto_loop</code>
</li>
<li>
<b>Field added. </b>
<code>int rto_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t rto_loop_next</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t rto_loop_start</code>
</li>
</ul>
</details>
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
<code>int overutilized</code>
</li>
<li>
<b>Field added. </b>
<code>struct perf_domain * pd</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool overload</code> ➡️ <code>int overload</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 visit_gen</code>
</li>
</ul>
</details>
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
