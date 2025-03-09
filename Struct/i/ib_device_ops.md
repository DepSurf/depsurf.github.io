# Struct: <code>ib_device_ops</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    struct ib_ucontext * (*)(struct ib_device *, struct ib_udata *) alloc_ucontext;
    int (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    struct ib_pd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_pd;
    int (*)(struct ib_pd *) dealloc_pd;
    struct ib_ah * (*)(struct ib_pd *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    int (*)(struct ib_ah *, u32) destroy_ah;
    struct ib_srq * (*)(struct ib_pd *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    int (*)(struct ib_srq *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *) destroy_qp;
    struct ib_cq * (*)(struct ib_device *, const struct ib_cq_init_attr *, struct ib_ucontext *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    int (*)(struct ib_cq *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    int (*)(struct ib_wq *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    void (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    void (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    void (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    void (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32, struct ib_udata *) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    void (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, u8, struct kobject *) init_port;
    int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_res_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    size_t size_ib_ah;
    size_t size_ib_cq;
    size_t size_ib_pd;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    void (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    void (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    void (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    void (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32, struct ib_udata *) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    void (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, u8, struct kobject *) init_port;
    int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_res_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    size_t size_ib_ah;
    size_t size_ib_cq;
    size_t size_ib_pd;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad *, struct ib_mad *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    void (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    void (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    void (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    void (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32, struct ib_udata *) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_guid *, struct ifla_vf_guid *) get_vf_guid;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    void (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, u8, struct kobject *) init_port;
    int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_res_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_stat_entry;
    size_t size_ib_ah;
    size_t size_ib_cq;
    size_t size_ib_pd;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad *, struct ib_mad *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    int (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_user_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    int (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    int (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    int (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    struct ib_mr * (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    int (*)(struct ib_mw *, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    int (*)(struct ib_xrcd *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_guid *, struct ifla_vf_guid *) get_vf_guid;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    int (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    int (*)(struct ib_rwq_ind_table *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    int (*)(struct ib_counters *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, u8, struct kobject *) init_port;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry_raw;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry_raw;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry_raw;
    int (*)(struct sk_buff *, struct rdma_cm_id *) fill_res_cm_id_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    int (*)(struct sk_buff *, struct ib_mr *) fill_stat_mr_entry;
    int (*)(struct ib_ucontext *, struct uverbs_attr_bundle *) query_ucontext;
    size_t size_ib_ah;
    size_t size_ib_counters;
    size_t size_ib_cq;
    size_t size_ib_mw;
    size_t size_ib_pd;
    size_t size_ib_rwq_ind_table;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
    size_t size_ib_xrcd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u32, const struct ib_wc *, const struct ib_grh *, const struct ib_mad *, struct ib_mad *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u32, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u32, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u32, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u32) get_link_layer;
    struct net_device * (*)(struct ib_device *, u32) get_netdev;
    struct net_device * (*)(struct ib_device *, u32, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u32, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u32, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u32, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    int (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_user_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    int (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    int (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    int (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, int, struct ib_udata *) reg_user_mr_dmabuf;
    struct ib_mr * (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    int (*)(struct ib_mw *, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    int (*)(struct ib_xrcd *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u32, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_guid *, struct ifla_vf_guid *) get_vf_guid;
    int (*)(struct ib_device *, int, u32, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    int (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    int (*)(struct ib_rwq_ind_table *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    int (*)(struct ib_counters *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *, u32) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u32, int) get_hw_stats;
    int (*)(struct ib_device *, u32, struct kobject *) init_port;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry_raw;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry_raw;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry_raw;
    int (*)(struct sk_buff *, struct rdma_cm_id *) fill_res_cm_id_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    int (*)(struct sk_buff *, struct ib_mr *) fill_stat_mr_entry;
    int (*)(struct ib_ucontext *, struct uverbs_attr_bundle *) query_ucontext;
    size_t size_ib_ah;
    size_t size_ib_counters;
    size_t size_ib_cq;
    size_t size_ib_mw;
    size_t size_ib_pd;
    size_t size_ib_rwq_ind_table;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
    size_t size_ib_xrcd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    const struct attribute_group * device_group;
    const struct attribute_group * * port_groups;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u32, const struct ib_wc *, const struct ib_grh *, const struct ib_mad *, struct ib_mad *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u32, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u32, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u32, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u32) get_link_layer;
    struct net_device * (*)(struct ib_device *, u32) get_netdev;
    struct net_device * (*)(struct ib_device *, u32, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u32, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u32, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u32, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    int (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_user_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    int (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    int (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    int (*)(struct ib_qp *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    int (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, int, struct ib_udata *) reg_user_mr_dmabuf;
    struct ib_mr * (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    int (*)(struct ib_mw *, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    int (*)(struct ib_xrcd *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u32, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_guid *, struct ifla_vf_guid *) get_vf_guid;
    int (*)(struct ib_device *, int, u32, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    int (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    int (*)(struct ib_rwq_ind_table *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    int (*)(struct ib_counters *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *) alloc_hw_device_stats;
    struct rdma_hw_stats * (*)(struct ib_device *, u32) alloc_hw_port_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u32, int) get_hw_stats;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry_raw;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry_raw;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry_raw;
    int (*)(struct sk_buff *, struct rdma_cm_id *) fill_res_cm_id_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    int (*)(struct sk_buff *, struct ib_mr *) fill_stat_mr_entry;
    int (*)(struct ib_ucontext *, struct uverbs_attr_bundle *) query_ucontext;
    int (*)(struct ib_device *) get_numa_node;
    size_t size_ib_ah;
    size_t size_ib_counters;
    size_t size_ib_cq;
    size_t size_ib_mw;
    size_t size_ib_pd;
    size_t size_ib_qp;
    size_t size_ib_rwq_ind_table;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
    size_t size_ib_xrcd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    const struct attribute_group * device_group;
    const struct attribute_group * * port_groups;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u32, const struct ib_wc *, const struct ib_grh *, const struct ib_mad *, struct ib_mad *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u32, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u32, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u32, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u32) get_link_layer;
    struct net_device * (*)(struct ib_device *, u32) get_netdev;
    struct net_device * (*)(struct ib_device *, u32, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u32, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u32, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u32, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    int (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_user_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    int (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    int (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    int (*)(struct ib_qp *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    int (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, int, struct ib_udata *) reg_user_mr_dmabuf;
    struct ib_mr * (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    int (*)(struct ib_mw *, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    int (*)(struct ib_xrcd *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_device *, int, u32, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_guid *, struct ifla_vf_guid *) get_vf_guid;
    int (*)(struct ib_device *, int, u32, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    int (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    int (*)(struct ib_rwq_ind_table *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    int (*)(struct ib_counters *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *) alloc_hw_device_stats;
    struct rdma_hw_stats * (*)(struct ib_device *, u32) alloc_hw_port_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u32, int) get_hw_stats;
    int (*)(struct ib_device *, u32, unsigned int, bool) modify_hw_stat;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry_raw;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry_raw;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry_raw;
    int (*)(struct sk_buff *, struct rdma_cm_id *) fill_res_cm_id_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    int (*)(struct sk_buff *, struct ib_mr *) fill_stat_mr_entry;
    int (*)(struct ib_ucontext *, struct uverbs_attr_bundle *) query_ucontext;
    int (*)(struct ib_device *) get_numa_node;
    size_t size_ib_ah;
    size_t size_ib_counters;
    size_t size_ib_cq;
    size_t size_ib_mw;
    size_t size_ib_pd;
    size_t size_ib_qp;
    size_t size_ib_rwq_ind_table;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
    size_t size_ib_xrcd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    const struct attribute_group * device_group;
    const struct attribute_group * * port_groups;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u32, const struct ib_wc *, const struct ib_grh *, const struct ib_mad *, struct ib_mad *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u32, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u32, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u32, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u32) get_link_layer;
    struct net_device * (*)(struct ib_device *, u32) get_netdev;
    struct net_device * (*)(struct ib_device *, u32, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u32, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u32, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u32, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    int (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_user_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    int (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    int (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    int (*)(struct ib_qp *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    int (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, int, struct ib_udata *) reg_user_mr_dmabuf;
    struct ib_mr * (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    int (*)(struct ib_mw *, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    int (*)(struct ib_xrcd *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_device *, int, u32, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_guid *, struct ifla_vf_guid *) get_vf_guid;
    int (*)(struct ib_device *, int, u32, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    int (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    int (*)(struct ib_rwq_ind_table *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    int (*)(struct ib_counters *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *) alloc_hw_device_stats;
    struct rdma_hw_stats * (*)(struct ib_device *, u32) alloc_hw_port_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u32, int) get_hw_stats;
    int (*)(struct ib_device *, u32, unsigned int, bool) modify_hw_stat;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry_raw;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry_raw;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry_raw;
    int (*)(struct sk_buff *, struct rdma_cm_id *) fill_res_cm_id_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    int (*)(struct sk_buff *, struct ib_mr *) fill_stat_mr_entry;
    int (*)(struct ib_ucontext *, struct uverbs_attr_bundle *) query_ucontext;
    int (*)(struct ib_device *) get_numa_node;
    size_t size_ib_ah;
    size_t size_ib_counters;
    size_t size_ib_cq;
    size_t size_ib_mw;
    size_t size_ib_pd;
    size_t size_ib_qp;
    size_t size_ib_rwq_ind_table;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
    size_t size_ib_xrcd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    const struct attribute_group * device_group;
    const struct attribute_group * * port_groups;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u32, const struct ib_wc *, const struct ib_grh *, const struct ib_mad *, struct ib_mad *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u32, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u32, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u32, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u32) get_link_layer;
    struct net_device * (*)(struct ib_device *, u32) get_netdev;
    struct net_device * (*)(struct ib_device *, u32, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u32, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u32, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u32, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    int (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_user_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    int (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    int (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    int (*)(struct ib_qp *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    int (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, int, struct ib_udata *) reg_user_mr_dmabuf;
    struct ib_mr * (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    int (*)(struct ib_mw *, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    int (*)(struct ib_xrcd *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_device *, int, u32, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_guid *, struct ifla_vf_guid *) get_vf_guid;
    int (*)(struct ib_device *, int, u32, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    int (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    int (*)(struct ib_rwq_ind_table *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    int (*)(struct ib_counters *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *) alloc_hw_device_stats;
    struct rdma_hw_stats * (*)(struct ib_device *, u32) alloc_hw_port_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u32, int) get_hw_stats;
    int (*)(struct ib_device *, u32, unsigned int, bool) modify_hw_stat;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry_raw;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry_raw;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry_raw;
    int (*)(struct sk_buff *, struct rdma_cm_id *) fill_res_cm_id_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    int (*)(struct sk_buff *, struct ib_mr *) fill_stat_mr_entry;
    int (*)(struct ib_ucontext *, struct uverbs_attr_bundle *) query_ucontext;
    int (*)(struct ib_device *) get_numa_node;
    size_t size_ib_ah;
    size_t size_ib_counters;
    size_t size_ib_cq;
    size_t size_ib_mw;
    size_t size_ib_pd;
    size_t size_ib_qp;
    size_t size_ib_rwq_ind_table;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
    size_t size_ib_xrcd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    const struct attribute_group * device_group;
    const struct attribute_group * * port_groups;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u32, const struct ib_wc *, const struct ib_grh *, const struct ib_mad *, struct ib_mad *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u32, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u32, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u32, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u32) get_link_layer;
    struct net_device * (*)(struct ib_device *, u32) get_netdev;
    struct net_device * (*)(struct ib_device *, u32, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u32, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u32, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u32, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    int (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_user_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    int (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    int (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    int (*)(struct ib_qp *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    int (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, int, struct ib_udata *) reg_user_mr_dmabuf;
    struct ib_mr * (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    int (*)(struct ib_mw *, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    int (*)(struct ib_xrcd *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_device *, int, u32, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u32, struct ifla_vf_guid *, struct ifla_vf_guid *) get_vf_guid;
    int (*)(struct ib_device *, int, u32, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    int (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    int (*)(struct ib_rwq_ind_table *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    int (*)(struct ib_counters *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *) alloc_hw_device_stats;
    struct rdma_hw_stats * (*)(struct ib_device *, u32) alloc_hw_port_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u32, int) get_hw_stats;
    int (*)(struct ib_device *, u32, unsigned int, bool) modify_hw_stat;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry;
    int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry_raw;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry;
    int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry_raw;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry;
    int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry_raw;
    int (*)(struct sk_buff *, struct rdma_cm_id *) fill_res_cm_id_entry;
    int (*)(struct sk_buff *, struct ib_srq *) fill_res_srq_entry;
    int (*)(struct sk_buff *, struct ib_srq *) fill_res_srq_entry_raw;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    int (*)(struct sk_buff *, struct ib_mr *) fill_stat_mr_entry;
    int (*)(struct ib_ucontext *, struct uverbs_attr_bundle *) query_ucontext;
    int (*)(struct ib_device *) get_numa_node;
    size_t size_ib_ah;
    size_t size_ib_counters;
    size_t size_ib_cq;
    size_t size_ib_mw;
    size_t size_ib_pd;
    size_t size_ib_qp;
    size_t size_ib_rwq_ind_table;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
    size_t size_ib_xrcd;
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
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    void (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    void (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    void (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    void (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32, struct ib_udata *) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    void (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, u8, struct kobject *) init_port;
    int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_res_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    size_t size_ib_ah;
    size_t size_ib_cq;
    size_t size_ib_pd;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    void (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    void (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    void (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    void (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32, struct ib_udata *) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    void (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, u8, struct kobject *) init_port;
    int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_res_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    size_t size_ib_ah;
    size_t size_ib_cq;
    size_t size_ib_pd;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    void (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    void (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    void (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    void (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32, struct ib_udata *) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    void (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, u8, struct kobject *) init_port;
    int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_res_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    size_t size_ib_ah;
    size_t size_ib_cq;
    size_t size_ib_pd;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    void (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    void (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    void (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    void (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32, struct ib_udata *) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    void (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, u8, struct kobject *) init_port;
    int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_res_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    size_t size_ib_ah;
    size_t size_ib_cq;
    size_t size_ib_pd;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
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
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    void (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    void (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    void (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    void (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32, struct ib_udata *) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    void (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, u8, struct kobject *) init_port;
    int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_res_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    size_t size_ib_ah;
    size_t size_ib_cq;
    size_t size_ib_pd;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    void (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    void (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    void (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    void (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32, struct ib_udata *) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    void (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, u8, struct kobject *) init_port;
    int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_res_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    size_t size_ib_ah;
    size_t size_ib_cq;
    size_t size_ib_pd;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    void (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    void (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    void (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    void (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32, struct ib_udata *) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    void (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, u8, struct kobject *) init_port;
    int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_res_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    size_t size_ib_ah;
    size_t size_ib_cq;
    size_t size_ib_pd;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ib_device_ops {
    struct module * owner;
    enum rdma_driver_id driver_id;
    u32 uverbs_abi_ver;
    unsigned int uverbs_no_driver_id_binding;
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext;
    void (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct rdma_user_mmap_entry *) mmap_free;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    int (*)(struct ib_pd *, struct ib_udata *) alloc_pd;
    void (*)(struct ib_pd *, struct ib_udata *) dealloc_pd;
    int (*)(struct ib_ah *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    void (*)(struct ib_ah *, u32) destroy_ah;
    int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    void (*)(struct ib_srq *, struct ib_udata *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *, struct ib_udata *) destroy_qp;
    int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    void (*)(struct ib_cq *, struct ib_udata *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *, struct ib_udata *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32, struct ib_udata *) alloc_mr;
    struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    void (*)(struct ib_wq *, struct ib_udata *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, u8, struct kobject *) init_port;
    int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_res_entry;
    int (*)(struct ib_device *) enable_driver;
    void (*)(struct ib_device *) dealloc_driver;
    void (*)(struct ib_qp *) iw_add_ref;
    void (*)(struct ib_qp *) iw_rem_ref;
    struct ib_qp * (*)(struct ib_device *, int) iw_get_qp;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect;
    int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept;
    int (*)(struct iw_cm_id *, const void *, u8) iw_reject;
    int (*)(struct iw_cm_id *, int) iw_create_listen;
    int (*)(struct iw_cm_id *) iw_destroy_listen;
    int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp;
    int (*)(struct ib_qp *) counter_unbind_qp;
    int (*)(struct rdma_counter *) counter_dealloc;
    struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats;
    int (*)(struct rdma_counter *) counter_update_stats;
    size_t size_ib_ah;
    size_t size_ib_cq;
    size_t size_ib_pd;
    size_t size_ib_srq;
    size_t size_ib_ucontext;
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct ib_device_ops {
    int (*)(struct ib_qp *, const struct ib_send_wr *, const struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_recv;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    int (*)(struct ib_srq *, const struct ib_recv_wr *, const struct ib_recv_wr * *) post_srq_recv;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    struct ib_ucontext * (*)(struct ib_device *, struct ib_udata *) alloc_ucontext;
    int (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    struct ib_pd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_pd;
    int (*)(struct ib_pd *) dealloc_pd;
    struct ib_ah * (*)(struct ib_pd *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    int (*)(struct ib_ah *, u32) destroy_ah;
    struct ib_srq * (*)(struct ib_pd *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    int (*)(struct ib_srq *) destroy_srq;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *) destroy_qp;
    struct ib_cq * (*)(struct ib_device *, const struct ib_cq_init_attr *, struct ib_ucontext *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    int (*)(struct ib_cq *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr;
    int (*)(struct ib_pd *, enum ib_uverbs_advise_mr_advice, u32, struct ib_sge *, u32, struct uverbs_attr_bundle *) advise_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    int (*)(struct ib_wq *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct module * owner</code>
</li>
<li>
<b>Field added. </b>
<code>enum rdma_driver_id driver_id</code>
</li>
<li>
<b>Field added. </b>
<code>u32 uverbs_abi_ver</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int uverbs_no_driver_id_binding</code>
</li>
<li>
<b>Field added. </b>
<code>struct ib_mr * (*)(struct ib_pd *, u32, u32) alloc_mr_integrity</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *, struct scatterlist *, int, unsigned int *) map_mr_sg_pi</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ib_device *, u8, struct kobject *) init_port</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_res_entry</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ib_device *) enable_driver</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct ib_device *) dealloc_driver</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct ib_qp *) iw_add_ref</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct ib_qp *) iw_rem_ref</code>
</li>
<li>
<b>Field added. </b>
<code>struct ib_qp * (*)(struct ib_device *, int) iw_get_qp</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_connect</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct iw_cm_id *, struct iw_cm_conn_param *) iw_accept</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct iw_cm_id *, const void *, u8) iw_reject</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct iw_cm_id *, int) iw_create_listen</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct iw_cm_id *) iw_destroy_listen</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct rdma_counter *, struct ib_qp *) counter_bind_qp</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ib_qp *) counter_unbind_qp</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct rdma_counter *) counter_dealloc</code>
</li>
<li>
<b>Field added. </b>
<code>struct rdma_hw_stats * (*)(struct rdma_counter *) counter_alloc_stats</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct rdma_counter *) counter_update_stats</code>
</li>
<li>
<b>Field added. </b>
<code>size_t size_ib_ah</code>
</li>
<li>
<b>Field added. </b>
<code>size_t size_ib_cq</code>
</li>
<li>
<b>Field added. </b>
<code>size_t size_ib_pd</code>
</li>
<li>
<b>Field added. </b>
<code>size_t size_ib_srq</code>
</li>
<li>
<b>Field added. </b>
<code>size_t size_ib_ucontext</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_ucontext * (*)(struct ib_device *, struct ib_udata *) alloc_ucontext</code> ➡️ <code>int (*)(struct ib_ucontext *, struct ib_udata *) alloc_ucontext</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_ucontext *) dealloc_ucontext</code> ➡️ <code>void (*)(struct ib_ucontext *) dealloc_ucontext</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_pd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_pd</code> ➡️ <code>int (*)(struct ib_pd *, struct ib_udata *) alloc_pd</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_pd *) dealloc_pd</code> ➡️ <code>void (*)(struct ib_pd *, struct ib_udata *) dealloc_pd</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_ah * (*)(struct ib_pd *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah</code> ➡️ <code>int (*)(struct ib_ah *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_ah *, u32) destroy_ah</code> ➡️ <code>void (*)(struct ib_ah *, u32) destroy_ah</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_srq * (*)(struct ib_pd *, struct ib_srq_init_attr *, struct ib_udata *) create_srq</code> ➡️ <code>int (*)(struct ib_srq *, struct ib_srq_init_attr *, struct ib_udata *) create_srq</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_srq *) destroy_srq</code> ➡️ <code>void (*)(struct ib_srq *, struct ib_udata *) destroy_srq</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_qp *) destroy_qp</code> ➡️ <code>int (*)(struct ib_qp *, struct ib_udata *) destroy_qp</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_cq * (*)(struct ib_device *, const struct ib_cq_init_attr *, struct ib_ucontext *, struct ib_udata *) create_cq</code> ➡️ <code>int (*)(struct ib_cq *, const struct ib_cq_init_attr *, struct ib_udata *) create_cq</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_cq *) destroy_cq</code> ➡️ <code>void (*)(struct ib_cq *, struct ib_udata *) destroy_cq</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_mr *) dereg_mr</code> ➡️ <code>int (*)(struct ib_mr *, struct ib_udata *) dereg_mr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr</code> ➡️ <code>struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32, struct ib_udata *) alloc_mr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_xrcd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_xrcd</code> ➡️ <code>struct ib_xrcd * (*)(struct ib_device *, struct ib_udata *) alloc_xrcd</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_xrcd *) dealloc_xrcd</code> ➡️ <code>int (*)(struct ib_xrcd *, struct ib_udata *) dealloc_xrcd</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_wq *) destroy_wq</code> ➡️ <code>void (*)(struct ib_wq *, struct ib_udata *) destroy_wq</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_dm *) dealloc_dm</code> ➡️ <code>int (*)(struct ib_dm *, struct uverbs_attr_bundle *) dealloc_dm</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct rdma_user_mmap_entry *) mmap_free</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct ib_device *, int, u8, struct ifla_vf_guid *, struct ifla_vf_guid *) get_vf_guid</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_stat_entry</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct list_head *) unmap_fmr</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_fmr *) dealloc_fmr</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct ib_umem_odp *, long unsigned int, long unsigned int) invalidate_range</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad</code> ➡️ <code>int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad *, struct ib_mad *, size_t *, u16 *) process_mad</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_ah *, struct rdma_ah_attr *, u32, struct ib_udata *) create_ah</code> ➡️ <code>int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_ah</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct ib_ah *, struct rdma_ah_init_attr *, struct ib_udata *) create_user_ah</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct ib_mr *) fill_res_mr_entry_raw</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct ib_cq *) fill_res_cq_entry_raw</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct ib_qp *) fill_res_qp_entry_raw</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct rdma_cm_id *) fill_res_cm_id_entry</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct ib_mr *) fill_stat_mr_entry</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ib_ucontext *, struct uverbs_attr_bundle *) query_ucontext</code>
</li>
<li>
<b>Field added. </b>
<code>size_t size_ib_counters</code>
</li>
<li>
<b>Field added. </b>
<code>size_t size_ib_mw</code>
</li>
<li>
<b>Field added. </b>
<code>size_t size_ib_rwq_ind_table</code>
</li>
<li>
<b>Field added. </b>
<code>size_t size_ib_xrcd</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_res_entry</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sk_buff *, struct rdma_restrack_entry *) fill_stat_entry</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct ib_pd *, struct ib_udata *) dealloc_pd</code> ➡️ <code>int (*)(struct ib_pd *, struct ib_udata *) dealloc_pd</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct ib_ah *, u32) destroy_ah</code> ➡️ <code>int (*)(struct ib_ah *, u32) destroy_ah</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct ib_srq *, struct ib_udata *) destroy_srq</code> ➡️ <code>int (*)(struct ib_srq *, struct ib_udata *) destroy_srq</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct ib_cq *, struct ib_udata *) destroy_cq</code> ➡️ <code>int (*)(struct ib_cq *, struct ib_udata *) destroy_cq</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr</code> ➡️ <code>struct ib_mr * (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32, struct ib_udata *) alloc_mr</code> ➡️ <code>struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw</code> ➡️ <code>int (*)(struct ib_mw *, struct ib_udata *) alloc_mw</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_xrcd * (*)(struct ib_device *, struct ib_udata *) alloc_xrcd</code> ➡️ <code>int (*)(struct ib_xrcd *, struct ib_udata *) alloc_xrcd</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow</code> ➡️ <code>struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, struct ib_udata *) create_flow</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct ib_wq *, struct ib_udata *) destroy_wq</code> ➡️ <code>int (*)(struct ib_wq *, struct ib_udata *) destroy_wq</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table</code> ➡️ <code>int (*)(struct ib_rwq_ind_table *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters</code> ➡️ <code>int (*)(struct ib_counters *, struct uverbs_attr_bundle *) create_counters</code>
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
<code>struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, int, struct ib_udata *) reg_user_mr_dmabuf</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_cq *, int) req_ncomp_notif</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad *, struct ib_mad *, size_t *, u16 *) process_mad</code> ➡️ <code>int (*)(struct ib_device *, int, u32, const struct ib_wc *, const struct ib_grh *, const struct ib_mad *, struct ib_mad *, size_t *, u16 *) process_mad</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port</code> ➡️ <code>int (*)(struct ib_device *, u32, struct ib_port_attr *) query_port</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port</code> ➡️ <code>int (*)(struct ib_device *, u32, int, struct ib_port_modify *) modify_port</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable</code> ➡️ <code>int (*)(struct ib_device *, u32, struct ib_port_immutable *) get_port_immutable</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer</code> ➡️ <code>enum rdma_link_layer (*)(struct ib_device *, u32) get_link_layer</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct net_device * (*)(struct ib_device *, u8) get_netdev</code> ➡️ <code>struct net_device * (*)(struct ib_device *, u32) get_netdev</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev</code> ➡️ <code>struct net_device * (*)(struct ib_device *, u32, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, u8, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params</code> ➡️ <code>int (*)(struct ib_device *, u32, enum rdma_netdev_t, struct rdma_netdev_alloc_params *) rdma_netdev_get_params</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid</code> ➡️ <code>int (*)(struct ib_device *, u32, int, union ib_gid *) query_gid</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, u8, u16, u16 *) query_pkey</code> ➡️ <code>int (*)(struct ib_device *, u32, u16, u16 *) query_pkey</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, int, u8, int) set_vf_link_state</code> ➡️ <code>int (*)(struct ib_device *, int, u32, int) set_vf_link_state</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config</code> ➡️ <code>int (*)(struct ib_device *, int, u32, struct ifla_vf_info *) get_vf_config</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats</code> ➡️ <code>int (*)(struct ib_device *, int, u32, struct ifla_vf_stats *) get_vf_stats</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, int, u8, struct ifla_vf_guid *, struct ifla_vf_guid *) get_vf_guid</code> ➡️ <code>int (*)(struct ib_device *, int, u32, struct ifla_vf_guid *, struct ifla_vf_guid *) get_vf_guid</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid</code> ➡️ <code>int (*)(struct ib_device *, int, u32, u64, int) set_vf_guid</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats</code> ➡️ <code>struct rdma_hw_stats * (*)(struct ib_device *, u32) alloc_hw_stats</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats</code> ➡️ <code>int (*)(struct ib_device *, struct rdma_hw_stats *, u32, int) get_hw_stats</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, u8, struct kobject *) init_port</code> ➡️ <code>int (*)(struct ib_device *, u32, struct kobject *) init_port</code>
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
<code>const struct attribute_group * device_group</code>
</li>
<li>
<b>Field added. </b>
<code>const struct attribute_group * * port_groups</code>
</li>
<li>
<b>Field added. </b>
<code>struct rdma_hw_stats * (*)(struct ib_device *) alloc_hw_device_stats</code>
</li>
<li>
<b>Field added. </b>
<code>struct rdma_hw_stats * (*)(struct ib_device *, u32) alloc_hw_port_stats</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ib_device *) get_numa_node</code>
</li>
<li>
<b>Field added. </b>
<code>size_t size_ib_qp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rdma_hw_stats * (*)(struct ib_device *, u32) alloc_hw_stats</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, u32, struct kobject *) init_port</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp</code> ➡️ <code>int (*)(struct ib_qp *, struct ib_qp_init_attr *, struct ib_udata *) create_qp</code>
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
<code>int (*)(struct ib_device *, u32, unsigned int, bool) modify_hw_stat</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp</code>
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
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct ib_srq *) fill_res_srq_entry</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sk_buff *, struct ib_srq *) fill_res_srq_entry_raw</code>
</li>
</ul>
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
