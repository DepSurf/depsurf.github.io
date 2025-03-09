# Struct: <code>sk_buff</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    ktime_t tstamp;
    struct skb_mstamp skb_mstamp;
    struct rb_node rbnode;
    struct sock * sk;
    struct net_device * dev;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct sec_path * sp;
    struct nf_conntrack * nfct;
    struct nf_bridge_info * nf_bridge;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 xmit_more;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 pfmemalloc;
    __u8 ignore_df;
    __u8 nfctinfo;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_bad;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u16 tc_index;
    __u16 tc_verd;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    atomic_t users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    ktime_t tstamp;
    struct skb_mstamp skb_mstamp;
    struct rb_node rbnode;
    struct sock * sk;
    struct net_device * dev;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct sec_path * sp;
    struct nf_conntrack * nfct;
    struct nf_bridge_info * nf_bridge;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 xmit_more;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 pfmemalloc;
    __u8 ignore_df;
    __u8 nfctinfo;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_bad;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u16 tc_index;
    __u16 tc_verd;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 offload_fwd_mark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    atomic_t users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    ktime_t tstamp;
    struct skb_mstamp skb_mstamp;
    struct rb_node rbnode;
    struct sock * sk;
    struct net_device * dev;
    long unsigned int dev_scratch;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct sec_path * sp;
    struct nf_conntrack * nfct;
    struct nf_bridge_info * nf_bridge;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 xmit_more;
    __u8 __unused;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 pfmemalloc;
    __u8 ignore_df;
    __u8 nfctinfo;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_bad;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u16 tc_index;
    __u16 tc_verd;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    atomic_t users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    ktime_t tstamp;
    u64 skb_mstamp;
    struct rb_node rbnode;
    struct sock * sk;
    struct net_device * dev;
    long unsigned int dev_scratch;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct sec_path * sp;
    long unsigned int _nfct;
    struct nf_bridge_info * nf_bridge;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 xmit_more;
    __u8 __unused;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 pfmemalloc;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 tc_redirected;
    __u8 tc_from_ingress;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct sock * sk;
    ktime_t tstamp;
    u64 skb_mstamp;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    struct sec_path * sp;
    long unsigned int _nfct;
    struct nf_bridge_info * nf_bridge;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 xmit_more;
    __u8 __unused;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 pfmemalloc;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_mr_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 tc_redirected;
    __u8 tc_from_ingress;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    int ip_defrag_offset;
    struct rb_node rbnode;
    struct sock * sk;
    ktime_t tstamp;
    u64 skb_mstamp;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    struct sec_path * sp;
    long unsigned int _nfct;
    struct nf_bridge_info * nf_bridge;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 xmit_more;
    __u8 pfmemalloc;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_mr_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 tc_redirected;
    __u8 tc_from_ingress;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 xmit_more;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 tc_redirected;
    __u8 tc_from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 tc_redirected;
    __u8 tc_from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 redirected;
    __u8 from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 redirected;
    __u8 from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 redirected;
    __u8 from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _sk_redir;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 redirected;
    __u8 from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _sk_redir;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 pp_recycle;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 redirected;
    __u8 from_ingress;
    __u8 decrypted;
    __u8 slow_gro;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct llist_node ll_node;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _sk_redir;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 pp_recycle;
    __u8 active_extensions;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 dst_pending_confirm;
    __u8 mono_delivery_time;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 redirected;
    __u8 from_ingress;
    __u8 nf_skip_egress;
    __u8 decrypted;
    __u8 slow_gro;
    __u8 csum_not_inet;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    u16 alloc_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    struct (anon) headers;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct llist_node ll_node;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _sk_redir;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 pp_recycle;
    __u8 active_extensions;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 remcsum_offload;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 dst_pending_confirm;
    __u8 mono_delivery_time;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 redirected;
    __u8 from_ingress;
    __u8 nf_skip_egress;
    __u8 decrypted;
    __u8 slow_gro;
    __u8 csum_not_inet;
    __u8 scm_io_uring;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    u32 vlan_all;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    u16 alloc_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    struct (anon) headers;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct llist_node ll_node;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _sk_redir;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 pp_recycle;
    __u8 active_extensions;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 dst_pending_confirm;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8[0] __mono_tc_offset;
    __u8 mono_delivery_time;
    __u8 tc_at_ingress;
    __u8 tc_skip_classify;
    __u8 remcsum_offload;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 inner_protocol_type;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 nf_trace;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 redirected;
    __u8 from_ingress;
    __u8 nf_skip_egress;
    __u8 decrypted;
    __u8 slow_gro;
    __u8 csum_not_inet;
    __u16 tc_index;
    u16 alloc_cpu;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    u32 vlan_all;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    struct (anon) headers;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct llist_node ll_node;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _sk_redir;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 pp_recycle;
    __u8 active_extensions;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 dst_pending_confirm;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8[0] __mono_tc_offset;
    __u8 mono_delivery_time;
    __u8 tc_at_ingress;
    __u8 tc_skip_classify;
    __u8 remcsum_offload;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 inner_protocol_type;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 nf_trace;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 redirected;
    __u8 from_ingress;
    __u8 nf_skip_egress;
    __u8 decrypted;
    __u8 slow_gro;
    __u8 csum_not_inet;
    __u16 tc_index;
    u16 alloc_cpu;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    u32 vlan_all;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    struct (anon) headers;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
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
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 redirected;
    __u8 from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 redirected;
    __u8 from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 redirected;
    __u8 from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 redirected;
    __u8 from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
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
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 redirected;
    __u8 from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 redirected;
    __u8 from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 redirected;
    __u8 from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sk_buff {
    struct sk_buff * next;
    struct sk_buff * prev;
    struct net_device * dev;
    long unsigned int dev_scratch;
    struct rb_node rbnode;
    struct list_head list;
    struct sock * sk;
    int ip_defrag_offset;
    ktime_t tstamp;
    u64 skb_mstamp_ns;
    char[48] cb;
    long unsigned int _skb_refdst;
    void (*)(struct sk_buff *) destructor;
    struct list_head tcp_tsorted_anchor;
    long unsigned int _nfct;
    unsigned int len;
    unsigned int data_len;
    __u16 mac_len;
    __u16 hdr_len;
    __u16 queue_mapping;
    __u8[0] __cloned_offset;
    __u8 cloned;
    __u8 nohdr;
    __u8 fclone;
    __u8 peeked;
    __u8 head_frag;
    __u8 pfmemalloc;
    __u8 active_extensions;
    __u32[0] headers_start;
    __u8[0] __pkt_type_offset;
    __u8 pkt_type;
    __u8 ignore_df;
    __u8 nf_trace;
    __u8 ip_summed;
    __u8 ooo_okay;
    __u8 l4_hash;
    __u8 sw_hash;
    __u8 wifi_acked_valid;
    __u8 wifi_acked;
    __u8 no_fcs;
    __u8 encapsulation;
    __u8 encap_hdr_csum;
    __u8 csum_valid;
    __u8[0] __pkt_vlan_present_offset;
    __u8 vlan_present;
    __u8 csum_complete_sw;
    __u8 csum_level;
    __u8 csum_not_inet;
    __u8 dst_pending_confirm;
    __u8 ndisc_nodetype;
    __u8 ipvs_property;
    __u8 inner_protocol_type;
    __u8 remcsum_offload;
    __u8 offload_fwd_mark;
    __u8 offload_l3_fwd_mark;
    __u8 tc_skip_classify;
    __u8 tc_at_ingress;
    __u8 redirected;
    __u8 from_ingress;
    __u8 decrypted;
    __u16 tc_index;
    __wsum csum;
    __u16 csum_start;
    __u16 csum_offset;
    __u32 priority;
    int skb_iif;
    __u32 hash;
    __be16 vlan_proto;
    __u16 vlan_tci;
    unsigned int napi_id;
    unsigned int sender_cpu;
    __u32 secmark;
    __u32 mark;
    __u32 reserved_tailroom;
    __be16 inner_protocol;
    __u8 inner_ipproto;
    __u16 inner_transport_header;
    __u16 inner_network_header;
    __u16 inner_mac_header;
    __be16 protocol;
    __u16 transport_header;
    __u16 network_header;
    __u16 mac_header;
    __u32[0] headers_end;
    sk_buff_data_t tail;
    sk_buff_data_t end;
    unsigned char * head;
    unsigned char * data;
    unsigned int truesize;
    refcount_t users;
    struct skb_ext * extensions;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 offload_fwd_mark</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int dev_scratch</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cloned_offset</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 __unused</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 offload_fwd_mark</code> ➡️ <code>__u8 offload_fwd_mark</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int _nfct</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 csum_not_inet</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 dst_pending_confirm</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 tc_skip_classify</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 tc_at_ingress</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 tc_redirected</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 tc_from_ingress</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nf_conntrack * nfct</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 nfctinfo</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 csum_bad</code>
</li>
<li>
<b>Field removed. </b>
<code>__u16 tc_verd</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct skb_mstamp skb_mstamp</code> ➡️ <code>u64 skb_mstamp</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_t users</code> ➡️ <code>refcount_t users</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head tcp_tsorted_anchor</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 offload_mr_fwd_mark</code>
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
<code>int ip_defrag_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 __unused</code>
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
<code>struct list_head list</code>
</li>
<li>
<b>Field added. </b>
<code>u64 skb_mstamp_ns</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 active_extensions</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __pkt_vlan_present_offset</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 vlan_present</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 offload_l3_fwd_mark</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 decrypted</code>
</li>
<li>
<b>Field added. </b>
<code>struct skb_ext * extensions</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 skb_mstamp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sec_path * sp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct nf_bridge_info * nf_bridge</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 offload_mr_fwd_mark</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>__u8 xmit_more</code>
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
<code>__u8 redirected</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 from_ingress</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 tc_redirected</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 tc_from_ingress</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>long unsigned int _sk_redir</code>
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
<code>__u8 pp_recycle</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 slow_gro</code>
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
<code>struct llist_node ll_node</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 mono_delivery_time</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 nf_skip_egress</code>
</li>
<li>
<b>Field added. </b>
<code>u16 alloc_cpu</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) headers</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32[0] headers_start</code>
</li>
<li>
<b>Field removed. </b>
<code>__u32[0] headers_end</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8 scm_io_uring</code>
</li>
<li>
<b>Field added. </b>
<code>u32 vlan_all</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 vlan_present</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u8[0] __mono_tc_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8[0] __pkt_vlan_present_offset</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 scm_io_uring</code>
</li>
</ul>
</details>
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
