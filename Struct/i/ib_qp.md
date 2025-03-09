# Struct: <code>ib_qp</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uqp_object * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uqp_object * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uqp_object * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u32 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uqp_object * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u32 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uqp_object * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u32 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uqp_object * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u32 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uqp_object * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u32 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uqp_object * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u32 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
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
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
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
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    const struct ib_gid_attr * av_sgid_attr;
    const struct ib_gid_attr * alt_path_sgid_attr;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
    bool integrity_en;
    struct rdma_restrack_entry res;
    struct rdma_counter * counter;
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct ib_qp {
    struct ib_device * device;
    struct ib_pd * pd;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    spinlock_t mr_lock;
    int mrs_used;
    struct list_head rdma_mrs;
    struct list_head sig_mrs;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct list_head xrcd_list;
    atomic_t usecnt;
    struct list_head open_list;
    struct ib_qp * real_qp;
    struct ib_uobject * uobject;
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    u32 qp_num;
    u32 max_write_sge;
    u32 max_read_sge;
    enum ib_qp_type qp_type;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    struct ib_qp_security * qp_sec;
    u8 port;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rdma_restrack_entry res</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct ib_gid_attr * av_sgid_attr</code>
</li>
<li>
<b>Field added. </b>
<code>const struct ib_gid_attr * alt_path_sgid_attr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool integrity_en</code>
</li>
<li>
<b>Field added. </b>
<code>struct rdma_counter * counter</code>
</li>
</ul>
</details>
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
<code>struct ib_uobject * uobject</code> ➡️ <code>struct ib_uqp_object * uobject</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u8 port</code> ➡️ <code>u32 port</code>
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
