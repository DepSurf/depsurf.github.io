# Struct: <code>kfree_rcu_cpu_work</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu_work {
    struct rcu_work rcu_work;
    struct callback_head * head_free;
    struct kfree_rcu_bulk_data * bhead_free;
    struct kfree_rcu_cpu * krcp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu_work {
    struct rcu_work rcu_work;
    struct callback_head * head_free;
    struct kvfree_rcu_bulk_data *[2] bkvhead_free;
    struct kfree_rcu_cpu * krcp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu_work {
    struct rcu_work rcu_work;
    struct callback_head * head_free;
    struct kvfree_rcu_bulk_data *[2] bkvhead_free;
    struct kfree_rcu_cpu * krcp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu_work {
    struct rcu_work rcu_work;
    struct callback_head * head_free;
    struct kvfree_rcu_bulk_data *[2] bkvhead_free;
    struct kfree_rcu_cpu * krcp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu_work {
    struct rcu_work rcu_work;
    struct callback_head * head_free;
    struct kvfree_rcu_bulk_data *[2] bkvhead_free;
    struct kfree_rcu_cpu * krcp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu_work {
    struct rcu_work rcu_work;
    struct callback_head * head_free;
    struct kvfree_rcu_bulk_data *[2] bkvhead_free;
    struct kfree_rcu_cpu * krcp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu_work {
    struct rcu_work rcu_work;
    struct callback_head * head_free;
    struct rcu_gp_oldstate head_free_gp_snap;
    struct list_head[2] bulk_head_free;
    struct kfree_rcu_cpu * krcp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kfree_rcu_cpu_work {
    struct rcu_work rcu_work;
    struct callback_head * head_free;
    struct rcu_gp_oldstate head_free_gp_snap;
    struct list_head[2] bulk_head_free;
    struct kfree_rcu_cpu * krcp;
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct kfree_rcu_cpu_work {
    struct rcu_work rcu_work;
    struct callback_head * head_free;
    struct kfree_rcu_bulk_data * bhead_free;
    struct kfree_rcu_cpu * krcp;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct kvfree_rcu_bulk_data *[2] bkvhead_free</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kfree_rcu_bulk_data * bhead_free</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rcu_gp_oldstate head_free_gp_snap</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head[2] bulk_head_free</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kvfree_rcu_bulk_data *[2] bkvhead_free</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
