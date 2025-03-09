# Struct: <code>bpf_sock_ops</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
    void * skb_data;
    void * skb_data_end;
    __u32 skb_len;
    __u32 skb_tcp_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
    void * skb_data;
    void * skb_data_end;
    __u32 skb_len;
    __u32 skb_tcp_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
    void * skb_data;
    void * skb_data_end;
    __u32 skb_len;
    __u32 skb_tcp_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
    void * skb_data;
    void * skb_data_end;
    __u32 skb_len;
    __u32 skb_tcp_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
    void * skb_data;
    void * skb_data_end;
    __u32 skb_len;
    __u32 skb_tcp_flags;
    __u64 skb_hwtstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
    void * skb_data;
    void * skb_data_end;
    __u32 skb_len;
    __u32 skb_tcp_flags;
    __u64 skb_hwtstamp;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
    void * skb_data;
    void * skb_data_end;
    __u32 skb_len;
    __u32 skb_tcp_flags;
    __u64 skb_hwtstamp;
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
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
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
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32[4] args;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
    __u32 is_fullsock;
    __u32 snd_cwnd;
    __u32 srtt_us;
    __u32 bpf_sock_ops_cb_flags;
    __u32 state;
    __u32 rtt_min;
    __u32 snd_ssthresh;
    __u32 rcv_nxt;
    __u32 snd_nxt;
    __u32 snd_una;
    __u32 mss_cache;
    __u32 ecn_flags;
    __u32 rate_delivered;
    __u32 rate_interval_us;
    __u32 packets_out;
    __u32 retrans_out;
    __u32 total_retrans;
    __u32 segs_in;
    __u32 data_segs_in;
    __u32 segs_out;
    __u32 data_segs_out;
    __u32 lost_out;
    __u32 sacked_out;
    __u32 sk_txhash;
    __u64 bytes_received;
    __u64 bytes_acked;
    struct bpf_sock * sk;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct bpf_sock_ops {
    __u32 op;
    __u32 reply;
    __u32[4] replylong;
    __u32 family;
    __u32 remote_ip4;
    __u32 local_ip4;
    __u32[4] remote_ip6;
    __u32[4] local_ip6;
    __u32 remote_port;
    __u32 local_port;
}
```
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
<code>__u32[4] args</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 is_fullsock</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 snd_cwnd</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 srtt_us</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 bpf_sock_ops_cb_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 state</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 rtt_min</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 snd_ssthresh</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 rcv_nxt</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 snd_nxt</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 snd_una</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 mss_cache</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 ecn_flags</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 rate_delivered</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 rate_interval_us</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 packets_out</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 retrans_out</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 total_retrans</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 segs_in</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 data_segs_in</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 segs_out</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 data_segs_out</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 lost_out</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 sacked_out</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 sk_txhash</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 bytes_received</code>
</li>
<li>
<b>Field added. </b>
<code>__u64 bytes_acked</code>
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
<b>Field added. </b>
<code>struct bpf_sock * sk</code>
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
<code>void * skb_data</code>
</li>
<li>
<b>Field added. </b>
<code>void * skb_data_end</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 skb_len</code>
</li>
<li>
<b>Field added. </b>
<code>__u32 skb_tcp_flags</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__u64 skb_hwtstamp</code>
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
