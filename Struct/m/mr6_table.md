# Struct: <code>mr6_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mr6_table {
    struct list_head list;
    possible_net_t net;
    u32 id;
    struct sock * mroute6_sk;
    struct timer_list ipmr_expire_timer;
    struct list_head mfc6_unres_queue;
    struct list_head[64] mfc6_cache_array;
    struct mif_device[32] vif6_table;
    int maxvif;
    atomic_t cache_resolve_queue_len;
    bool mroute_do_assert;
    bool mroute_do_pim;
    int mroute_reg_vif_num;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mr6_table {
    struct list_head list;
    possible_net_t net;
    u32 id;
    struct sock * mroute6_sk;
    struct timer_list ipmr_expire_timer;
    struct list_head mfc6_unres_queue;
    struct list_head[64] mfc6_cache_array;
    struct mif_device[32] vif6_table;
    int maxvif;
    atomic_t cache_resolve_queue_len;
    bool mroute_do_assert;
    bool mroute_do_pim;
    int mroute_reg_vif_num;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mr6_table {
    struct list_head list;
    possible_net_t net;
    u32 id;
    struct sock * mroute6_sk;
    struct timer_list ipmr_expire_timer;
    struct list_head mfc6_unres_queue;
    struct list_head[64] mfc6_cache_array;
    struct mif_device[32] vif6_table;
    int maxvif;
    atomic_t cache_resolve_queue_len;
    bool mroute_do_assert;
    bool mroute_do_pim;
    int mroute_reg_vif_num;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mr6_table {
    struct list_head list;
    possible_net_t net;
    u32 id;
    struct sock * mroute6_sk;
    struct timer_list ipmr_expire_timer;
    struct list_head mfc6_unres_queue;
    struct list_head[64] mfc6_cache_array;
    struct mif_device[32] vif6_table;
    int maxvif;
    atomic_t cache_resolve_queue_len;
    bool mroute_do_assert;
    bool mroute_do_pim;
    int mroute_reg_vif_num;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mr6_table {
    struct list_head list;
    possible_net_t net;
    u32 id;
    struct sock * mroute6_sk;
    struct timer_list ipmr_expire_timer;
    struct list_head mfc6_unres_queue;
    struct list_head[64] mfc6_cache_array;
    struct mif_device[32] vif6_table;
    int maxvif;
    atomic_t cache_resolve_queue_len;
    bool mroute_do_assert;
    bool mroute_do_pim;
    int mroute_reg_vif_num;
}
```
</details>
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct mr6_table {
    struct list_head list;
    possible_net_t net;
    u32 id;
    struct sock * mroute6_sk;
    struct timer_list ipmr_expire_timer;
    struct list_head mfc6_unres_queue;
    struct list_head[64] mfc6_cache_array;
    struct mif_device[32] vif6_table;
    int maxvif;
    atomic_t cache_resolve_queue_len;
    bool mroute_do_assert;
    bool mroute_do_pim;
    int mroute_reg_vif_num;
}
```
</details>
</li>
</ul>
