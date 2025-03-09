# Struct: <code>tcp_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u8 tcpi_fastopen_client_fail;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u8 tcpi_fastopen_client_fail;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u8 tcpi_fastopen_client_fail;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u8 tcpi_fastopen_client_fail;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u8 tcpi_fastopen_client_fail;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u8 tcpi_fastopen_client_fail;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
    __u32 tcpi_rcv_wnd;
    __u32 tcpi_rehash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u8 tcpi_fastopen_client_fail;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
    __u32 tcpi_rcv_wnd;
    __u32 tcpi_rehash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u8 tcpi_fastopen_client_fail;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
    __u32 tcpi_rcv_wnd;
    __u32 tcpi_rehash;
    __u16 tcpi_total_rto;
    __u16 tcpi_total_rto_recoveries;
    __u32 tcpi_total_rto_time;
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
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
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
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tcp_info {
    __u8 tcpi_state;
    __u8 tcpi_ca_state;
    __u8 tcpi_retransmits;
    __u8 tcpi_probes;
    __u8 tcpi_backoff;
    __u8 tcpi_options;
    __u8 tcpi_snd_wscale;
    __u8 tcpi_rcv_wscale;
    __u8 tcpi_delivery_rate_app_limited;
    __u32 tcpi_rto;
    __u32 tcpi_ato;
    __u32 tcpi_snd_mss;
    __u32 tcpi_rcv_mss;
    __u32 tcpi_unacked;
    __u32 tcpi_sacked;
    __u32 tcpi_lost;
    __u32 tcpi_retrans;
    __u32 tcpi_fackets;
    __u32 tcpi_last_data_sent;
    __u32 tcpi_last_ack_sent;
    __u32 tcpi_last_data_recv;
    __u32 tcpi_last_ack_recv;
    __u32 tcpi_pmtu;
    __u32 tcpi_rcv_ssthresh;
    __u32 tcpi_rtt;
    __u32 tcpi_rttvar;
    __u32 tcpi_snd_ssthresh;
    __u32 tcpi_snd_cwnd;
    __u32 tcpi_advmss;
    __u32 tcpi_reordering;
    __u32 tcpi_rcv_rtt;
    __u32 tcpi_rcv_space;
    __u32 tcpi_total_retrans;
    __u64 tcpi_pacing_rate;
    __u64 tcpi_max_pacing_rate;
    __u64 tcpi_bytes_acked;
    __u64 tcpi_bytes_received;
    __u32 tcpi_segs_out;
    __u32 tcpi_segs_in;
    __u32 tcpi_notsent_bytes;
    __u32 tcpi_min_rtt;
    __u32 tcpi_data_segs_in;
    __u32 tcpi_data_segs_out;
    __u64 tcpi_delivery_rate;
    __u64 tcpi_busy_time;
    __u64 tcpi_rwnd_limited;
    __u64 tcpi_sndbuf_limited;
    __u32 tcpi_delivered;
    __u32 tcpi_delivered_ce;
    __u64 tcpi_bytes_sent;
    __u64 tcpi_bytes_retrans;
    __u32 tcpi_dsack_dups;
    __u32 tcpi_reord_seen;
    __u32 tcpi_rcv_ooopack;
    __u32 tcpi_snd_wnd;
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
<code>__u32 tcpi_notsent_bytes</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 tcpi_min_rtt</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 tcpi_data_segs_in</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 tcpi_data_segs_out</code>
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
<code>__u8 tcpi_delivery_rate_app_limited</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 tcpi_delivery_rate</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 tcpi_busy_time</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 tcpi_rwnd_limited</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 tcpi_sndbuf_limited</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<code>__u32 tcpi_delivered</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 tcpi_delivered_ce</code>
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
<code>__u64 tcpi_bytes_sent</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 tcpi_bytes_retrans</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 tcpi_dsack_dups</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 tcpi_reord_seen</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 tcpi_rcv_ooopack</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 tcpi_snd_wnd</code>
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
<code>__u8 tcpi_fastopen_client_fail</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u32 tcpi_rcv_wnd</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 tcpi_rehash</code>
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
<code>__u16 tcpi_total_rto</code>
</li>
<li>
<b>Field added. </b>
<code>__u16 tcpi_total_rto_recoveries</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 tcpi_total_rto_time</code>
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
