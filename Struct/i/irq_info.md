# Struct: <code>irq_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    unsigned int evtchn;
    short unsigned int cpu;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    unsigned int evtchn;
    short unsigned int cpu;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    unsigned int evtchn;
    short unsigned int cpu;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    unsigned int evtchn;
    short unsigned int cpu;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    unsigned int evtchn;
    short unsigned int cpu;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    unsigned int evtchn;
    short unsigned int cpu;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    unsigned int evtchn;
    short unsigned int cpu;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    unsigned int evtchn;
    short unsigned int cpu;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    unsigned int evtchn;
    short unsigned int cpu;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    evtchn_port_t evtchn;
    short unsigned int cpu;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    struct list_head eoi_list;
    short int refcnt;
    u8 spurious_cnt;
    u8 is_accounted;
    short int type;
    u8 mask_reason;
    u8 is_active;
    unsigned int irq;
    evtchn_port_t evtchn;
    short unsigned int cpu;
    short unsigned int eoi_cpu;
    unsigned int irq_epoch;
    u64 eoi_time;
    spinlock_t lock;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    struct list_head eoi_list;
    short int refcnt;
    u8 spurious_cnt;
    u8 is_accounted;
    short int type;
    u8 mask_reason;
    u8 is_active;
    unsigned int irq;
    evtchn_port_t evtchn;
    short unsigned int cpu;
    short unsigned int eoi_cpu;
    unsigned int irq_epoch;
    u64 eoi_time;
    raw_spinlock_t lock;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    struct list_head eoi_list;
    short int refcnt;
    u8 spurious_cnt;
    u8 is_accounted;
    short int type;
    u8 mask_reason;
    u8 is_active;
    unsigned int irq;
    evtchn_port_t evtchn;
    short unsigned int cpu;
    short unsigned int eoi_cpu;
    unsigned int irq_epoch;
    u64 eoi_time;
    raw_spinlock_t lock;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    struct list_head eoi_list;
    short int refcnt;
    u8 spurious_cnt;
    u8 is_accounted;
    short int type;
    u8 mask_reason;
    u8 is_active;
    unsigned int irq;
    evtchn_port_t evtchn;
    short unsigned int cpu;
    short unsigned int eoi_cpu;
    unsigned int irq_epoch;
    u64 eoi_time;
    raw_spinlock_t lock;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    struct list_head eoi_list;
    short int refcnt;
    u8 spurious_cnt;
    u8 is_accounted;
    short int type;
    u8 mask_reason;
    u8 is_active;
    unsigned int irq;
    evtchn_port_t evtchn;
    short unsigned int cpu;
    short unsigned int eoi_cpu;
    unsigned int irq_epoch;
    u64 eoi_time;
    raw_spinlock_t lock;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    struct list_head eoi_list;
    short int refcnt;
    u8 spurious_cnt;
    u8 is_accounted;
    short int type;
    u8 mask_reason;
    u8 is_active;
    unsigned int irq;
    evtchn_port_t evtchn;
    short unsigned int cpu;
    short unsigned int eoi_cpu;
    unsigned int irq_epoch;
    u64 eoi_time;
    raw_spinlock_t lock;
    bool is_static;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    struct list_head eoi_list;
    struct rcu_work rwork;
    short int refcnt;
    u8 spurious_cnt;
    u8 is_accounted;
    short int type;
    u8 mask_reason;
    u8 is_active;
    unsigned int irq;
    evtchn_port_t evtchn;
    short unsigned int cpu;
    short unsigned int eoi_cpu;
    unsigned int irq_epoch;
    u64 eoi_time;
    raw_spinlock_t lock;
    bool is_static;
    union (anon) u;
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
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    unsigned int evtchn;
    short unsigned int cpu;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct irq_info {
    struct hlist_node node;
    int irq;
    spinlock_t lock;
    struct list_head * head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct irq_info {
    struct hlist_node node;
    int irq;
    spinlock_t lock;
    struct list_head * head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct irq_info {
    struct hlist_node node;
    int irq;
    spinlock_t lock;
    struct list_head * head;
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
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    unsigned int evtchn;
    short unsigned int cpu;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct hlist_node node;
    int irq;
    spinlock_t lock;
    struct list_head * head;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    unsigned int evtchn;
    short unsigned int cpu;
    union (anon) u;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct irq_info {
    struct list_head list;
    int refcnt;
    enum xen_irq_type type;
    unsigned int irq;
    unsigned int evtchn;
    short unsigned int cpu;
    union (anon) u;
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned int evtchn</code> ➡️ <code>evtchn_port_t evtchn</code>
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
<code>struct list_head eoi_list</code>
</li>
<li>
<b>Field added. </b>
<code>u8 spurious_cnt</code>
</li>
<li>
<b>Field added. </b>
<code>u8 is_accounted</code>
</li>
<li>
<b>Field added. </b>
<code>u8 mask_reason</code>
</li>
<li>
<b>Field added. </b>
<code>u8 is_active</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int eoi_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int irq_epoch</code>
</li>
<li>
<b>Field added. </b>
<code>u64 eoi_time</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>int refcnt</code> ➡️ <code>short int refcnt</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum xen_irq_type type</code> ➡️ <code>short int type</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>spinlock_t lock</code> ➡️ <code>raw_spinlock_t lock</code>
</li>
</ul>
</details>
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
<code>bool is_static</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rcu_work rwork</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_node node</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head * head</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field removed. </b>
<code>int refcnt</code>
</li>
<li>
<b>Field removed. </b>
<code>enum xen_irq_type type</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int evtchn</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>union (anon) u</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int irq</code> ➡️ <code>int irq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_node node</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head * head</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field removed. </b>
<code>int refcnt</code>
</li>
<li>
<b>Field removed. </b>
<code>enum xen_irq_type type</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int evtchn</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>union (anon) u</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int irq</code> ➡️ <code>int irq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_node node</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head * head</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field removed. </b>
<code>int refcnt</code>
</li>
<li>
<b>Field removed. </b>
<code>enum xen_irq_type type</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int evtchn</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>union (anon) u</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int irq</code> ➡️ <code>int irq</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_node node</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head * head</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
<li>
<b>Field removed. </b>
<code>int refcnt</code>
</li>
<li>
<b>Field removed. </b>
<code>enum xen_irq_type type</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int evtchn</code>
</li>
<li>
<b>Field removed. </b>
<code>short unsigned int cpu</code>
</li>
<li>
<b>Field removed. </b>
<code>union (anon) u</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int irq</code> ➡️ <code>int irq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
