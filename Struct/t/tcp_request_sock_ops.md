# Struct: <code>tcp_request_sock_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *, bool *) route_req;
    __u32 (*)(const struct sk_buff *) init_seq;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, bool) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *, bool *) route_req;
    __u32 (*)(const struct sk_buff *) init_seq;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *, bool *) route_req;
    __u32 (*)(const struct sk_buff *, u32 *) init_seq;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct sk_buff *, struct flowi *, struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type, struct sk_buff *) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct sk_buff *, struct flowi *, struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type, struct sk_buff *) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct sk_buff *, struct flowi *, struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type, struct sk_buff *) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct sk_buff *, struct flowi *, struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type, struct sk_buff *) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct sk_buff *, struct flowi *, struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type, struct sk_buff *) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct sk_buff *, struct flowi *, struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type, struct sk_buff *) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    struct tcp_ao_key * (*)(const struct sock *, struct request_sock *, int, int) ao_lookup;
    int (*)(struct tcp_ao_key *, u8 *, struct request_sock *) ao_calc_key;
    int (*)(char *, struct tcp_ao_key *, struct request_sock *, const struct sk_buff *, int, u32) ao_synack_hash;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct sk_buff *, struct flowi *, struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type, struct sk_buff *) send_synack;
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
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
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
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tcp_request_sock_ops {
    u16 mss_clamp;
    struct tcp_md5sig_key * (*)(const struct sock *, const struct sock *) req_md5_lookup;
    int (*)(char *, const struct tcp_md5sig_key *, const struct sock *, const struct sk_buff *) calc_md5_hash;
    void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req;
    __u32 (*)(const struct sk_buff *, __u16 *) cookie_init_seq;
    struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req;
    u32 (*)(const struct sk_buff *) init_seq;
    u32 (*)(const struct net *, const struct sk_buff *) init_ts_off;
    int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack;
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
<code>int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, bool) send_synack</code> ➡️ <code>int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>__u32 (*)(const struct sk_buff *) init_seq</code> ➡️ <code>__u32 (*)(const struct sk_buff *, u32 *) init_seq</code>
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
<code>u32 (*)(const struct net *, const struct sk_buff *) init_ts_off</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *, bool *) route_req</code> ➡️ <code>struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 (*)(const struct sk_buff *, u32 *) init_seq</code> ➡️ <code>u32 (*)(const struct sk_buff *) init_seq</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(struct request_sock *, const struct sock *, struct sk_buff *) init_req</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct dst_entry * (*)(const struct sock *, struct flowi *, const struct request_sock *) route_req</code> ➡️ <code>struct dst_entry * (*)(const struct sock *, struct sk_buff *, struct flowi *, struct request_sock *) route_req</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type) send_synack</code> ➡️ <code>int (*)(const struct sock *, struct dst_entry *, struct flowi *, struct request_sock *, struct tcp_fastopen_cookie *, enum tcp_synack_type, struct sk_buff *) send_synack</code>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
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
<code>struct tcp_ao_key * (*)(const struct sock *, struct request_sock *, int, int) ao_lookup</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct tcp_ao_key *, u8 *, struct request_sock *) ao_calc_key</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(char *, struct tcp_ao_key *, struct request_sock *, const struct sk_buff *, int, u32) ao_synack_hash</code>
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
