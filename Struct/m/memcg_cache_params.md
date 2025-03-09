# Struct: <code>memcg_cache_params</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct memcg_cache_params {
    bool is_root_cache;
    struct list_head list;
    struct memcg_cache_array * memcg_caches;
    struct mem_cgroup * memcg;
    struct kmem_cache * root_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct memcg_cache_params {
    bool is_root_cache;
    struct list_head list;
    struct memcg_cache_array * memcg_caches;
    struct mem_cgroup * memcg;
    struct kmem_cache * root_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct memcg_cache_params {
    bool is_root_cache;
    struct list_head list;
    struct memcg_cache_array * memcg_caches;
    struct mem_cgroup * memcg;
    struct kmem_cache * root_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    void (*)(struct kmem_cache *) deact_fn;
    struct callback_head deact_rcu_head;
    struct work_struct deact_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    void (*)(struct kmem_cache *) deact_fn;
    struct callback_head deact_rcu_head;
    struct work_struct deact_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    void (*)(struct kmem_cache *) deact_fn;
    struct callback_head deact_rcu_head;
    struct work_struct deact_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    void (*)(struct kmem_cache *) deact_fn;
    struct callback_head deact_rcu_head;
    struct work_struct deact_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    struct percpu_ref refcnt;
    void (*)(struct kmem_cache *) work_fn;
    struct callback_head callback_head;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    struct percpu_ref refcnt;
    void (*)(struct kmem_cache *) work_fn;
    struct callback_head callback_head;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    struct percpu_ref refcnt;
    void (*)(struct kmem_cache *) work_fn;
    struct callback_head callback_head;
    struct work_struct work;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    struct percpu_ref refcnt;
    void (*)(struct kmem_cache *) work_fn;
    struct callback_head callback_head;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    struct percpu_ref refcnt;
    void (*)(struct kmem_cache *) work_fn;
    struct callback_head callback_head;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    struct percpu_ref refcnt;
    void (*)(struct kmem_cache *) work_fn;
    struct callback_head callback_head;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    struct percpu_ref refcnt;
    void (*)(struct kmem_cache *) work_fn;
    struct callback_head callback_head;
    struct work_struct work;
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
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    struct percpu_ref refcnt;
    void (*)(struct kmem_cache *) work_fn;
    struct callback_head callback_head;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    struct percpu_ref refcnt;
    void (*)(struct kmem_cache *) work_fn;
    struct callback_head callback_head;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    struct percpu_ref refcnt;
    void (*)(struct kmem_cache *) work_fn;
    struct callback_head callback_head;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    struct percpu_ref refcnt;
    void (*)(struct kmem_cache *) work_fn;
    struct callback_head callback_head;
    struct work_struct work;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head __root_caches_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head children</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head children_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head kmem_caches_node</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kmem_cache *) deact_fn</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head deact_rcu_head</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct deact_work</code>
</li>
<li>
<b>Field removed. </b>
<code>bool is_root_cache</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool dying</code>
</li>
</ul>
</details>
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
<code>struct percpu_ref refcnt</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct kmem_cache *) work_fn</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head callback_head</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct work</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct kmem_cache *) deact_fn</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head deact_rcu_head</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct deact_work</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct memcg_cache_params {
    struct kmem_cache * root_cache;
    struct memcg_cache_array * memcg_caches;
    struct list_head __root_caches_node;
    struct list_head children;
    bool dying;
    struct mem_cgroup * memcg;
    struct list_head children_node;
    struct list_head kmem_caches_node;
    struct percpu_ref refcnt;
    void (*)(struct kmem_cache *) work_fn;
    struct callback_head callback_head;
    struct work_struct work;
}
```
</details>
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
