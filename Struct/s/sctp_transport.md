# Struct: <code>sctp_transport</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    int pf_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    int pf_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    int pf_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    int pf_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    __u16 pf_retrans;
    __u16 ps_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __be16 encap_port;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    __u16 pf_retrans;
    __u16 ps_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __be16 encap_port;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    __u16 pf_retrans;
    __u16 ps_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int probe_interval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __be16 encap_port;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    __u16 pf_retrans;
    __u16 ps_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct timer_list probe_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    struct (anon) pl;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int probe_interval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __be16 encap_port;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    __u16 pf_retrans;
    __u16 ps_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct timer_list probe_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    struct (anon) pl;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int probe_interval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __be16 encap_port;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    __u16 pf_retrans;
    __u16 ps_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct timer_list probe_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    struct (anon) pl;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int probe_interval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __be16 encap_port;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    __u16 pf_retrans;
    __u16 ps_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct timer_list probe_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    struct (anon) pl;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int probe_interval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __be16 encap_port;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    __u16 pf_retrans;
    __u16 ps_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct timer_list probe_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    struct (anon) pl;
    __u64 hb_nonce;
    struct callback_head rcu;
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
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    int pf_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    int pf_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    int pf_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    int pf_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
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
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    int pf_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    int pf_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    int pf_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    atomic_t mtu_info;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    __u32 flowlabel;
    __u8 dscp;
    int pf_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct sctp_transport {
    struct list_head transports;
    struct rhlist_head node;
    refcount_t refcnt;
    __u32 rto_pending;
    __u32 hb_sent;
    __u32 pmtu_pending;
    __u32 dst_pending_confirm;
    __u32 sack_generation;
    u32 dst_cookie;
    struct flowi fl;
    union sctp_addr ipaddr;
    struct sctp_af * af_specific;
    struct sctp_association * asoc;
    long unsigned int rto;
    __u32 rtt;
    __u32 rttvar;
    __u32 srtt;
    __u32 cwnd;
    __u32 ssthresh;
    __u32 partial_bytes_acked;
    __u32 flight_size;
    __u32 burst_limited;
    struct dst_entry * dst;
    union sctp_addr saddr;
    long unsigned int hbinterval;
    long unsigned int sackdelay;
    __u32 sackfreq;
    ktime_t last_time_heard;
    long unsigned int last_time_sent;
    long unsigned int last_time_ecne_reduced;
    __u16 pathmaxrxt;
    int pf_retrans;
    __u32 pathmtu;
    __u32 param_flags;
    int init_sent_count;
    int state;
    short unsigned int error_count;
    struct timer_list T3_rtx_timer;
    struct timer_list hb_timer;
    struct timer_list proto_unreach_timer;
    struct timer_list reconf_timer;
    struct list_head transmitted;
    struct sctp_packet packet;
    struct list_head send_ready;
    struct (anon) cacc;
    __u64 hb_nonce;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_t mtu_info</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 flowlabel</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 dscp</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u16 ps_retrans</code>
</li>
<li>
<b>Field type changed. </b>
<code>int pf_retrans</code> ➡️ <code>__u16 pf_retrans</code>
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
<code>__be16 encap_port</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int probe_interval</code>
</li>
<li>
<b>Field added. </b>
<code>struct timer_list probe_timer</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) pl</code>
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
