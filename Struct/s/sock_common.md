# Struct: <code>sock_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_nulls_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    int skc_tx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    atomic_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    int skc_tx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    atomic_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    int skc_tx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    atomic_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    int skc_tx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    int skc_tx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    int skc_tx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
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
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
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
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sock_common {
    __addrpair skc_addrpair;
    __be32 skc_daddr;
    __be32 skc_rcv_saddr;
    unsigned int skc_hash;
    __u16[2] skc_u16hashes;
    __portpair skc_portpair;
    __be16 skc_dport;
    __u16 skc_num;
    short unsigned int skc_family;
    volatile unsigned char skc_state;
    unsigned char skc_reuse;
    unsigned char skc_reuseport;
    unsigned char skc_ipv6only;
    unsigned char skc_net_refcnt;
    int skc_bound_dev_if;
    struct hlist_node skc_bind_node;
    struct hlist_node skc_portaddr_node;
    struct proto * skc_prot;
    possible_net_t skc_net;
    struct in6_addr skc_v6_daddr;
    struct in6_addr skc_v6_rcv_saddr;
    atomic64_t skc_cookie;
    long unsigned int skc_flags;
    struct sock * skc_listener;
    struct inet_timewait_death_row * skc_tw_dr;
    int[0] skc_dontcopy_begin;
    struct hlist_node skc_node;
    struct hlist_nulls_node skc_nulls_node;
    short unsigned int skc_tx_queue_mapping;
    short unsigned int skc_rx_queue_mapping;
    int skc_incoming_cpu;
    u32 skc_rcv_wnd;
    u32 skc_tw_rcv_nxt;
    refcount_t skc_refcnt;
    int[0] skc_dontcopy_end;
    u32 skc_rxhash;
    u32 skc_window_clamp;
    u32 skc_tw_snd_nxt;
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
<code>struct hlist_nulls_node skc_portaddr_node</code> ➡️ <code>struct hlist_node skc_portaddr_node</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_t skc_refcnt</code> ➡️ <code>refcount_t skc_refcnt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>short unsigned int skc_rx_queue_mapping</code>
</li>
<li>
<b>Field type changed. </b>
<code>int skc_tx_queue_mapping</code> ➡️ <code>short unsigned int skc_tx_queue_mapping</code>
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
