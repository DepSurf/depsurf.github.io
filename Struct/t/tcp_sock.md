# Struct: <code>tcp_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u64 bytes_acked;
    struct u64_stats_sync syncp;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 tsoffset;
    struct list_head tsq_node;
    long unsigned int tsq_flags;
    struct (anon) ucopy;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 thin_dupack;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 do_early_retrans;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u32 tlp_high_seq;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct rtt_meas[3] rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    u32 fackets_out;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct sk_buff_head out_of_order_queue;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 retransmit_high;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_acked;
    struct u64_stats_sync syncp;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 tsoffset;
    struct list_head tsq_node;
    long unsigned int tsq_flags;
    struct (anon) ucopy;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 thin_dupack;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 do_early_retrans;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u32 tlp_high_seq;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct rtt_meas[3] rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    u32 fackets_out;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct sk_buff_head out_of_order_queue;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 retransmit_high;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_acked;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 tsoffset;
    struct list_head tsq_node;
    struct (anon) ucopy;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 thin_dupack;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 do_early_retrans;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u32 tlp_high_seq;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 lost;
    u32 app_limited;
    struct skb_mstamp first_tx_mstamp;
    struct skb_mstamp delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    u32 fackets_out;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 retransmit_high;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_acked;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 tsoffset;
    struct list_head tsq_node;
    struct (anon) ucopy;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 unused1;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u32 tlp_high_seq;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    u32 fackets_out;
    struct hrtimer pacing_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_acked;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 unused1;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_acked;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u8 dup_ack_counter;
    u8 tlp_retrans;
    u8 unused;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 fastopen_client_fail;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u16 timeout_rehash;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    bool is_mptcp;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u8 dup_ack_counter;
    u8 tlp_retrans;
    u8 unused;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 fastopen_client_fail;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 save_syn;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 is_cwnd_limited;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u16 timeout_rehash;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    bool is_mptcp;
    bool syn_smc;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    struct saved_syn * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u8 dup_ack_counter;
    u8 tlp_retrans;
    u8 unused;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 fastopen_client_fail;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 save_syn;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 is_cwnd_limited;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u16 timeout_rehash;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    bool is_mptcp;
    bool syn_smc;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    struct saved_syn * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u8 dup_ack_counter;
    u8 tlp_retrans;
    u8 unused;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 fastopen_client_fail;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 save_syn;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 is_cwnd_limited;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u16 timeout_rehash;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    bool is_mptcp;
    bool syn_smc;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    struct saved_syn * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u8 dup_ack_counter;
    u8 tlp_retrans;
    u8 unused;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 fastopen_client_fail;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 save_syn;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 is_cwnd_limited;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u16 timeout_rehash;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    bool is_mptcp;
    bool (*)(const struct sock *) smc_hs_congested;
    bool syn_smc;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    struct saved_syn * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u8 dup_ack_counter;
    u8 tlp_retrans;
    u8 unused;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 fastopen_client_fail;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 save_syn;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 is_cwnd_limited;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 cwnd_usage_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u8 bpf_chg_cc_inprogress;
    u16 timeout_rehash;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 plb_rehash;
    u32 mtu_info;
    bool is_mptcp;
    bool (*)(const struct sock *) smc_hs_congested;
    bool syn_smc;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    struct saved_syn * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u8 dup_ack_counter;
    u8 tlp_retrans;
    u8 unused;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 fastopen_client_fail;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 save_syn;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 is_cwnd_limited;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 cwnd_usage_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u8 bpf_chg_cc_inprogress;
    u16 timeout_rehash;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 plb_rehash;
    u32 mtu_info;
    bool is_mptcp;
    bool (*)(const struct sock *) smc_hs_congested;
    bool syn_smc;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    struct saved_syn * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    __u8[0] __cacheline_group_begin__tcp_sock_read_tx;
    u32 max_window;
    u32 rcv_ssthresh;
    u32 reordering;
    u32 notsent_lowat;
    u16 gso_segs;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    __u8[0] __cacheline_group_end__tcp_sock_read_tx;
    __u8[0] __cacheline_group_begin__tcp_sock_read_txrx;
    u32 tsoffset;
    u32 snd_wnd;
    u32 mss_cache;
    u32 snd_cwnd;
    u32 prr_out;
    u32 lost_out;
    u32 sacked_out;
    u16 tcp_header_len;
    u8 scaling_ratio;
    u8 chrono_type;
    u8 repair;
    u8 tcp_usec_ts;
    u8 is_sack_reneg;
    u8 is_cwnd_limited;
    __u8[0] __cacheline_group_end__tcp_sock_read_txrx;
    __u8[0] __cacheline_group_begin__tcp_sock_read_rx;
    u32 copied_seq;
    u32 rcv_tstamp;
    u32 snd_wl1;
    u32 tlp_high_seq;
    u32 rttvar_us;
    u32 retrans_out;
    u16 advmss;
    u16 urg_data;
    u32 lost;
    struct minmax rtt_min;
    struct rb_root out_of_order_queue;
    u32 snd_ssthresh;
    __u8[0] __cacheline_group_end__tcp_sock_read_rx;
    __u8[0] __cacheline_group_begin__tcp_sock_write_tx;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u32 snd_sml;
    u32 chrono_start;
    u32[3] chrono_stat;
    u32 write_seq;
    u32 pushed_seq;
    u32 lsndtime;
    u32 mdev_us;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 rtt_seq;
    struct list_head tsorted_sent_queue;
    struct sk_buff * highest_sack;
    u8 ecn_flags;
    __u8[0] __cacheline_group_end__tcp_sock_write_tx;
    __u8[0] __cacheline_group_begin__tcp_sock_write_txrx;
    __be32 pred_flags;
    u32 rcv_nxt;
    u32 snd_nxt;
    u32 snd_una;
    u32 window_clamp;
    u32 srtt_us;
    u32 packets_out;
    u32 snd_up;
    u32 delivered;
    u32 delivered_ce;
    u32 app_limited;
    u32 rcv_wnd;
    struct tcp_options_received rx_opt;
    u8 nonagle;
    u8 rate_app_limited;
    __u8[0] __cacheline_group_end__tcp_sock_write_txrx;
    __u8[0] __cacheline_group_begin__tcp_sock_write_rx;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_wup;
    u32 max_packets_out;
    u32 cwnd_usage_seq;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_rtt_last_tsecr;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u64 bytes_acked;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    __u8[0] __cacheline_group_end__tcp_sock_write_rx;
    u32 dsack_dups;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    struct list_head tsq_node;
    struct tcp_rack rack;
    u8 compressed_ack;
    u8 dup_ack_counter;
    u8 tlp_retrans;
    u8 unused;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 fastopen_client_fail;
    u8 frto;
    u8 repair_queue;
    u8 save_syn;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u32 tcp_tx_delay;
    u32 mdev_max_us;
    u8 keepalive_probes;
    u32 reord_seen;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 rto_stamp;
    u16 total_rto;
    u16 total_rto_recoveries;
    u32 total_rto_time;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u8 bpf_chg_cc_inprogress;
    u16 timeout_rehash;
    u32 rcv_ooopack;
    struct (anon) mtu_probe;
    u32 plb_rehash;
    u32 mtu_info;
    bool is_mptcp;
    bool (*)(const struct sock *) smc_hs_congested;
    bool syn_smc;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_ao_info * ao_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    struct saved_syn * saved_syn;
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
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
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
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tcp_sock {
    struct inet_connection_sock inet_conn;
    u16 tcp_header_len;
    u16 gso_segs;
    __be32 pred_flags;
    u64 bytes_received;
    u32 segs_in;
    u32 data_segs_in;
    u32 rcv_nxt;
    u32 copied_seq;
    u32 rcv_wup;
    u32 snd_nxt;
    u32 segs_out;
    u32 data_segs_out;
    u64 bytes_sent;
    u64 bytes_acked;
    u32 dsack_dups;
    u32 snd_una;
    u32 snd_sml;
    u32 rcv_tstamp;
    u32 lsndtime;
    u32 last_oow_ack_time;
    u32 compressed_ack_rcv_nxt;
    u32 tsoffset;
    struct list_head tsq_node;
    struct list_head tsorted_sent_queue;
    u32 snd_wl1;
    u32 snd_wnd;
    u32 max_window;
    u32 mss_cache;
    u32 window_clamp;
    u32 rcv_ssthresh;
    struct tcp_rack rack;
    u16 advmss;
    u8 compressed_ack;
    u32 chrono_start;
    u32[3] chrono_stat;
    u8 chrono_type;
    u8 rate_app_limited;
    u8 fastopen_connect;
    u8 fastopen_no_cookie;
    u8 is_sack_reneg;
    u8 unused;
    u8 nonagle;
    u8 thin_lto;
    u8 recvmsg_inq;
    u8 repair;
    u8 frto;
    u8 repair_queue;
    u8 syn_data;
    u8 syn_fastopen;
    u8 syn_fastopen_exp;
    u8 syn_fastopen_ch;
    u8 syn_data_acked;
    u8 save_syn;
    u8 is_cwnd_limited;
    u8 syn_smc;
    u32 tlp_high_seq;
    u32 tcp_tx_delay;
    u64 tcp_wstamp_ns;
    u64 tcp_clock_cache;
    u64 tcp_mstamp;
    u32 srtt_us;
    u32 mdev_us;
    u32 mdev_max_us;
    u32 rttvar_us;
    u32 rtt_seq;
    struct minmax rtt_min;
    u32 packets_out;
    u32 retrans_out;
    u32 max_packets_out;
    u32 max_packets_seq;
    u16 urg_data;
    u8 ecn_flags;
    u8 keepalive_probes;
    u32 reordering;
    u32 reord_seen;
    u32 snd_up;
    struct tcp_options_received rx_opt;
    u32 snd_ssthresh;
    u32 snd_cwnd;
    u32 snd_cwnd_cnt;
    u32 snd_cwnd_clamp;
    u32 snd_cwnd_used;
    u32 snd_cwnd_stamp;
    u32 prior_cwnd;
    u32 prr_delivered;
    u32 prr_out;
    u32 delivered;
    u32 delivered_ce;
    u32 lost;
    u32 app_limited;
    u64 first_tx_mstamp;
    u64 delivered_mstamp;
    u32 rate_delivered;
    u32 rate_interval_us;
    u32 rcv_wnd;
    u32 write_seq;
    u32 notsent_lowat;
    u32 pushed_seq;
    u32 lost_out;
    u32 sacked_out;
    struct hrtimer pacing_timer;
    struct hrtimer compressed_ack_timer;
    struct sk_buff * lost_skb_hint;
    struct sk_buff * retransmit_skb_hint;
    struct rb_root out_of_order_queue;
    struct sk_buff * ooo_last_skb;
    struct tcp_sack_block[1] duplicate_sack;
    struct tcp_sack_block[4] selective_acks;
    struct tcp_sack_block[4] recv_sack_cache;
    struct sk_buff * highest_sack;
    int lost_cnt_hint;
    u32 prior_ssthresh;
    u32 high_seq;
    u32 retrans_stamp;
    u32 undo_marker;
    int undo_retrans;
    u64 bytes_retrans;
    u32 total_retrans;
    u32 urg_seq;
    unsigned int keepalive_time;
    unsigned int keepalive_intvl;
    int linger2;
    u8 bpf_sock_ops_cb_flags;
    u32 rcv_ooopack;
    u32 rcv_rtt_last_tsecr;
    struct (anon) rcv_rtt_est;
    struct (anon) rcvq_space;
    struct (anon) mtu_probe;
    u32 mtu_info;
    const struct tcp_sock_af_ops * af_specific;
    struct tcp_md5sig_info * md5sig_info;
    struct tcp_fastopen_request * fastopen_req;
    struct request_sock * fastopen_rsk;
    u32 * saved_syn;
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
<code>u32 data_segs_in</code>
</li>
<li>
<b>Field added. </b>
<code>u32 data_segs_out</code>
</li>
<li>
<b>Field added. </b>
<code>u32 delivered</code>
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
<code>u32 chrono_start</code>
</li>
<li>
<b>Field added. </b>
<code>u32[3] chrono_stat</code>
</li>
<li>
<b>Field added. </b>
<code>u8 chrono_type</code>
</li>
<li>
<b>Field added. </b>
<code>u8 rate_app_limited</code>
</li>
<li>
<b>Field added. </b>
<code>u32 lost</code>
</li>
<li>
<b>Field added. </b>
<code>u32 app_limited</code>
</li>
<li>
<b>Field added. </b>
<code>struct skb_mstamp first_tx_mstamp</code>
</li>
<li>
<b>Field added. </b>
<code>struct skb_mstamp delivered_mstamp</code>
</li>
<li>
<b>Field added. </b>
<code>u32 rate_delivered</code>
</li>
<li>
<b>Field added. </b>
<code>u32 rate_interval_us</code>
</li>
<li>
<b>Field added. </b>
<code>struct sk_buff * ooo_last_skb</code>
</li>
<li>
<b>Field removed. </b>
<code>struct u64_stats_sync syncp</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int tsq_flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct rtt_meas[3] rtt_min</code> ➡️ <code>struct minmax rtt_min</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct sk_buff_head out_of_order_queue</code> ➡️ <code>struct rb_root out_of_order_queue</code>
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
<code>u8 fastopen_connect</code>
</li>
<li>
<b>Field added. </b>
<code>u8 unused1</code>
</li>
<li>
<b>Field added. </b>
<code>u8 syn_fastopen_ch</code>
</li>
<li>
<b>Field added. </b>
<code>u64 tcp_mstamp</code>
</li>
<li>
<b>Field added. </b>
<code>struct hrtimer pacing_timer</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 thin_dupack</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 do_early_retrans</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 retransmit_high</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct skb_mstamp first_tx_mstamp</code> ➡️ <code>u64 first_tx_mstamp</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct skb_mstamp delivered_mstamp</code> ➡️ <code>u64 delivered_mstamp</code>
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
<code>struct list_head tsorted_sent_queue</code>
</li>
<li>
<b>Field added. </b>
<code>u8 fastopen_no_cookie</code>
</li>
<li>
<b>Field added. </b>
<code>u8 is_sack_reneg</code>
</li>
<li>
<b>Field added. </b>
<code>u8 syn_smc</code>
</li>
<li>
<b>Field removed. </b>
<code>struct (anon) ucopy</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 fackets_out</code>
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
<code>u8 compressed_ack</code>
</li>
<li>
<b>Field added. </b>
<code>u8 recvmsg_inq</code>
</li>
<li>
<b>Field added. </b>
<code>u32 delivered_ce</code>
</li>
<li>
<b>Field added. </b>
<code>struct hrtimer compressed_ack_timer</code>
</li>
<li>
<b>Field added. </b>
<code>u8 bpf_sock_ops_cb_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 unused1</code>
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
<code>u64 bytes_sent</code>
</li>
<li>
<b>Field added. </b>
<code>u32 dsack_dups</code>
</li>
<li>
<b>Field added. </b>
<code>u32 compressed_ack_rcv_nxt</code>
</li>
<li>
<b>Field added. </b>
<code>u64 tcp_wstamp_ns</code>
</li>
<li>
<b>Field added. </b>
<code>u64 tcp_clock_cache</code>
</li>
<li>
<b>Field added. </b>
<code>u32 reord_seen</code>
</li>
<li>
<b>Field added. </b>
<code>u64 bytes_retrans</code>
</li>
<li>
<b>Field added. </b>
<code>u32 rcv_rtt_last_tsecr</code>
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
<code>u32 tcp_tx_delay</code>
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
<code>u32 rcv_ooopack</code>
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
<code>u8 dup_ack_counter</code>
</li>
<li>
<b>Field added. </b>
<code>u8 tlp_retrans</code>
</li>
<li>
<b>Field added. </b>
<code>u8 fastopen_client_fail</code>
</li>
<li>
<b>Field added. </b>
<code>u16 timeout_rehash</code>
</li>
<li>
<b>Field added. </b>
<code>bool is_mptcp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>u8 syn_smc</code> ➡️ <code>bool syn_smc</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 * saved_syn</code> ➡️ <code>struct saved_syn * saved_syn</code>
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
<b>Field added. </b>
<code>bool (*)(const struct sock *) smc_hs_congested</code>
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
<code>u32 cwnd_usage_seq</code>
</li>
<li>
<b>Field added. </b>
<code>u8 bpf_chg_cc_inprogress</code>
</li>
<li>
<b>Field added. </b>
<code>u32 plb_rehash</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 max_packets_seq</code>
</li>
</ul>
</details>
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
<code>__u8[0] __cacheline_group_begin__tcp_sock_read_tx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_end__tcp_sock_read_tx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_begin__tcp_sock_read_txrx</code>
</li>
<li>
<b>Field added. </b>
<code>u8 scaling_ratio</code>
</li>
<li>
<b>Field added. </b>
<code>u8 tcp_usec_ts</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_end__tcp_sock_read_txrx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_begin__tcp_sock_read_rx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_end__tcp_sock_read_rx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_begin__tcp_sock_write_tx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_end__tcp_sock_write_tx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_begin__tcp_sock_write_txrx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_end__tcp_sock_write_txrx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_begin__tcp_sock_write_rx</code>
</li>
<li>
<b>Field added. </b>
<code>__u8[0] __cacheline_group_end__tcp_sock_write_rx</code>
</li>
<li>
<b>Field added. </b>
<code>u32 rto_stamp</code>
</li>
<li>
<b>Field added. </b>
<code>u16 total_rto</code>
</li>
<li>
<b>Field added. </b>
<code>u16 total_rto_recoveries</code>
</li>
<li>
<b>Field added. </b>
<code>u32 total_rto_time</code>
</li>
<li>
<b>Field added. </b>
<code>struct tcp_ao_info * ao_info</code>
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
