# Struct: <code>parallel_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_instance * pinst;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    struct padata_cpumask cpumask;
    spinlock_t lock;
    unsigned int processed;
    struct timer_list timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_instance * pinst;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    struct padata_cpumask cpumask;
    spinlock_t lock;
    unsigned int processed;
    struct timer_list timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_instance * pinst;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    struct padata_cpumask cpumask;
    spinlock_t lock;
    unsigned int processed;
    struct timer_list timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_instance * pinst;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    struct padata_cpumask cpumask;
    spinlock_t lock;
    unsigned int processed;
    struct timer_list timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_instance * pinst;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    struct padata_cpumask cpumask;
    spinlock_t lock;
    unsigned int processed;
    struct timer_list timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_instance * pinst;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    struct padata_cpumask cpumask;
    spinlock_t lock;
    unsigned int processed;
    struct timer_list timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_instance * pinst;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    struct padata_cpumask cpumask;
    spinlock_t lock;
    unsigned int processed;
    struct timer_list timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_instance * pinst;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    struct padata_cpumask cpumask;
    spinlock_t lock;
    unsigned int processed;
    struct timer_list timer;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t refcnt;
    unsigned int seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_list * reorder_list;
    struct padata_serial_queue * squeue;
    atomic_t refcnt;
    unsigned int seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_list * reorder_list;
    struct padata_serial_queue * squeue;
    atomic_t refcnt;
    unsigned int seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_list * reorder_list;
    struct padata_serial_queue * squeue;
    refcount_t refcnt;
    unsigned int seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_list * reorder_list;
    struct padata_serial_queue * squeue;
    refcount_t refcnt;
    unsigned int seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_list * reorder_list;
    struct padata_serial_queue * squeue;
    refcount_t refcnt;
    unsigned int seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_list * reorder_list;
    struct padata_serial_queue * squeue;
    refcount_t refcnt;
    unsigned int seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_list * reorder_list;
    struct padata_serial_queue * squeue;
    refcount_t refcnt;
    unsigned int seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
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
struct parallel_data {
    struct padata_shell * ps;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
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
struct parallel_data {
    struct padata_shell * ps;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct parallel_data {
    struct padata_shell * ps;
    struct padata_parallel_queue * pqueue;
    struct padata_serial_queue * squeue;
    atomic_t reorder_objects;
    atomic_t refcnt;
    atomic_t seq_nr;
    unsigned int processed;
    int cpu;
    struct padata_cpumask cpumask;
    struct work_struct reorder_work;
    spinlock_t lock;
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct padata_shell * ps</code>
</li>
<li>
<b>Field added. </b>
<code>int cpu</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct reorder_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct padata_instance * pinst</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list timer</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>atomic_t reorder_objects</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t seq_nr</code> ➡️ <code>unsigned int seq_nr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct padata_list * reorder_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct padata_parallel_queue * pqueue</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_t refcnt</code> ➡️ <code>refcount_t refcnt</code>
</li>
</ul>
</details>
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
