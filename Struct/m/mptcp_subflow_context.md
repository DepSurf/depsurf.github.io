# Struct: <code>mptcp_subflow_context</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mptcp_subflow_context {
    struct list_head node;
    u64 local_key;
    u64 remote_key;
    u64 idsn;
    u64 map_seq;
    u32 snd_isn;
    u32 token;
    u32 rel_write_seq;
    u32 map_subflow_seq;
    u32 ssn_offset;
    u32 map_data_len;
    u32 request_mptcp;
    u32 request_join;
    u32 request_bkup;
    u32 mp_capable;
    u32 mp_join;
    u32 fully_established;
    u32 pm_notified;
    u32 conn_finished;
    u32 map_valid;
    u32 mpc_map;
    u32 backup;
    u32 data_avail;
    u32 rx_eof;
    u32 data_fin_tx_enable;
    u32 use_64bit_ack;
    u32 can_ack;
    u64 data_fin_tx_seq;
    u32 remote_nonce;
    u64 thmac;
    u32 local_nonce;
    u32 remote_token;
    u8[20] hmac;
    u8 local_id;
    u8 remote_id;
    struct sock * tcp_sock;
    struct sock * conn;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    void (*)(struct sock *) tcp_data_ready;
    void (*)(struct sock *) tcp_state_change;
    void (*)(struct sock *) tcp_write_space;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mptcp_subflow_context {
    struct list_head node;
    u64 local_key;
    u64 remote_key;
    u64 idsn;
    u64 map_seq;
    u32 snd_isn;
    u32 token;
    u32 rel_write_seq;
    u32 map_subflow_seq;
    u32 ssn_offset;
    u32 map_data_len;
    u32 request_mptcp;
    u32 request_join;
    u32 request_bkup;
    u32 mp_capable;
    u32 mp_join;
    u32 fully_established;
    u32 pm_notified;
    u32 conn_finished;
    u32 map_valid;
    u32 mpc_map;
    u32 backup;
    u32 rx_eof;
    u32 can_ack;
    u32 disposable;
    enum mptcp_data_avail data_avail;
    u32 remote_nonce;
    u64 thmac;
    u32 local_nonce;
    u32 remote_token;
    u8[20] hmac;
    u8 local_id;
    u8 remote_id;
    struct sock * tcp_sock;
    struct sock * conn;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    void (*)(struct sock *) tcp_data_ready;
    void (*)(struct sock *) tcp_state_change;
    void (*)(struct sock *) tcp_write_space;
    void (*)(struct sock *) tcp_error_report;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mptcp_subflow_context {
    struct list_head node;
    u64 local_key;
    u64 remote_key;
    u64 idsn;
    u64 map_seq;
    u32 snd_isn;
    u32 token;
    u32 rel_write_seq;
    u32 map_subflow_seq;
    u32 ssn_offset;
    u32 map_data_len;
    u32 request_mptcp;
    u32 request_join;
    u32 request_bkup;
    u32 mp_capable;
    u32 mp_join;
    u32 fully_established;
    u32 pm_notified;
    u32 conn_finished;
    u32 map_valid;
    u32 mpc_map;
    u32 backup;
    u32 send_mp_prio;
    u32 rx_eof;
    u32 can_ack;
    u32 disposable;
    enum mptcp_data_avail data_avail;
    u32 remote_nonce;
    u64 thmac;
    u32 local_nonce;
    u32 remote_token;
    u8[20] hmac;
    u8 local_id;
    u8 remote_id;
    u8 reset_seen;
    u8 reset_transient;
    u8 reset_reason;
    long int delegated_status;
    struct list_head delegated_node;
    u32 setsockopt_seq;
    struct sock * tcp_sock;
    struct sock * conn;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    void (*)(struct sock *) tcp_data_ready;
    void (*)(struct sock *) tcp_state_change;
    void (*)(struct sock *) tcp_write_space;
    void (*)(struct sock *) tcp_error_report;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mptcp_subflow_context {
    struct list_head node;
    u64 local_key;
    u64 remote_key;
    u64 idsn;
    u64 map_seq;
    u32 snd_isn;
    u32 token;
    u32 rel_write_seq;
    u32 map_subflow_seq;
    u32 ssn_offset;
    u32 map_data_len;
    __wsum map_data_csum;
    u32 map_csum_len;
    u32 request_mptcp;
    u32 request_join;
    u32 request_bkup;
    u32 mp_capable;
    u32 mp_join;
    u32 fully_established;
    u32 pm_notified;
    u32 conn_finished;
    u32 map_valid;
    u32 map_csum_reqd;
    u32 map_data_fin;
    u32 mpc_map;
    u32 backup;
    u32 send_mp_prio;
    u32 send_mp_fail;
    u32 rx_eof;
    u32 can_ack;
    u32 disposable;
    u32 stale;
    enum mptcp_data_avail data_avail;
    u32 remote_nonce;
    u64 thmac;
    u32 local_nonce;
    u32 remote_token;
    u8[20] hmac;
    u8 local_id;
    u8 remote_id;
    u8 reset_seen;
    u8 reset_transient;
    u8 reset_reason;
    u8 stale_count;
    long int delegated_status;
    struct list_head delegated_node;
    u32 setsockopt_seq;
    u32 stale_rcv_tstamp;
    struct sock * tcp_sock;
    struct sock * conn;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    void (*)(struct sock *) tcp_data_ready;
    void (*)(struct sock *) tcp_state_change;
    void (*)(struct sock *) tcp_write_space;
    void (*)(struct sock *) tcp_error_report;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mptcp_subflow_context {
    struct list_head node;
    long unsigned int avg_pacing_rate;
    u64 local_key;
    u64 remote_key;
    u64 idsn;
    u64 map_seq;
    u32 snd_isn;
    u32 token;
    u32 rel_write_seq;
    u32 map_subflow_seq;
    u32 ssn_offset;
    u32 map_data_len;
    __wsum map_data_csum;
    u32 map_csum_len;
    u32 request_mptcp;
    u32 request_join;
    u32 request_bkup;
    u32 mp_capable;
    u32 mp_join;
    u32 fully_established;
    u32 pm_notified;
    u32 conn_finished;
    u32 map_valid;
    u32 map_csum_reqd;
    u32 map_data_fin;
    u32 mpc_map;
    u32 backup;
    u32 send_mp_prio;
    u32 send_mp_fail;
    u32 send_fastclose;
    u32 send_infinite_map;
    u32 rx_eof;
    u32 can_ack;
    u32 disposable;
    u32 stale;
    u32 local_id_valid;
    u32 valid_csum_seen;
    enum mptcp_data_avail data_avail;
    u32 remote_nonce;
    u64 thmac;
    u32 local_nonce;
    u32 remote_token;
    u8[20] hmac;
    u8 local_id;
    u8 remote_id;
    u8 reset_seen;
    u8 reset_transient;
    u8 reset_reason;
    u8 stale_count;
    long int delegated_status;
    long unsigned int fail_tout;
    struct (anon) reset;
    struct list_head delegated_node;
    u32 setsockopt_seq;
    u32 stale_rcv_tstamp;
    struct sock * tcp_sock;
    struct sock * conn;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    void (*)(struct sock *) tcp_state_change;
    void (*)(struct sock *) tcp_error_report;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mptcp_subflow_context {
    struct list_head node;
    long unsigned int avg_pacing_rate;
    u64 local_key;
    u64 remote_key;
    u64 idsn;
    u64 map_seq;
    u32 snd_isn;
    u32 token;
    u32 rel_write_seq;
    u32 map_subflow_seq;
    u32 ssn_offset;
    u32 map_data_len;
    __wsum map_data_csum;
    u32 map_csum_len;
    u32 request_mptcp;
    u32 request_join;
    u32 request_bkup;
    u32 mp_capable;
    u32 mp_join;
    u32 fully_established;
    u32 pm_notified;
    u32 conn_finished;
    u32 map_valid;
    u32 map_csum_reqd;
    u32 map_data_fin;
    u32 mpc_map;
    u32 backup;
    u32 send_mp_prio;
    u32 send_mp_fail;
    u32 send_fastclose;
    u32 send_infinite_map;
    u32 rx_eof;
    u32 remote_key_valid;
    u32 disposable;
    u32 stale;
    u32 local_id_valid;
    u32 valid_csum_seen;
    u32 is_mptfo;
    u32 __unused;
    enum mptcp_data_avail data_avail;
    u32 remote_nonce;
    u64 thmac;
    u32 local_nonce;
    u32 remote_token;
    u8[20] hmac;
    u64 iasn;
    u8 local_id;
    u8 remote_id;
    u8 reset_seen;
    u8 reset_transient;
    u8 reset_reason;
    u8 stale_count;
    long int delegated_status;
    long unsigned int fail_tout;
    struct (anon) reset;
    struct list_head delegated_node;
    u32 setsockopt_seq;
    u32 stale_rcv_tstamp;
    struct sock * tcp_sock;
    struct sock * conn;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    void (*)(struct sock *) tcp_state_change;
    void (*)(struct sock *) tcp_error_report;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mptcp_subflow_context {
    struct list_head node;
    long unsigned int avg_pacing_rate;
    u64 local_key;
    u64 remote_key;
    u64 idsn;
    u64 map_seq;
    u32 snd_isn;
    u32 token;
    u32 rel_write_seq;
    u32 map_subflow_seq;
    u32 ssn_offset;
    u32 map_data_len;
    __wsum map_data_csum;
    u32 map_csum_len;
    u32 request_mptcp;
    u32 request_join;
    u32 request_bkup;
    u32 mp_capable;
    u32 mp_join;
    u32 fully_established;
    u32 pm_notified;
    u32 conn_finished;
    u32 map_valid;
    u32 map_csum_reqd;
    u32 map_data_fin;
    u32 mpc_map;
    u32 backup;
    u32 send_mp_prio;
    u32 send_mp_fail;
    u32 send_fastclose;
    u32 send_infinite_map;
    u32 remote_key_valid;
    u32 disposable;
    u32 stale;
    u32 local_id_valid;
    u32 valid_csum_seen;
    u32 is_mptfo;
    u32 __unused;
    enum mptcp_data_avail data_avail;
    u32 remote_nonce;
    u64 thmac;
    u32 local_nonce;
    u32 remote_token;
    u8[20] hmac;
    u64 iasn;
    u8 local_id;
    u8 remote_id;
    u8 reset_seen;
    u8 reset_transient;
    u8 reset_reason;
    u8 stale_count;
    u32 subflow_id;
    long int delegated_status;
    long unsigned int fail_tout;
    struct (anon) reset;
    struct list_head delegated_node;
    u32 setsockopt_seq;
    u32 stale_rcv_tstamp;
    struct sock * tcp_sock;
    struct sock * conn;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    void (*)(struct sock *) tcp_state_change;
    void (*)(struct sock *) tcp_error_report;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mptcp_subflow_context {
    struct list_head node;
    long unsigned int avg_pacing_rate;
    u64 local_key;
    u64 remote_key;
    u64 idsn;
    u64 map_seq;
    u32 snd_isn;
    u32 token;
    u32 rel_write_seq;
    u32 map_subflow_seq;
    u32 ssn_offset;
    u32 map_data_len;
    __wsum map_data_csum;
    u32 map_csum_len;
    u32 request_mptcp;
    u32 request_join;
    u32 request_bkup;
    u32 mp_capable;
    u32 mp_join;
    u32 fully_established;
    u32 pm_notified;
    u32 conn_finished;
    u32 map_valid;
    u32 map_csum_reqd;
    u32 map_data_fin;
    u32 mpc_map;
    u32 backup;
    u32 send_mp_prio;
    u32 send_mp_fail;
    u32 send_fastclose;
    u32 send_infinite_map;
    u32 remote_key_valid;
    u32 disposable;
    u32 stale;
    u32 valid_csum_seen;
    u32 is_mptfo;
    u32 __unused;
    bool data_avail;
    bool scheduled;
    u32 remote_nonce;
    u64 thmac;
    u32 local_nonce;
    u32 remote_token;
    u8[20] hmac;
    u64 iasn;
    s16 local_id;
    u8 remote_id;
    u8 reset_seen;
    u8 reset_transient;
    u8 reset_reason;
    u8 stale_count;
    u32 subflow_id;
    long int delegated_status;
    long unsigned int fail_tout;
    struct (anon) reset;
    struct list_head delegated_node;
    u32 setsockopt_seq;
    u32 stale_rcv_tstamp;
    int cached_sndbuf;
    struct sock * tcp_sock;
    struct sock * conn;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    void (*)(struct sock *) tcp_state_change;
    void (*)(struct sock *) tcp_error_report;
    struct callback_head rcu;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct mptcp_subflow_context {
    struct list_head node;
    u64 local_key;
    u64 remote_key;
    u64 idsn;
    u64 map_seq;
    u32 snd_isn;
    u32 token;
    u32 rel_write_seq;
    u32 map_subflow_seq;
    u32 ssn_offset;
    u32 map_data_len;
    u32 request_mptcp;
    u32 request_join;
    u32 request_bkup;
    u32 mp_capable;
    u32 mp_join;
    u32 fully_established;
    u32 pm_notified;
    u32 conn_finished;
    u32 map_valid;
    u32 mpc_map;
    u32 backup;
    u32 data_avail;
    u32 rx_eof;
    u32 data_fin_tx_enable;
    u32 use_64bit_ack;
    u32 can_ack;
    u64 data_fin_tx_seq;
    u32 remote_nonce;
    u64 thmac;
    u32 local_nonce;
    u32 remote_token;
    u8[20] hmac;
    u8 local_id;
    u8 remote_id;
    struct sock * tcp_sock;
    struct sock * conn;
    const struct inet_connection_sock_af_ops * icsk_af_ops;
    void (*)(struct sock *) tcp_data_ready;
    void (*)(struct sock *) tcp_state_change;
    void (*)(struct sock *) tcp_write_space;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 disposable</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct sock *) tcp_error_report</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 data_fin_tx_enable</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 use_64bit_ack</code>
</li>
<li>
<b>Field removed. </b>
<code>u64 data_fin_tx_seq</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 data_avail</code> ➡️ <code>enum mptcp_data_avail data_avail</code>
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
<code>u32 send_mp_prio</code>
</li>
<li>
<b>Field added. </b>
<code>u8 reset_seen</code>
</li>
<li>
<b>Field added. </b>
<code>u8 reset_transient</code>
</li>
<li>
<b>Field added. </b>
<code>u8 reset_reason</code>
</li>
<li>
<b>Field added. </b>
<code>long int delegated_status</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head delegated_node</code>
</li>
<li>
<b>Field added. </b>
<code>u32 setsockopt_seq</code>
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
<code>__wsum map_data_csum</code>
</li>
<li>
<b>Field added. </b>
<code>u32 map_csum_len</code>
</li>
<li>
<b>Field added. </b>
<code>u32 map_csum_reqd</code>
</li>
<li>
<b>Field added. </b>
<code>u32 map_data_fin</code>
</li>
<li>
<b>Field added. </b>
<code>u32 send_mp_fail</code>
</li>
<li>
<b>Field added. </b>
<code>u32 stale</code>
</li>
<li>
<b>Field added. </b>
<code>u8 stale_count</code>
</li>
<li>
<b>Field added. </b>
<code>u32 stale_rcv_tstamp</code>
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
<code>long unsigned int avg_pacing_rate</code>
</li>
<li>
<b>Field added. </b>
<code>u32 send_fastclose</code>
</li>
<li>
<b>Field added. </b>
<code>u32 send_infinite_map</code>
</li>
<li>
<b>Field added. </b>
<code>u32 local_id_valid</code>
</li>
<li>
<b>Field added. </b>
<code>u32 valid_csum_seen</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int fail_tout</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) reset</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct sock *) tcp_data_ready</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct sock *) tcp_write_space</code>
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
<code>u32 remote_key_valid</code>
</li>
<li>
<b>Field added. </b>
<code>u32 is_mptfo</code>
</li>
<li>
<b>Field added. </b>
<code>u32 __unused</code>
</li>
<li>
<b>Field added. </b>
<code>u64 iasn</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 can_ack</code>
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
<code>u32 subflow_id</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 rx_eof</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool scheduled</code>
</li>
<li>
<b>Field added. </b>
<code>int cached_sndbuf</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 local_id_valid</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum mptcp_data_avail data_avail</code> ➡️ <code>bool data_avail</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8 local_id</code> ➡️ <code>s16 local_id</code>
</li>
</ul>
</details>
</li>
</ul>
