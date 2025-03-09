# Struct: <code>ib_qp_attr</code>

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
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
    struct net_device * xmit_slave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
    struct net_device * xmit_slave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u32 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u32 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
    struct net_device * xmit_slave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u32 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u32 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
    struct net_device * xmit_slave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u32 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u32 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
    struct net_device * xmit_slave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u32 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u32 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
    struct net_device * xmit_slave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u32 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u32 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
    struct net_device * xmit_slave;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u32 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u32 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
    struct net_device * xmit_slave;
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
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
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
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
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
struct ib_qp_attr {
    enum ib_qp_state qp_state;
    enum ib_qp_state cur_qp_state;
    enum ib_mtu path_mtu;
    enum ib_mig_state path_mig_state;
    u32 qkey;
    u32 rq_psn;
    u32 sq_psn;
    u32 dest_qp_num;
    int qp_access_flags;
    struct ib_qp_cap cap;
    struct rdma_ah_attr ah_attr;
    struct rdma_ah_attr alt_ah_attr;
    u16 pkey_index;
    u16 alt_pkey_index;
    u8 en_sqd_async_notify;
    u8 sq_draining;
    u8 max_rd_atomic;
    u8 max_dest_rd_atomic;
    u8 min_rnr_timer;
    u8 port_num;
    u8 timeout;
    u8 retry_cnt;
    u8 rnr_retry;
    u8 alt_port_num;
    u8 alt_timeout;
    u32 rate_limit;
}
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct net_device * xmit_slave</code>
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
<code>u8 port_num</code> ➡️ <code>u32 port_num</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 alt_port_num</code> ➡️ <code>u32 alt_port_num</code>
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
