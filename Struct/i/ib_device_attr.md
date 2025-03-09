# Struct: <code>ib_device_attr</code>

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
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
    u32 max_sgl_rd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
    u32 max_sgl_rd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
    u32 max_sgl_rd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
    u32 max_sgl_rd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    u64 kernel_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
    u32 max_sgl_rd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    u64 kernel_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
    u32 max_sgl_rd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    u64 kernel_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
    u32 max_sgl_rd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    u64 kernel_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
    u32 max_sgl_rd;
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
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
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
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_send_sge;
    int max_recv_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    unsigned int max_pi_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
    u64 max_dm_size;
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
struct ib_device_attr {
    u64 fw_ver;
    __be64 sys_image_guid;
    u64 max_mr_size;
    u64 page_size_cap;
    u32 vendor_id;
    u32 vendor_part_id;
    u32 hw_ver;
    int max_qp;
    int max_qp_wr;
    u64 device_cap_flags;
    int max_sge;
    int max_sge_rd;
    int max_cq;
    int max_cqe;
    int max_mr;
    int max_pd;
    int max_qp_rd_atom;
    int max_ee_rd_atom;
    int max_res_rd_atom;
    int max_qp_init_rd_atom;
    int max_ee_init_rd_atom;
    enum ib_atomic_cap atomic_cap;
    enum ib_atomic_cap masked_atomic_cap;
    int max_ee;
    int max_rdd;
    int max_mw;
    int max_raw_ipv6_qp;
    int max_raw_ethy_qp;
    int max_mcast_grp;
    int max_mcast_qp_attach;
    int max_total_mcast_qp_attach;
    int max_ah;
    int max_fmr;
    int max_map_per_fmr;
    int max_srq;
    int max_srq_wr;
    int max_srq_sge;
    unsigned int max_fast_reg_page_list_len;
    u16 max_pkeys;
    u8 local_ca_ack_delay;
    int sig_prot_cap;
    int sig_guard_cap;
    struct ib_odp_caps odp_caps;
    uint64_t timestamp_mask;
    uint64_t hca_core_clock;
    struct ib_rss_caps rss_caps;
    u32 max_wq_type_rq;
    u32 raw_packet_caps;
    struct ib_tm_caps tm_caps;
    struct ib_cq_caps cq_caps;
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
<code>u64 max_dm_size</code>
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
<code>int max_send_sge</code>
</li>
<li>
<b>Field added. </b>
<code>int max_recv_sge</code>
</li>
<li>
<b>Field removed. </b>
<code>int max_sge</code>
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
<code>unsigned int max_pi_fast_reg_page_list_len</code>
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
<b>Field added. </b>
<code>u32 max_sgl_rd</code>
</li>
<li>
<b>Field removed. </b>
<code>int max_fmr</code>
</li>
<li>
<b>Field removed. </b>
<code>int max_map_per_fmr</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>u64 kernel_cap_flags</code>
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
