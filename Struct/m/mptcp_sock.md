# Struct: <code>mptcp_sock</code>

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
struct mptcp_sock {
    struct inet_connection_sock sk;
    u64 local_key;
    u64 remote_key;
    u64 write_seq;
    u64 ack_seq;
    atomic64_t snd_una;
    long unsigned int timer_ival;
    u32 token;
    long unsigned int flags;
    bool can_ack;
    spinlock_t join_list_lock;
    struct work_struct work;
    struct list_head conn_list;
    struct list_head rtx_queue;
    struct list_head join_list;
    struct skb_ext * cached_ext;
    struct socket * subflow;
    struct sock * first;
    struct mptcp_pm_data pm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mptcp_sock {
    struct inet_connection_sock sk;
    u64 local_key;
    u64 remote_key;
    u64 write_seq;
    u64 snd_nxt;
    u64 ack_seq;
    u64 rcv_wnd_sent;
    u64 rcv_data_fin_seq;
    int wmem_reserved;
    struct sock * last_snd;
    int snd_burst;
    int old_wspace;
    u64 snd_una;
    u64 wnd_end;
    long unsigned int timer_ival;
    u32 token;
    int rmem_pending;
    int rmem_released;
    long unsigned int flags;
    bool can_ack;
    bool fully_established;
    bool rcv_data_fin;
    bool snd_data_fin_enable;
    bool rcv_fastclose;
    bool use_64bit_ack;
    spinlock_t join_list_lock;
    struct sock * ack_hint;
    struct work_struct work;
    struct sk_buff * ooo_last_skb;
    struct rb_root out_of_order_queue;
    struct sk_buff_head receive_queue;
    struct sk_buff_head skb_tx_cache;
    int tx_pending_data;
    int size_goal_cache;
    struct list_head conn_list;
    struct list_head rtx_queue;
    struct mptcp_data_frag * first_pending;
    struct list_head join_list;
    struct socket * subflow;
    struct sock * first;
    struct mptcp_pm_data pm;
    struct (anon) rcvq_space;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mptcp_sock {
    struct inet_connection_sock sk;
    u64 local_key;
    u64 remote_key;
    u64 write_seq;
    u64 snd_nxt;
    u64 ack_seq;
    u64 rcv_wnd_sent;
    u64 rcv_data_fin_seq;
    int wmem_reserved;
    struct sock * last_snd;
    int snd_burst;
    int old_wspace;
    u64 snd_una;
    u64 wnd_end;
    long unsigned int timer_ival;
    u32 token;
    int rmem_released;
    long unsigned int flags;
    bool can_ack;
    bool fully_established;
    bool rcv_data_fin;
    bool snd_data_fin_enable;
    bool rcv_fastclose;
    bool use_64bit_ack;
    spinlock_t join_list_lock;
    struct work_struct work;
    struct sk_buff * ooo_last_skb;
    struct rb_root out_of_order_queue;
    struct sk_buff_head receive_queue;
    struct sk_buff_head skb_tx_cache;
    int tx_pending_data;
    int size_goal_cache;
    struct list_head conn_list;
    struct list_head rtx_queue;
    struct mptcp_data_frag * first_pending;
    struct list_head join_list;
    struct socket * subflow;
    struct sock * first;
    struct mptcp_pm_data pm;
    struct (anon) rcvq_space;
    u32 setsockopt_seq;
    char[16] ca_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mptcp_sock {
    struct inet_connection_sock sk;
    u64 local_key;
    u64 remote_key;
    u64 write_seq;
    u64 snd_nxt;
    u64 ack_seq;
    u64 rcv_wnd_sent;
    u64 rcv_data_fin_seq;
    int wmem_reserved;
    struct sock * last_snd;
    int snd_burst;
    int old_wspace;
    u64 recovery_snd_nxt;
    u64 snd_una;
    u64 wnd_end;
    long unsigned int timer_ival;
    u32 token;
    int rmem_released;
    long unsigned int flags;
    bool recovery;
    bool can_ack;
    bool fully_established;
    bool rcv_data_fin;
    bool snd_data_fin_enable;
    bool rcv_fastclose;
    bool use_64bit_ack;
    bool csum_enabled;
    spinlock_t join_list_lock;
    struct work_struct work;
    struct sk_buff * ooo_last_skb;
    struct rb_root out_of_order_queue;
    struct sk_buff_head receive_queue;
    int tx_pending_data;
    struct list_head conn_list;
    struct list_head rtx_queue;
    struct mptcp_data_frag * first_pending;
    struct list_head join_list;
    struct socket * subflow;
    struct sock * first;
    struct mptcp_pm_data pm;
    struct (anon) rcvq_space;
    u32 setsockopt_seq;
    char[16] ca_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mptcp_sock {
    struct inet_connection_sock sk;
    u64 local_key;
    u64 remote_key;
    u64 write_seq;
    u64 snd_nxt;
    u64 ack_seq;
    atomic64_t rcv_wnd_sent;
    u64 rcv_data_fin_seq;
    int rmem_fwd_alloc;
    struct sock * last_snd;
    int snd_burst;
    int old_wspace;
    u64 recovery_snd_nxt;
    u64 snd_una;
    u64 wnd_end;
    long unsigned int timer_ival;
    u32 token;
    int rmem_released;
    long unsigned int flags;
    long unsigned int cb_flags;
    long unsigned int push_pending;
    bool recovery;
    bool can_ack;
    bool fully_established;
    bool rcv_data_fin;
    bool snd_data_fin_enable;
    bool rcv_fastclose;
    bool use_64bit_ack;
    bool csum_enabled;
    bool allow_infinite_fallback;
    u8 recvmsg_inq;
    u8 cork;
    u8 nodelay;
    struct work_struct work;
    struct sk_buff * ooo_last_skb;
    struct rb_root out_of_order_queue;
    struct sk_buff_head receive_queue;
    struct list_head conn_list;
    struct list_head rtx_queue;
    struct mptcp_data_frag * first_pending;
    struct list_head join_list;
    struct socket * subflow;
    struct sock * first;
    struct mptcp_pm_data pm;
    struct (anon) rcvq_space;
    u32 setsockopt_seq;
    char[16] ca_name;
    struct mptcp_sock * dl_next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mptcp_sock {
    struct inet_connection_sock sk;
    u64 local_key;
    u64 remote_key;
    u64 write_seq;
    u64 snd_nxt;
    u64 ack_seq;
    atomic64_t rcv_wnd_sent;
    u64 rcv_data_fin_seq;
    int rmem_fwd_alloc;
    struct sock * last_snd;
    int snd_burst;
    int old_wspace;
    u64 recovery_snd_nxt;
    u64 snd_una;
    u64 wnd_end;
    long unsigned int timer_ival;
    u32 token;
    int rmem_released;
    long unsigned int flags;
    long unsigned int cb_flags;
    long unsigned int push_pending;
    bool recovery;
    bool can_ack;
    bool fully_established;
    bool rcv_data_fin;
    bool snd_data_fin_enable;
    bool rcv_fastclose;
    bool use_64bit_ack;
    bool csum_enabled;
    bool allow_infinite_fallback;
    u8 mpc_endpoint_id;
    u8 recvmsg_inq;
    u8 cork;
    u8 nodelay;
    u8 fastopening;
    int connect_flags;
    struct work_struct work;
    struct sk_buff * ooo_last_skb;
    struct rb_root out_of_order_queue;
    struct sk_buff_head receive_queue;
    struct list_head conn_list;
    struct list_head rtx_queue;
    struct mptcp_data_frag * first_pending;
    struct list_head join_list;
    struct socket * subflow;
    struct sock * first;
    struct mptcp_pm_data pm;
    struct (anon) rcvq_space;
    u32 setsockopt_seq;
    char[16] ca_name;
    struct mptcp_sock * dl_next;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mptcp_sock {
    struct inet_connection_sock sk;
    u64 local_key;
    u64 remote_key;
    u64 write_seq;
    u64 bytes_sent;
    u64 snd_nxt;
    u64 bytes_received;
    u64 ack_seq;
    atomic64_t rcv_wnd_sent;
    u64 rcv_data_fin_seq;
    u64 bytes_retrans;
    int rmem_fwd_alloc;
    struct sock * last_snd;
    int snd_burst;
    int old_wspace;
    u64 recovery_snd_nxt;
    u64 bytes_acked;
    u64 snd_una;
    u64 wnd_end;
    long unsigned int timer_ival;
    u32 token;
    int rmem_released;
    long unsigned int flags;
    long unsigned int cb_flags;
    long unsigned int push_pending;
    bool recovery;
    bool can_ack;
    bool fully_established;
    bool rcv_data_fin;
    bool snd_data_fin_enable;
    bool rcv_fastclose;
    bool use_64bit_ack;
    bool csum_enabled;
    bool allow_infinite_fallback;
    u8 mpc_endpoint_id;
    u8 recvmsg_inq;
    u8 cork;
    u8 nodelay;
    u8 fastopening;
    u8 in_accept_queue;
    struct work_struct work;
    struct sk_buff * ooo_last_skb;
    struct rb_root out_of_order_queue;
    struct sk_buff_head receive_queue;
    struct list_head conn_list;
    struct list_head rtx_queue;
    struct mptcp_data_frag * first_pending;
    struct list_head join_list;
    struct socket * subflow;
    struct sock * first;
    struct mptcp_pm_data pm;
    struct (anon) rcvq_space;
    u32 subflow_id;
    u32 setsockopt_seq;
    char[16] ca_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mptcp_sock {
    struct inet_connection_sock sk;
    u64 local_key;
    u64 remote_key;
    u64 write_seq;
    u64 bytes_sent;
    u64 snd_nxt;
    u64 bytes_received;
    u64 ack_seq;
    atomic64_t rcv_wnd_sent;
    u64 rcv_data_fin_seq;
    u64 bytes_retrans;
    u64 bytes_consumed;
    int rmem_fwd_alloc;
    int snd_burst;
    int old_wspace;
    u64 recovery_snd_nxt;
    u64 bytes_acked;
    u64 snd_una;
    u64 wnd_end;
    long unsigned int timer_ival;
    u32 token;
    int rmem_released;
    long unsigned int flags;
    long unsigned int cb_flags;
    bool recovery;
    bool can_ack;
    bool fully_established;
    bool rcv_data_fin;
    bool snd_data_fin_enable;
    bool rcv_fastclose;
    bool use_64bit_ack;
    bool csum_enabled;
    bool allow_infinite_fallback;
    u8 pending_state;
    u8 mpc_endpoint_id;
    u8 recvmsg_inq;
    u8 cork;
    u8 nodelay;
    u8 fastopening;
    u8 in_accept_queue;
    u8 free_first;
    u8 rcvspace_init;
    struct work_struct work;
    struct sk_buff * ooo_last_skb;
    struct rb_root out_of_order_queue;
    struct sk_buff_head receive_queue;
    struct list_head conn_list;
    struct list_head rtx_queue;
    struct mptcp_data_frag * first_pending;
    struct list_head join_list;
    struct sock * first;
    struct mptcp_pm_data pm;
    struct mptcp_sched_ops * sched;
    struct (anon) rcvq_space;
    u8 scaling_ratio;
    u32 subflow_id;
    u32 setsockopt_seq;
    char[16] ca_name;
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
struct mptcp_sock {
    struct inet_connection_sock sk;
    u64 local_key;
    u64 remote_key;
    u64 write_seq;
    u64 ack_seq;
    atomic64_t snd_una;
    long unsigned int timer_ival;
    u32 token;
    long unsigned int flags;
    bool can_ack;
    spinlock_t join_list_lock;
    struct work_struct work;
    struct list_head conn_list;
    struct list_head rtx_queue;
    struct list_head join_list;
    struct skb_ext * cached_ext;
    struct socket * subflow;
    struct sock * first;
    struct mptcp_pm_data pm;
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
<code>u64 snd_nxt</code>
</li>
<li>
<b>Field added. </b>
<code>u64 rcv_wnd_sent</code>
</li>
<li>
<b>Field added. </b>
<code>u64 rcv_data_fin_seq</code>
</li>
<li>
<b>Field added. </b>
<code>int wmem_reserved</code>
</li>
<li>
<b>Field added. </b>
<code>struct sock * last_snd</code>
</li>
<li>
<b>Field added. </b>
<code>int snd_burst</code>
</li>
<li>
<b>Field added. </b>
<code>int old_wspace</code>
</li>
<li>
<b>Field added. </b>
<code>u64 wnd_end</code>
</li>
<li>
<b>Field added. </b>
<code>int rmem_pending</code>
</li>
<li>
<b>Field added. </b>
<code>int rmem_released</code>
</li>
<li>
<b>Field added. </b>
<code>bool fully_established</code>
</li>
<li>
<b>Field added. </b>
<code>bool rcv_data_fin</code>
</li>
<li>
<b>Field added. </b>
<code>bool snd_data_fin_enable</code>
</li>
<li>
<b>Field added. </b>
<code>bool rcv_fastclose</code>
</li>
<li>
<b>Field added. </b>
<code>bool use_64bit_ack</code>
</li>
<li>
<b>Field added. </b>
<code>struct sock * ack_hint</code>
</li>
<li>
<b>Field added. </b>
<code>struct sk_buff * ooo_last_skb</code>
</li>
<li>
<b>Field added. </b>
<code>struct rb_root out_of_order_queue</code>
</li>
<li>
<b>Field added. </b>
<code>struct sk_buff_head receive_queue</code>
</li>
<li>
<b>Field added. </b>
<code>struct sk_buff_head skb_tx_cache</code>
</li>
<li>
<b>Field added. </b>
<code>int tx_pending_data</code>
</li>
<li>
<b>Field added. </b>
<code>int size_goal_cache</code>
</li>
<li>
<b>Field added. </b>
<code>struct mptcp_data_frag * first_pending</code>
</li>
<li>
<b>Field added. </b>
<code>struct (anon) rcvq_space</code>
</li>
<li>
<b>Field removed. </b>
<code>struct skb_ext * cached_ext</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic64_t snd_una</code> ➡️ <code>u64 snd_una</code>
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
<code>u32 setsockopt_seq</code>
</li>
<li>
<b>Field added. </b>
<code>char[16] ca_name</code>
</li>
<li>
<b>Field removed. </b>
<code>int rmem_pending</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sock * ack_hint</code>
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
<code>u64 recovery_snd_nxt</code>
</li>
<li>
<b>Field added. </b>
<code>bool recovery</code>
</li>
<li>
<b>Field added. </b>
<code>bool csum_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sk_buff_head skb_tx_cache</code>
</li>
<li>
<b>Field removed. </b>
<code>int size_goal_cache</code>
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
<code>int rmem_fwd_alloc</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int cb_flags</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int push_pending</code>
</li>
<li>
<b>Field added. </b>
<code>bool allow_infinite_fallback</code>
</li>
<li>
<b>Field added. </b>
<code>u8 recvmsg_inq</code>
</li>
<li>
<b>Field added. </b>
<code>u8 cork</code>
</li>
<li>
<b>Field added. </b>
<code>u8 nodelay</code>
</li>
<li>
<b>Field added. </b>
<code>struct mptcp_sock * dl_next</code>
</li>
<li>
<b>Field removed. </b>
<code>int wmem_reserved</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t join_list_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>int tx_pending_data</code>
</li>
<li>
<b>Field type changed. </b>
<code>u64 rcv_wnd_sent</code> ➡️ <code>atomic64_t rcv_wnd_sent</code>
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
<code>u8 mpc_endpoint_id</code>
</li>
<li>
<b>Field added. </b>
<code>u8 fastopening</code>
</li>
<li>
<b>Field added. </b>
<code>int connect_flags</code>
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
<code>u64 bytes_sent</code>
</li>
<li>
<b>Field added. </b>
<code>u64 bytes_received</code>
</li>
<li>
<b>Field added. </b>
<code>u64 bytes_retrans</code>
</li>
<li>
<b>Field added. </b>
<code>u64 bytes_acked</code>
</li>
<li>
<b>Field added. </b>
<code>u8 in_accept_queue</code>
</li>
<li>
<b>Field added. </b>
<code>u32 subflow_id</code>
</li>
<li>
<b>Field removed. </b>
<code>int connect_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mptcp_sock * dl_next</code>
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
<code>u64 bytes_consumed</code>
</li>
<li>
<b>Field added. </b>
<code>u8 pending_state</code>
</li>
<li>
<b>Field added. </b>
<code>u8 free_first</code>
</li>
<li>
<b>Field added. </b>
<code>u8 rcvspace_init</code>
</li>
<li>
<b>Field added. </b>
<code>struct mptcp_sched_ops * sched</code>
</li>
<li>
<b>Field added. </b>
<code>u8 scaling_ratio</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sock * last_snd</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int push_pending</code>
</li>
<li>
<b>Field removed. </b>
<code>struct socket * subflow</code>
</li>
</ul>
</details>
</li>
</ul>
