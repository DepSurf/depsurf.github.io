# Struct: <code>cppc_pcc_data</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    int pcc_subspace_idx;
    bool pcc_channel_acquired;
    ktime_t deadline;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    int pcc_subspace_idx;
    bool pcc_channel_acquired;
    ktime_t deadline;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    ktime_t deadline;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct pcc_mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct pcc_mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct pcc_mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct pcc_mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
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
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    int pcc_subspace_idx;
    bool pcc_channel_acquired;
    ktime_t deadline;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
}
```
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
<code>ktime_t last_cmd_cmpl_time</code>
</li>
<li>
<b>Field added. </b>
<code>ktime_t last_mpar_reset</code>
</li>
<li>
<b>Field added. </b>
<code>int mpar_count</code>
</li>
<li>
<b>Field added. </b>
<code>int refcount</code>
</li>
<li>
<b>Field removed. </b>
<code>int pcc_subspace_idx</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int deadline_us</code>
</li>
<li>
<b>Field removed. </b>
<code>ktime_t deadline</code>
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
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct mbox_chan * pcc_channel</code> ➡️ <code>struct pcc_mbox_chan * pcc_channel</code>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct cppc_pcc_data {
    struct mbox_chan * pcc_channel;
    void * pcc_comm_addr;
    bool pcc_channel_acquired;
    unsigned int deadline_us;
    unsigned int pcc_mpar;
    unsigned int pcc_mrtt;
    unsigned int pcc_nominal;
    bool pending_pcc_write_cmd;
    bool platform_owns_pcc;
    unsigned int pcc_write_cnt;
    struct rw_semaphore pcc_lock;
    wait_queue_head_t pcc_write_wait_q;
    ktime_t last_cmd_cmpl_time;
    ktime_t last_mpar_reset;
    int mpar_count;
    int refcount;
}
```
</details>
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
