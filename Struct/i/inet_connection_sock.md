# Struct: <code>inet_connection_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[8] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[8] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[11] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[11] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[11] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[11] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[11] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_rto_min;
    __u32 icsk_delack_max;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_initialized;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_probes_tstamp;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_rto_min;
    __u32 icsk_delack_max;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_initialized;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_probes_tstamp;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_rto_min;
    __u32 icsk_delack_max;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_initialized;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_probes_tstamp;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_rto_min;
    __u32 icsk_delack_max;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_initialized;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_probes_tstamp;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    struct inet_bind2_bucket * icsk_bind2_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_rto_min;
    __u32 icsk_delack_max;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_initialized;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_probes_tstamp;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    struct inet_bind2_bucket * icsk_bind2_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_rto_min;
    __u32 icsk_delack_max;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_initialized;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_probes_tstamp;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    struct inet_bind2_bucket * icsk_bind2_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_rto_min;
    __u32 icsk_delack_max;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_initialized;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_probes_tstamp;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
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
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
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
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inet_connection_sock {
    struct inet_sock icsk_inet;
    struct request_sock_queue icsk_accept_queue;
    struct inet_bind_bucket * icsk_bind_hash;
    long unsigned int icsk_timeout;
    struct timer_list icsk_retransmit_timer;
    struct timer_list icsk_delack_timer;
    __u32 icsk_rto;
    __u32 icsk_pmtu_cookie;
    const struct tcp_congestion_ops * icsk_ca_ops;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    const struct tcp_ulp_ops * icsk_ulp_ops;
    void * icsk_ulp_data;
    void (*)(struct sock *, u32) icsk_clean_acked;
    struct hlist_node icsk_listen_portaddr_node;
    unsigned int (*)(struct sock *, u32) icsk_sync_mss;
    __u8 icsk_ca_state;
    __u8 icsk_ca_setsockopt;
    __u8 icsk_ca_dst_locked;
    __u8 icsk_retransmits;
    __u8 icsk_pending;
    __u8 icsk_backoff;
    __u8 icsk_syn_retries;
    __u8 icsk_probes_out;
    __u16 icsk_ext_hdr_len;
    struct (anon) icsk_ack;
    struct (anon) icsk_mtup;
    u32 icsk_user_timeout;
    u64[13] icsk_ca_priv;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u64[8] icsk_ca_priv</code> ➡️ <code>u64[11] icsk_ca_priv</code>
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
<code>const struct tcp_ulp_ops * icsk_ulp_ops</code>
</li>
<li>
<b>Field added. </b>
<code>void * icsk_ulp_data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct sock *, u32) icsk_clean_acked</code>
</li>
<li>
<b>Field added. </b>
<code>struct hlist_node icsk_listen_portaddr_node</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u64[11] icsk_ca_priv</code> ➡️ <code>u64[13] icsk_ca_priv</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 icsk_rto_min</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 icsk_delack_max</code>
</li>
<li>
<b>Field added. </b>
<code>__u8 icsk_ca_initialized</code>
</li>
<li>
<b>Field added. </b>
<code>u32 icsk_probes_tstamp</code>
</li>
</ul>
</details>
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
<b>Field removed. </b>
<code>struct hlist_node icsk_listen_portaddr_node</code>
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
<code>struct inet_bind2_bucket * icsk_bind2_hash</code>
</li>
</ul>
</details>
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
