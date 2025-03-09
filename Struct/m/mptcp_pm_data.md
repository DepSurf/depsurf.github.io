# Struct: <code>mptcp_pm_data</code>

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
struct mptcp_pm_data {
    struct mptcp_addr_info local;
    struct mptcp_addr_info remote;
    spinlock_t lock;
    bool addr_signal;
    bool server_side;
    bool work_pending;
    bool accept_addr;
    bool accept_subflow;
    u8 add_addr_signaled;
    u8 add_addr_accepted;
    u8 local_addr_used;
    u8 subflows;
    u8 add_addr_signal_max;
    u8 add_addr_accept_max;
    u8 local_addr_max;
    u8 subflows_max;
    u8 status;
    struct work_struct work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pm_data {
    struct mptcp_addr_info local;
    struct mptcp_addr_info remote;
    struct list_head anno_list;
    spinlock_t lock;
    u8 addr_signal;
    bool server_side;
    bool work_pending;
    bool accept_addr;
    bool accept_subflow;
    u8 add_addr_signaled;
    u8 add_addr_accepted;
    u8 local_addr_used;
    u8 subflows;
    u8 add_addr_signal_max;
    u8 add_addr_accept_max;
    u8 local_addr_max;
    u8 subflows_max;
    u8 status;
    u8 rm_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pm_data {
    struct mptcp_addr_info local;
    struct mptcp_addr_info remote;
    struct list_head anno_list;
    spinlock_t lock;
    u8 addr_signal;
    bool server_side;
    bool work_pending;
    bool accept_addr;
    bool accept_subflow;
    u8 add_addr_signaled;
    u8 add_addr_accepted;
    u8 local_addr_used;
    u8 subflows;
    u8 status;
    struct mptcp_rm_list rm_list_tx;
    struct mptcp_rm_list rm_list_rx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pm_data {
    struct mptcp_addr_info local;
    struct mptcp_addr_info remote;
    struct list_head anno_list;
    spinlock_t lock;
    u8 addr_signal;
    bool server_side;
    bool work_pending;
    bool accept_addr;
    bool accept_subflow;
    bool remote_deny_join_id0;
    u8 add_addr_signaled;
    u8 add_addr_accepted;
    u8 local_addr_used;
    u8 subflows;
    u8 status;
    struct mptcp_rm_list rm_list_tx;
    struct mptcp_rm_list rm_list_rx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pm_data {
    struct mptcp_addr_info local;
    struct mptcp_addr_info remote;
    struct list_head anno_list;
    struct list_head userspace_pm_local_addr_list;
    spinlock_t lock;
    u8 addr_signal;
    bool server_side;
    bool work_pending;
    bool accept_addr;
    bool accept_subflow;
    bool remote_deny_join_id0;
    u8 add_addr_signaled;
    u8 add_addr_accepted;
    u8 local_addr_used;
    u8 pm_type;
    u8 subflows;
    u8 status;
    long unsigned int[4] id_avail_bitmap;
    struct mptcp_rm_list rm_list_tx;
    struct mptcp_rm_list rm_list_rx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pm_data {
    struct mptcp_addr_info local;
    struct mptcp_addr_info remote;
    struct list_head anno_list;
    struct list_head userspace_pm_local_addr_list;
    spinlock_t lock;
    u8 addr_signal;
    bool server_side;
    bool work_pending;
    bool accept_addr;
    bool accept_subflow;
    bool remote_deny_join_id0;
    u8 add_addr_signaled;
    u8 add_addr_accepted;
    u8 local_addr_used;
    u8 pm_type;
    u8 subflows;
    u8 status;
    long unsigned int[4] id_avail_bitmap;
    struct mptcp_rm_list rm_list_tx;
    struct mptcp_rm_list rm_list_rx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pm_data {
    struct mptcp_addr_info local;
    struct mptcp_addr_info remote;
    struct list_head anno_list;
    struct list_head userspace_pm_local_addr_list;
    spinlock_t lock;
    u8 addr_signal;
    bool server_side;
    bool work_pending;
    bool accept_addr;
    bool accept_subflow;
    bool remote_deny_join_id0;
    u8 add_addr_signaled;
    u8 add_addr_accepted;
    u8 local_addr_used;
    u8 pm_type;
    u8 subflows;
    u8 status;
    long unsigned int[4] id_avail_bitmap;
    struct mptcp_rm_list rm_list_tx;
    struct mptcp_rm_list rm_list_rx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mptcp_pm_data {
    struct mptcp_addr_info local;
    struct mptcp_addr_info remote;
    struct list_head anno_list;
    struct list_head userspace_pm_local_addr_list;
    spinlock_t lock;
    u8 addr_signal;
    bool server_side;
    bool work_pending;
    bool accept_addr;
    bool accept_subflow;
    bool remote_deny_join_id0;
    u8 add_addr_signaled;
    u8 add_addr_accepted;
    u8 local_addr_used;
    u8 pm_type;
    u8 subflows;
    u8 status;
    long unsigned int[4] id_avail_bitmap;
    struct mptcp_rm_list rm_list_tx;
    struct mptcp_rm_list rm_list_rx;
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
struct mptcp_pm_data {
    struct mptcp_addr_info local;
    struct mptcp_addr_info remote;
    spinlock_t lock;
    bool addr_signal;
    bool server_side;
    bool work_pending;
    bool accept_addr;
    bool accept_subflow;
    u8 add_addr_signaled;
    u8 add_addr_accepted;
    u8 local_addr_used;
    u8 subflows;
    u8 add_addr_signal_max;
    u8 add_addr_accept_max;
    u8 local_addr_max;
    u8 subflows_max;
    u8 status;
    struct work_struct work;
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
<code>struct list_head anno_list</code>
</li>
<li>
<b>Field added. </b>
<code>u8 rm_id</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct work</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool addr_signal</code> ➡️ <code>u8 addr_signal</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mptcp_rm_list rm_list_tx</code>
</li>
<li>
<b>Field added. </b>
<code>struct mptcp_rm_list rm_list_rx</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 add_addr_signal_max</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 add_addr_accept_max</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 local_addr_max</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 subflows_max</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 rm_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool remote_deny_join_id0</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head userspace_pm_local_addr_list</code>
</li>
<li>
<b>Field added. </b>
<code>u8 pm_type</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int[4] id_avail_bitmap</code>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
