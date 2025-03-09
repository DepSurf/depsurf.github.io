# Struct: <code>inet_connection_sock_af_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    int (*)(const struct sock *, const struct inet_bind_bucket *, bool) bind_conflict;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    int (*)(const struct sock *, const struct inet_bind_bucket *, bool) bind_conflict;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    int (*)(const struct sock *, const struct inet_bind_bucket *, bool, bool) bind_conflict;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
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
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
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
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inet_connection_sock_af_ops {
    int (*)(struct sock *, struct sk_buff *, struct flowi *) queue_xmit;
    void (*)(struct sock *, struct sk_buff *) send_check;
    int (*)(struct sock *) rebuild_header;
    void (*)(struct sock *, const struct sk_buff *) sk_rx_dst_set;
    int (*)(struct sock *, struct sk_buff *) conn_request;
    struct sock * (*)(const struct sock *, struct sk_buff *, struct request_sock *, struct dst_entry *, struct request_sock *, bool *) syn_recv_sock;
    u16 net_header_len;
    u16 net_frag_header_len;
    u16 sockaddr_len;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt;
    int (*)(struct sock *, int, int, char *, int *) compat_getsockopt;
    void (*)(struct sock *, struct sockaddr *) addr2sockaddr;
    void (*)(struct sock *) mtu_reduced;
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
<code>int (*)(const struct sock *, const struct inet_bind_bucket *, bool) bind_conflict</code> ➡️ <code>int (*)(const struct sock *, const struct inet_bind_bucket *, bool, bool) bind_conflict</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(const struct sock *, const struct inet_bind_bucket *, bool, bool) bind_conflict</code>
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
<code>int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, int *) compat_getsockopt</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct sock *, int, int, char *, unsigned int) setsockopt</code> ➡️ <code>int (*)(struct sock *, int, int, sockptr_t, unsigned int) setsockopt</code>
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
<b>Field removed. </b>
<code>u16 net_frag_header_len</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, int *) compat_getsockopt</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, unsigned int) compat_setsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, int *) compat_getsockopt</code>
</li>
</ul>
</details>
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
