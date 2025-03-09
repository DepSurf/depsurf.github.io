# Struct: <code>ib_qp_init_attr</code>

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
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    enum ib_qp_create_flags create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    enum ib_qp_create_flags create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u32 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u32 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u32 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u32 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u32 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u32 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
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
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
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
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    u32 create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
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
struct ib_qp_init_attr {
    void (*)(struct ib_event *, void *) event_handler;
    void * qp_context;
    struct ib_cq * send_cq;
    struct ib_cq * recv_cq;
    struct ib_srq * srq;
    struct ib_xrcd * xrcd;
    struct ib_qp_cap cap;
    enum ib_sig_type sq_sig_type;
    enum ib_qp_type qp_type;
    enum ib_qp_create_flags create_flags;
    u8 port_num;
    struct ib_rwq_ind_table * rwq_ind_tbl;
    u32 source_qpn;
}
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>enum ib_qp_create_flags create_flags</code> ➡️ <code>u32 create_flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u8 port_num</code> ➡️ <code>u32 port_num</code>
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
