# Struct: <code>ib_device</code>

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
struct ib_device {
    struct device * dma_device;
    char[64] name;
    struct list_head event_handler_list;
    spinlock_t event_handler_lock;
    spinlock_t client_data_lock;
    struct list_head core_list;
    struct list_head client_data_list;
    struct ib_cache cache;
    struct ib_port_immutable * port_immutable;
    int num_comp_vectors;
    struct ib_port_pkey_list * port_pkey_list;
    struct iw_cm_verbs * iwcm;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(struct ib_device *, u8, unsigned int, const union ib_gid *, const struct ib_gid_attr *, void * *) add_gid;
    int (*)(struct ib_device *, u8, unsigned int, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    struct ib_ucontext * (*)(struct ib_device *, struct ib_udata *) alloc_ucontext;
    int (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    struct ib_pd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_pd;
    int (*)(struct ib_pd *) dealloc_pd;
    struct ib_ah * (*)(struct ib_pd *, struct rdma_ah_attr *, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    int (*)(struct ib_ah *) destroy_ah;
    struct ib_srq * (*)(struct ib_pd *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    int (*)(struct ib_srq *) destroy_srq;
    int (*)(struct ib_srq *, struct ib_recv_wr *, struct ib_recv_wr * *) post_srq_recv;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *) destroy_qp;
    int (*)(struct ib_qp *, struct ib_send_wr *, struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, struct ib_recv_wr *, struct ib_recv_wr * *) post_recv;
    struct ib_cq * (*)(struct ib_device *, const struct ib_cq_init_attr *, struct ib_ucontext *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    int (*)(struct ib_cq *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    int (*)(struct ib_wq *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    struct module * owner;
    struct device dev;
    struct kobject * ports_parent;
    struct list_head port_list;
    enum (anon) reg_state;
    int uverbs_abi_ver;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    struct uverbs_root_spec * specs_root;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    char[64] name;
    struct list_head event_handler_list;
    spinlock_t event_handler_lock;
    spinlock_t client_data_lock;
    struct list_head core_list;
    struct list_head client_data_list;
    struct ib_cache cache;
    struct ib_port_immutable * port_immutable;
    int num_comp_vectors;
    struct ib_port_pkey_list * port_pkey_list;
    struct iw_cm_verbs * iwcm;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(const union ib_gid *, const struct ib_gid_attr *, void * *) add_gid;
    int (*)(const struct ib_gid_attr *, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    struct ib_ucontext * (*)(struct ib_device *, struct ib_udata *) alloc_ucontext;
    int (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    struct ib_pd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_pd;
    int (*)(struct ib_pd *) dealloc_pd;
    struct ib_ah * (*)(struct ib_pd *, struct rdma_ah_attr *, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    int (*)(struct ib_ah *) destroy_ah;
    struct ib_srq * (*)(struct ib_pd *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    int (*)(struct ib_srq *) destroy_srq;
    int (*)(struct ib_srq *, struct ib_recv_wr *, struct ib_recv_wr * *) post_srq_recv;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *) destroy_qp;
    int (*)(struct ib_qp *, struct ib_send_wr *, struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, struct ib_recv_wr *, struct ib_recv_wr * *) post_recv;
    struct ib_cq * (*)(struct ib_device *, const struct ib_cq_init_attr *, struct ib_ucontext *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    int (*)(struct ib_cq *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    int (*)(struct ib_wq *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp;
    int (*)(struct ib_flow_action *) destroy_flow_action;
    int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp;
    struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm;
    int (*)(struct ib_dm *) dealloc_dm;
    struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr;
    struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters;
    int (*)(struct ib_counters *) destroy_counters;
    int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    struct module * owner;
    struct device dev;
    struct kobject * ports_parent;
    struct list_head port_list;
    enum (anon) reg_state;
    int uverbs_abi_ver;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    struct rdma_restrack_root res;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    struct uverbs_root_spec * specs_root;
    enum rdma_driver_id driver_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct list_head event_handler_list;
    spinlock_t event_handler_lock;
    rwlock_t client_data_lock;
    struct list_head core_list;
    struct list_head client_data_list;
    struct ib_cache cache;
    struct ib_port_immutable * port_immutable;
    int num_comp_vectors;
    struct ib_port_pkey_list * port_pkey_list;
    struct iw_cm_verbs * iwcm;
    struct module * owner;
    struct device dev;
    const struct attribute_group *[3] groups;
    struct kobject * ports_kobj;
    struct list_head port_list;
    enum (anon) reg_state;
    int uverbs_abi_ver;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    struct rdma_restrack_root res;
    const struct uapi_definition * driver_def;
    enum rdma_driver_id driver_id;
    refcount_t refcount;
    struct completion unreg_completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    spinlock_t event_handler_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    struct ib_cache cache;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[3] groups;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t event_handler_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    struct ib_cache cache;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[3] groups;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t qp_open_list_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    rwlock_t cache_lock;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[3] groups;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    spinlock_t cq_pools_lock;
    struct list_head[3] cq_pools;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
    u32 lag_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t qp_open_list_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    rwlock_t cache_lock;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[3] groups;
    u64 uverbs_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    spinlock_t cq_pools_lock;
    struct list_head[3] cq_pools;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
    u32 lag_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t qp_open_list_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    rwlock_t cache_lock;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[3] groups;
    u64 uverbs_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u32 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    spinlock_t cq_pools_lock;
    struct list_head[3] cq_pools;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
    u32 lag_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t qp_open_list_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    rwlock_t cache_lock;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[4] groups;
    u64 uverbs_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u32 phys_port_cnt;
    struct ib_device_attr attrs;
    struct hw_stats_device_data * hw_stats_data;
    struct rdmacg_device cg_device;
    u32 index;
    spinlock_t cq_pools_lock;
    struct list_head[3] cq_pools;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
    u32 lag_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t qp_open_list_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    rwlock_t cache_lock;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[4] groups;
    u64 uverbs_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u32 phys_port_cnt;
    struct ib_device_attr attrs;
    struct hw_stats_device_data * hw_stats_data;
    struct rdmacg_device cg_device;
    u32 index;
    spinlock_t cq_pools_lock;
    struct list_head[3] cq_pools;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
    u32 lag_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t qp_open_list_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    rwlock_t cache_lock;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[4] groups;
    u64 uverbs_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u32 phys_port_cnt;
    struct ib_device_attr attrs;
    struct hw_stats_device_data * hw_stats_data;
    struct rdmacg_device cg_device;
    u32 index;
    spinlock_t cq_pools_lock;
    struct list_head[3] cq_pools;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
    u32 lag_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t qp_open_list_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    rwlock_t cache_lock;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[4] groups;
    u64 uverbs_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u32 phys_port_cnt;
    struct ib_device_attr attrs;
    struct hw_stats_device_data * hw_stats_data;
    struct rdmacg_device cg_device;
    u32 index;
    spinlock_t cq_pools_lock;
    struct list_head[3] cq_pools;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
    u32 lag_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t qp_open_list_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    rwlock_t cache_lock;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[4] groups;
    u64 uverbs_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u32 phys_port_cnt;
    struct ib_device_attr attrs;
    struct hw_stats_device_data * hw_stats_data;
    struct rdmacg_device cg_device;
    u32 index;
    spinlock_t cq_pools_lock;
    struct list_head[3] cq_pools;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
    u32 lag_flags;
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
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t event_handler_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    struct ib_cache cache;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[3] groups;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t event_handler_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    struct ib_cache cache;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[3] groups;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t event_handler_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    struct ib_cache cache;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[3] groups;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t event_handler_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    struct ib_cache cache;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[3] groups;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
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
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t event_handler_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    struct ib_cache cache;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[3] groups;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t event_handler_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    struct ib_cache cache;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[3] groups;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t event_handler_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    struct ib_cache cache;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[3] groups;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ib_device {
    struct device * dma_device;
    struct ib_device_ops ops;
    char[64] name;
    struct callback_head callback_head;
    struct list_head event_handler_list;
    struct rw_semaphore event_handler_rwsem;
    spinlock_t event_handler_lock;
    struct rw_semaphore client_data_rwsem;
    struct xarray client_data;
    struct mutex unregistration_lock;
    struct ib_cache cache;
    struct ib_port_data * port_data;
    int num_comp_vectors;
    struct device dev;
    struct ib_core_device coredev;
    const struct attribute_group *[3] groups;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u16 kverbs_provider;
    u16 use_cq_dim;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    struct rdma_restrack_root * res;
    const struct uapi_definition * driver_def;
    refcount_t refcount;
    struct completion unreg_completion;
    struct work_struct unregistration_work;
    const struct rdma_link_ops * link_ops;
    struct mutex compat_devs_mutex;
    struct xarray compat_devs;
    char[16] iw_ifname;
    u32 iw_driver_flags;
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
struct ib_device {
    struct device * dma_device;
    char[64] name;
    struct list_head event_handler_list;
    spinlock_t event_handler_lock;
    spinlock_t client_data_lock;
    struct list_head core_list;
    struct list_head client_data_list;
    struct ib_cache cache;
    struct ib_port_immutable * port_immutable;
    int num_comp_vectors;
    struct ib_port_pkey_list * port_pkey_list;
    struct iw_cm_verbs * iwcm;
    struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats;
    int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats;
    int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device;
    int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port;
    enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer;
    struct net_device * (*)(struct ib_device *, u8) get_netdev;
    int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid;
    int (*)(struct ib_device *, u8, unsigned int, const union ib_gid *, const struct ib_gid_attr *, void * *) add_gid;
    int (*)(struct ib_device *, u8, unsigned int, void * *) del_gid;
    int (*)(struct ib_device *, u8, u16, u16 *) query_pkey;
    int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device;
    int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port;
    struct ib_ucontext * (*)(struct ib_device *, struct ib_udata *) alloc_ucontext;
    int (*)(struct ib_ucontext *) dealloc_ucontext;
    int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap;
    struct ib_pd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_pd;
    int (*)(struct ib_pd *) dealloc_pd;
    struct ib_ah * (*)(struct ib_pd *, struct rdma_ah_attr *, struct ib_udata *) create_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah;
    int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah;
    int (*)(struct ib_ah *) destroy_ah;
    struct ib_srq * (*)(struct ib_pd *, struct ib_srq_init_attr *, struct ib_udata *) create_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq;
    int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq;
    int (*)(struct ib_srq *) destroy_srq;
    int (*)(struct ib_srq *, struct ib_recv_wr *, struct ib_recv_wr * *) post_srq_recv;
    struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp;
    int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp;
    int (*)(struct ib_qp *) destroy_qp;
    int (*)(struct ib_qp *, struct ib_send_wr *, struct ib_send_wr * *) post_send;
    int (*)(struct ib_qp *, struct ib_recv_wr *, struct ib_recv_wr * *) post_recv;
    struct ib_cq * (*)(struct ib_device *, const struct ib_cq_init_attr *, struct ib_ucontext *, struct ib_udata *) create_cq;
    int (*)(struct ib_cq *, u16, u16) modify_cq;
    int (*)(struct ib_cq *) destroy_cq;
    int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq;
    int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq;
    int (*)(struct ib_cq *, int) peek_cq;
    int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq;
    int (*)(struct ib_cq *, int) req_ncomp_notif;
    struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr;
    struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr;
    int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr;
    int (*)(struct ib_mr *) dereg_mr;
    struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr;
    int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg;
    struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw;
    int (*)(struct ib_mw *) dealloc_mw;
    struct ib_fmr * (*)(struct ib_pd *, int, struct ib_fmr_attr *) alloc_fmr;
    int (*)(struct ib_fmr *, u64 *, int, u64) map_phys_fmr;
    int (*)(struct list_head *) unmap_fmr;
    int (*)(struct ib_fmr *) dealloc_fmr;
    int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast;
    int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast;
    int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad;
    struct ib_xrcd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_xrcd;
    int (*)(struct ib_xrcd *) dealloc_xrcd;
    struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int) create_flow;
    int (*)(struct ib_flow *) destroy_flow;
    int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status;
    void (*)(struct ib_ucontext *) disassociate_ucontext;
    void (*)(struct ib_qp *) drain_rq;
    void (*)(struct ib_qp *) drain_sq;
    int (*)(struct ib_device *, int, u8, int) set_vf_link_state;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config;
    int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats;
    int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid;
    struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq;
    int (*)(struct ib_wq *) destroy_wq;
    int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq;
    struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table;
    int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table;
    struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev;
    struct module * owner;
    struct device dev;
    struct kobject * ports_parent;
    struct list_head port_list;
    enum (anon) reg_state;
    int uverbs_abi_ver;
    u64 uverbs_cmd_mask;
    u64 uverbs_ex_cmd_mask;
    char[64] node_desc;
    __be64 node_guid;
    u32 local_dma_lkey;
    u16 is_switch;
    u8 node_type;
    u8 phys_port_cnt;
    struct ib_device_attr attrs;
    struct attribute_group * hw_stats_ag;
    struct rdma_hw_stats * hw_stats;
    struct rdmacg_device cg_device;
    u32 index;
    int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable;
    void (*)(struct ib_device *, char *) get_dev_fw_str;
    const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity;
    struct uverbs_root_spec * specs_root;
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
<code>struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ib_flow_action *) destroy_flow_action</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp</code>
</li>
<li>
<b>Field added. </b>
<code>struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ib_dm *) dealloc_dm</code>
</li>
<li>
<b>Field added. </b>
<code>struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr</code>
</li>
<li>
<b>Field added. </b>
<code>struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ib_counters *) destroy_counters</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters</code>
</li>
<li>
<b>Field added. </b>
<code>struct rdma_restrack_root res</code>
</li>
<li>
<b>Field added. </b>
<code>enum rdma_driver_id driver_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, u8, unsigned int, const union ib_gid *, const struct ib_gid_attr *, void * *) add_gid</code> ➡️ <code>int (*)(const union ib_gid *, const struct ib_gid_attr *, void * *) add_gid</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct ib_device *, u8, unsigned int, void * *) del_gid</code> ➡️ <code>int (*)(const struct ib_gid_attr *, void * *) del_gid</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int) create_flow</code> ➡️ <code>struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow</code>
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
<code>struct ib_device_ops ops</code>
</li>
<li>
<b>Field added. </b>
<code>const struct attribute_group *[3] groups</code>
</li>
<li>
<b>Field added. </b>
<code>struct kobject * ports_kobj</code>
</li>
<li>
<b>Field added. </b>
<code>const struct uapi_definition * driver_def</code>
</li>
<li>
<b>Field added. </b>
<code>refcount_t refcount</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion unreg_completion</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rdma_hw_stats * (*)(struct ib_device *, u8) alloc_hw_stats</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, struct rdma_hw_stats *, u8, int) get_hw_stats</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, struct ib_device_attr *, struct ib_udata *) query_device</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, u8, struct ib_port_attr *) query_port</code>
</li>
<li>
<b>Field removed. </b>
<code>enum rdma_link_layer (*)(struct ib_device *, u8) get_link_layer</code>
</li>
<li>
<b>Field removed. </b>
<code>struct net_device * (*)(struct ib_device *, u8) get_netdev</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, u8, int, union ib_gid *) query_gid</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(const union ib_gid *, const struct ib_gid_attr *, void * *) add_gid</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(const struct ib_gid_attr *, void * *) del_gid</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, u8, u16, u16 *) query_pkey</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, int, struct ib_device_modify *) modify_device</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, u8, int, struct ib_port_modify *) modify_port</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_ucontext * (*)(struct ib_device *, struct ib_udata *) alloc_ucontext</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_ucontext *) dealloc_ucontext</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_ucontext *, struct vm_area_struct *) mmap</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_pd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_pd</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_pd *) dealloc_pd</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_ah * (*)(struct ib_pd *, struct rdma_ah_attr *, struct ib_udata *) create_ah</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_ah *, struct rdma_ah_attr *) modify_ah</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_ah *, struct rdma_ah_attr *) query_ah</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_ah *) destroy_ah</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_srq * (*)(struct ib_pd *, struct ib_srq_init_attr *, struct ib_udata *) create_srq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_srq *, struct ib_srq_attr *, enum ib_srq_attr_mask, struct ib_udata *) modify_srq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_srq *, struct ib_srq_attr *) query_srq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_srq *) destroy_srq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_srq *, struct ib_recv_wr *, struct ib_recv_wr * *) post_srq_recv</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_qp * (*)(struct ib_pd *, struct ib_qp_init_attr *, struct ib_udata *) create_qp</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_udata *) modify_qp</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_qp *, struct ib_qp_attr *, int, struct ib_qp_init_attr *) query_qp</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_qp *) destroy_qp</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_qp *, struct ib_send_wr *, struct ib_send_wr * *) post_send</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_qp *, struct ib_recv_wr *, struct ib_recv_wr * *) post_recv</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_cq * (*)(struct ib_device *, const struct ib_cq_init_attr *, struct ib_ucontext *, struct ib_udata *) create_cq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_cq *, u16, u16) modify_cq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_cq *) destroy_cq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_cq *, int, struct ib_udata *) resize_cq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_cq *, int, struct ib_wc *) poll_cq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_cq *, int) peek_cq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_cq *, enum ib_cq_notify_flags) req_notify_cq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_cq *, int) req_ncomp_notif</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_mr * (*)(struct ib_pd *, int) get_dma_mr</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_mr * (*)(struct ib_pd *, u64, u64, u64, int, struct ib_udata *) reg_user_mr</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_mr *, int, u64, u64, u64, int, struct ib_pd *, struct ib_udata *) rereg_user_mr</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_mr *) dereg_mr</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_mr * (*)(struct ib_pd *, enum ib_mr_type, u32) alloc_mr</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_mr *, struct scatterlist *, int, unsigned int *) map_mr_sg</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_mw * (*)(struct ib_pd *, enum ib_mw_type, struct ib_udata *) alloc_mw</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_mw *) dealloc_mw</code>
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
<code>int (*)(struct ib_qp *, union ib_gid *, u16) attach_mcast</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_qp *, union ib_gid *, u16) detach_mcast</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, int, u8, const struct ib_wc *, const struct ib_grh *, const struct ib_mad_hdr *, size_t, struct ib_mad_hdr *, size_t *, u16 *) process_mad</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_xrcd * (*)(struct ib_device *, struct ib_ucontext *, struct ib_udata *) alloc_xrcd</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_xrcd *) dealloc_xrcd</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_flow * (*)(struct ib_qp *, struct ib_flow_attr *, int, struct ib_udata *) create_flow</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_flow *) destroy_flow</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_mr *, u32, struct ib_mr_status *) check_mr_status</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct ib_ucontext *) disassociate_ucontext</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct ib_qp *) drain_rq</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct ib_qp *) drain_sq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, int, u8, int) set_vf_link_state</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, int, u8, struct ifla_vf_info *) get_vf_config</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, int, u8, struct ifla_vf_stats *) get_vf_stats</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, int, u8, u64, int) set_vf_guid</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_wq * (*)(struct ib_pd *, struct ib_wq_init_attr *, struct ib_udata *) create_wq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_wq *) destroy_wq</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_wq *, struct ib_wq_attr *, u32, struct ib_udata *) modify_wq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_rwq_ind_table * (*)(struct ib_device *, struct ib_rwq_ind_table_init_attr *, struct ib_udata *) create_rwq_ind_table</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_rwq_ind_table *) destroy_rwq_ind_table</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_flow_action * (*)(struct ib_device *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) create_flow_action_esp</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_flow_action *) destroy_flow_action</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_flow_action *, const struct ib_flow_action_attrs_esp *, struct uverbs_attr_bundle *) modify_flow_action_esp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_dm * (*)(struct ib_device *, struct ib_ucontext *, struct ib_dm_alloc_attr *, struct uverbs_attr_bundle *) alloc_dm</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_dm *) dealloc_dm</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_mr * (*)(struct ib_pd *, struct ib_dm *, struct ib_dm_mr_attr *, struct uverbs_attr_bundle *) reg_dm_mr</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_counters * (*)(struct ib_device *, struct uverbs_attr_bundle *) create_counters</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_counters *) destroy_counters</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_counters *, struct ib_counters_read_attr *, struct uverbs_attr_bundle *) read_counters</code>
</li>
<li>
<b>Field removed. </b>
<code>struct net_device * (*)(struct ib_device *, u8, enum rdma_netdev_t, const char *, unsigned char, void (*)(struct net_device *)) alloc_rdma_netdev</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kobject * ports_parent</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ib_device *, u8, struct ib_port_immutable *) get_port_immutable</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct ib_device *, char *) get_dev_fw_str</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct cpumask * (*)(struct ib_device *, int) get_vector_affinity</code>
</li>
<li>
<b>Field removed. </b>
<code>struct uverbs_root_spec * specs_root</code>
</li>
<li>
<b>Field type changed. </b>
<code>spinlock_t client_data_lock</code> ➡️ <code>rwlock_t client_data_lock</code>
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
<code>struct callback_head callback_head</code>
</li>
<li>
<b>Field added. </b>
<code>struct rw_semaphore client_data_rwsem</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray client_data</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex unregistration_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct ib_port_data * port_data</code>
</li>
<li>
<b>Field added. </b>
<code>struct ib_core_device coredev</code>
</li>
<li>
<b>Field added. </b>
<code>u16 kverbs_provider</code>
</li>
<li>
<b>Field added. </b>
<code>u16 use_cq_dim</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct unregistration_work</code>
</li>
<li>
<b>Field added. </b>
<code>const struct rdma_link_ops * link_ops</code>
</li>
<li>
<b>Field added. </b>
<code>struct mutex compat_devs_mutex</code>
</li>
<li>
<b>Field added. </b>
<code>struct xarray compat_devs</code>
</li>
<li>
<b>Field added. </b>
<code>char[16] iw_ifname</code>
</li>
<li>
<b>Field added. </b>
<code>u32 iw_driver_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>rwlock_t client_data_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head core_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head client_data_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_port_immutable * port_immutable</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_port_pkey_list * port_pkey_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct iw_cm_verbs * iwcm</code>
</li>
<li>
<b>Field removed. </b>
<code>struct module * owner</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kobject * ports_kobj</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head port_list</code>
</li>
<li>
<b>Field removed. </b>
<code>enum (anon) reg_state</code>
</li>
<li>
<b>Field removed. </b>
<code>int uverbs_abi_ver</code>
</li>
<li>
<b>Field removed. </b>
<code>enum rdma_driver_id driver_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rdma_restrack_root res</code> ➡️ <code>struct rdma_restrack_root * res</code>
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
<code>struct rw_semaphore event_handler_rwsem</code>
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
<code>spinlock_t qp_open_list_lock</code>
</li>
<li>
<b>Field added. </b>
<code>rwlock_t cache_lock</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t cq_pools_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head[3] cq_pools</code>
</li>
<li>
<b>Field added. </b>
<code>u32 lag_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t event_handler_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>struct ib_cache cache</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u64 uverbs_ex_cmd_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u8 phys_port_cnt</code> ➡️ <code>u32 phys_port_cnt</code>
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
<code>struct hw_stats_device_data * hw_stats_data</code>
</li>
<li>
<b>Field removed. </b>
<code>struct attribute_group * hw_stats_ag</code>
</li>
<li>
<b>Field removed. </b>
<code>struct rdma_hw_stats * hw_stats</code>
</li>
<li>
<b>Field type changed. </b>
<code>const struct attribute_group *[3] groups</code> ➡️ <code>const struct attribute_group *[4] groups</code>
</li>
</ul>
</details>
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
