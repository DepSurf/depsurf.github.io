# Struct: <code>bpf_mem_cache</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_mem_cache {
    struct llist_head free_llist;
    local_t active;
    struct llist_head free_llist_extra;
    struct irq_work refill_work;
    struct obj_cgroup * objcg;
    int unit_size;
    int free_cnt;
    int low_watermark;
    int high_watermark;
    int batch;
    int percpu_size;
    struct callback_head rcu;
    struct llist_head free_by_rcu;
    struct llist_head waiting_for_gp;
    atomic_t call_rcu_in_progress;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_mem_cache {
    struct llist_head free_llist;
    local_t active;
    struct llist_head free_llist_extra;
    struct irq_work refill_work;
    struct obj_cgroup * objcg;
    int unit_size;
    int free_cnt;
    int low_watermark;
    int high_watermark;
    int batch;
    int percpu_size;
    struct callback_head rcu;
    struct llist_head free_by_rcu;
    struct llist_head waiting_for_gp;
    atomic_t call_rcu_in_progress;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_mem_cache {
    struct llist_head free_llist;
    local_t active;
    struct llist_head free_llist_extra;
    struct irq_work refill_work;
    struct obj_cgroup * objcg;
    int unit_size;
    int free_cnt;
    int low_watermark;
    int high_watermark;
    int batch;
    int percpu_size;
    bool draining;
    struct bpf_mem_cache * tgt;
    struct llist_head free_by_rcu;
    struct llist_node * free_by_rcu_tail;
    struct llist_head waiting_for_gp;
    struct llist_node * waiting_for_gp_tail;
    struct callback_head rcu;
    atomic_t call_rcu_in_progress;
    struct llist_head free_llist_extra_rcu;
    struct llist_head free_by_rcu_ttrace;
    struct llist_head waiting_for_gp_ttrace;
    struct callback_head rcu_ttrace;
    atomic_t call_rcu_ttrace_in_progress;
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
struct bpf_mem_cache {
    struct llist_head free_llist;
    local_t active;
    struct llist_head free_llist_extra;
    struct irq_work refill_work;
    struct obj_cgroup * objcg;
    int unit_size;
    int free_cnt;
    int low_watermark;
    int high_watermark;
    int batch;
    int percpu_size;
    struct callback_head rcu;
    struct llist_head free_by_rcu;
    struct llist_head waiting_for_gp;
    atomic_t call_rcu_in_progress;
}
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool draining</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_mem_cache * tgt</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_node * free_by_rcu_tail</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_node * waiting_for_gp_tail</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_head free_llist_extra_rcu</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_head free_by_rcu_ttrace</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_head waiting_for_gp_ttrace</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head rcu_ttrace</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t call_rcu_ttrace_in_progress</code>
</li>
</ul>
</details>
</li>
</ul>
