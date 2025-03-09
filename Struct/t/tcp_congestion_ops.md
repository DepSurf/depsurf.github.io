# Struct: <code>tcp_congestion_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, u32, s32) pkts_acked;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) tso_segs_goal;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) tso_segs_goal;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) tso_segs_goal;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    u32 (*)(struct sock *) undo_cwnd;
    u32 (*)(struct sock *) sndbuf_expand;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    u32 (*)(struct sock *) undo_cwnd;
    u32 (*)(struct sock *) sndbuf_expand;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    u32 (*)(struct sock *) undo_cwnd;
    u32 (*)(struct sock *) sndbuf_expand;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    u32 (*)(struct sock *) undo_cwnd;
    u32 (*)(struct sock *) sndbuf_expand;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    u32 (*)(struct sock *) undo_cwnd;
    u32 (*)(struct sock *) sndbuf_expand;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    u32 (*)(struct sock *) undo_cwnd;
    u32 (*)(struct sock *) sndbuf_expand;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
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
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
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
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tcp_congestion_ops {
    struct list_head list;
    u32 key;
    u32 flags;
    void (*)(struct sock *) init;
    void (*)(struct sock *) release;
    u32 (*)(struct sock *) ssthresh;
    void (*)(struct sock *, u32, u32) cong_avoid;
    void (*)(struct sock *, u8) set_state;
    void (*)(struct sock *, enum tcp_ca_event) cwnd_event;
    void (*)(struct sock *, u32) in_ack_event;
    u32 (*)(struct sock *) undo_cwnd;
    void (*)(struct sock *, const struct ack_sample *) pkts_acked;
    u32 (*)(struct sock *) min_tso_segs;
    u32 (*)(struct sock *) sndbuf_expand;
    void (*)(struct sock *, const struct rate_sample *) cong_control;
    size_t (*)(struct sock *, u32, int *, union tcp_cc_info *) get_info;
    char[16] name;
    struct module * owner;
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
<b>Field type changed. </b>
<code>void (*)(struct sock *, u32, s32) pkts_acked</code> ➡️ <code>void (*)(struct sock *, const struct ack_sample *) pkts_acked</code>
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
<code>u32 (*)(struct sock *) tso_segs_goal</code>
</li>
<li>
<b>Field added. </b>
<code>u32 (*)(struct sock *) sndbuf_expand</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct sock *, const struct rate_sample *) cong_control</code>
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
<code>u32 (*)(struct sock *) min_tso_segs</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 (*)(struct sock *) tso_segs_goal</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
