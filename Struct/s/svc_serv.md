# Struct: <code>svc_serv</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct svc_serv {
    struct svc_program * sv_program;
    struct svc_stat * sv_stats;
    spinlock_t sv_lock;
    unsigned int sv_nrthreads;
    unsigned int sv_maxconn;
    unsigned int sv_max_payload;
    unsigned int sv_max_mesg;
    unsigned int sv_xdrsize;
    struct list_head sv_permsocks;
    struct list_head sv_tempsocks;
    int sv_tmpcnt;
    struct timer_list sv_temptimer;
    char * sv_name;
    unsigned int sv_nrpools;
    struct svc_pool * sv_pools;
    const struct svc_serv_ops * sv_ops;
    struct list_head sv_cb_list;
    spinlock_t sv_cb_lock;
    wait_queue_head_t sv_cb_waitq;
    bool sv_bc_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct svc_serv {
    struct svc_program * sv_program;
    struct svc_stat * sv_stats;
    spinlock_t sv_lock;
    struct kref sv_refcnt;
    unsigned int sv_nrthreads;
    unsigned int sv_maxconn;
    unsigned int sv_max_payload;
    unsigned int sv_max_mesg;
    unsigned int sv_xdrsize;
    struct list_head sv_permsocks;
    struct list_head sv_tempsocks;
    int sv_tmpcnt;
    struct timer_list sv_temptimer;
    char * sv_name;
    unsigned int sv_nrpools;
    struct svc_pool * sv_pools;
    int (*)(void *) sv_threadfn;
    struct list_head sv_cb_list;
    spinlock_t sv_cb_lock;
    wait_queue_head_t sv_cb_waitq;
    bool sv_bc_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct svc_serv {
    struct svc_program * sv_program;
    struct svc_stat * sv_stats;
    spinlock_t sv_lock;
    struct kref sv_refcnt;
    unsigned int sv_nrthreads;
    unsigned int sv_maxconn;
    unsigned int sv_max_payload;
    unsigned int sv_max_mesg;
    unsigned int sv_xdrsize;
    struct list_head sv_permsocks;
    struct list_head sv_tempsocks;
    int sv_tmpcnt;
    struct timer_list sv_temptimer;
    char * sv_name;
    unsigned int sv_nrpools;
    struct svc_pool * sv_pools;
    int (*)(void *) sv_threadfn;
    struct list_head sv_cb_list;
    spinlock_t sv_cb_lock;
    wait_queue_head_t sv_cb_waitq;
    bool sv_bc_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct svc_serv {
    struct svc_program * sv_program;
    struct svc_stat * sv_stats;
    spinlock_t sv_lock;
    struct kref sv_refcnt;
    unsigned int sv_nrthreads;
    unsigned int sv_maxconn;
    unsigned int sv_max_payload;
    unsigned int sv_max_mesg;
    unsigned int sv_xdrsize;
    struct list_head sv_permsocks;
    struct list_head sv_tempsocks;
    int sv_tmpcnt;
    struct timer_list sv_temptimer;
    char * sv_name;
    unsigned int sv_nrpools;
    struct svc_pool * sv_pools;
    int (*)(void *) sv_threadfn;
    struct list_head sv_cb_list;
    spinlock_t sv_cb_lock;
    wait_queue_head_t sv_cb_waitq;
    bool sv_bc_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct svc_serv {
    struct svc_program * sv_program;
    struct svc_stat * sv_stats;
    spinlock_t sv_lock;
    unsigned int sv_nrthreads;
    unsigned int sv_maxconn;
    unsigned int sv_max_payload;
    unsigned int sv_max_mesg;
    unsigned int sv_xdrsize;
    struct list_head sv_permsocks;
    struct list_head sv_tempsocks;
    int sv_tmpcnt;
    struct timer_list sv_temptimer;
    char * sv_name;
    unsigned int sv_nrpools;
    struct svc_pool * sv_pools;
    int (*)(void *) sv_threadfn;
    struct lwq sv_cb_list;
    bool sv_bc_enabled;
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct svc_serv {
    struct svc_program * sv_program;
    struct svc_stat * sv_stats;
    spinlock_t sv_lock;
    unsigned int sv_nrthreads;
    unsigned int sv_maxconn;
    unsigned int sv_max_payload;
    unsigned int sv_max_mesg;
    unsigned int sv_xdrsize;
    struct list_head sv_permsocks;
    struct list_head sv_tempsocks;
    int sv_tmpcnt;
    struct timer_list sv_temptimer;
    char * sv_name;
    unsigned int sv_nrpools;
    struct svc_pool * sv_pools;
    const struct svc_serv_ops * sv_ops;
    struct list_head sv_cb_list;
    spinlock_t sv_cb_lock;
    wait_queue_head_t sv_cb_waitq;
    bool sv_bc_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct kref sv_refcnt</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(void *) sv_threadfn</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct svc_serv_ops * sv_ops</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct kref sv_refcnt</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t sv_cb_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>wait_queue_head_t sv_cb_waitq</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head sv_cb_list</code> ➡️ <code>struct lwq sv_cb_list</code>
</li>
</ul>
</details>
</li>
</ul>
