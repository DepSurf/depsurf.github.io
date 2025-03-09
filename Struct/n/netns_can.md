# Struct: <code>netns_can</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct dev_rcv_lists * can_rx_alldev_list;
    spinlock_t can_rcvlists_lock;
    struct timer_list can_stattimer;
    struct s_stats * can_stats;
    struct s_pstats * can_pstats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct dev_rcv_lists * can_rx_alldev_list;
    spinlock_t can_rcvlists_lock;
    struct timer_list can_stattimer;
    struct s_stats * can_stats;
    struct s_pstats * can_pstats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * can_rx_alldev_list;
    spinlock_t can_rcvlists_lock;
    struct timer_list can_stattimer;
    struct s_stats * can_stats;
    struct s_pstats * can_pstats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * can_rx_alldev_list;
    spinlock_t can_rcvlists_lock;
    struct timer_list can_stattimer;
    struct s_stats * can_stats;
    struct s_pstats * can_pstats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * can_rx_alldev_list;
    spinlock_t can_rcvlists_lock;
    struct timer_list can_stattimer;
    struct s_stats * can_stats;
    struct s_pstats * can_pstats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
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
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
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
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct can_dev_rcv_lists * rx_alldev_list;
    spinlock_t rcvlists_lock;
    struct timer_list stattimer;
    struct can_pkg_stats * pkg_stats;
    struct can_rcv_lists_stats * rcv_lists_stats;
    struct hlist_head cgw_list;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct netns_can {
    struct proc_dir_entry * proc_dir;
    struct proc_dir_entry * pde_version;
    struct proc_dir_entry * pde_stats;
    struct proc_dir_entry * pde_reset_stats;
    struct proc_dir_entry * pde_rcvlist_all;
    struct proc_dir_entry * pde_rcvlist_fil;
    struct proc_dir_entry * pde_rcvlist_inv;
    struct proc_dir_entry * pde_rcvlist_sff;
    struct proc_dir_entry * pde_rcvlist_eff;
    struct proc_dir_entry * pde_rcvlist_err;
    struct proc_dir_entry * bcmproc_dir;
    struct dev_rcv_lists * can_rx_alldev_list;
    spinlock_t can_rcvlists_lock;
    struct timer_list can_stattimer;
    struct s_stats * can_stats;
    struct s_pstats * can_pstats;
    struct hlist_head cgw_list;
}
```
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
<b>Field type changed. </b>
<code>struct dev_rcv_lists * can_rx_alldev_list</code> ➡️ <code>struct can_dev_rcv_lists * can_rx_alldev_list</code>
</li>
</ul>
</details>
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
<code>struct can_dev_rcv_lists * rx_alldev_list</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t rcvlists_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct timer_list stattimer</code>
</li>
<li>
<b>Field added. </b>
<code>struct can_pkg_stats * pkg_stats</code>
</li>
<li>
<b>Field added. </b>
<code>struct can_rcv_lists_stats * rcv_lists_stats</code>
</li>
<li>
<b>Field removed. </b>
<code>struct can_dev_rcv_lists * can_rx_alldev_list</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t can_rcvlists_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct timer_list can_stattimer</code>
</li>
<li>
<b>Field removed. </b>
<code>struct s_stats * can_stats</code>
</li>
<li>
<b>Field removed. </b>
<code>struct s_pstats * can_pstats</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct proc_dir_entry * pde_version</code>
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
