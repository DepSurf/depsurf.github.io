# Struct: <code>rpc_rqst</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    __u32 * rq_buffer;
    size_t rq_callsize;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    void * rq_xprtdata;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    void * rq_xprtdata;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    void * rq_xprtdata;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_minortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_minortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_minortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_minortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_minortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_minortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct lwq_node rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
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
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
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
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    __u32 * rq_buffer;
    size_t rq_callsize;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * rq_xprtdata</code>
</li>
<li>
<b>Field added. </b>
<code>void * rq_rbuffer</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 * rq_buffer</code> ➡️ <code>void * rq_buffer</code>
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
<b>Field removed. </b>
<code>void * rq_xprtdata</code>
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
<code>struct rb_node rq_recv</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head rq_xmit</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head rq_xmit2</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t rq_pin</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct rpc_rqst {
    struct rpc_xprt * rq_xprt;
    struct xdr_buf rq_snd_buf;
    struct xdr_buf rq_rcv_buf;
    struct rpc_task * rq_task;
    struct rpc_cred * rq_cred;
    __be32 rq_xid;
    int rq_cong;
    u32 rq_seqno;
    int rq_enc_pages_num;
    struct page * * rq_enc_pages;
    void (*)(struct rpc_rqst *) rq_release_snd_buf;
    struct list_head rq_list;
    struct rb_node rq_recv;
    struct list_head rq_xmit;
    struct list_head rq_xmit2;
    void * rq_buffer;
    size_t rq_callsize;
    void * rq_rbuffer;
    size_t rq_rcvsize;
    size_t rq_xmit_bytes_sent;
    size_t rq_reply_bytes_recvd;
    struct xdr_buf rq_private_buf;
    long unsigned int rq_majortimeo;
    long unsigned int rq_minortimeo;
    long unsigned int rq_timeout;
    ktime_t rq_rtt;
    unsigned int rq_retries;
    unsigned int rq_connect_cookie;
    atomic_t rq_pin;
    u32 rq_bytes_sent;
    ktime_t rq_xtime;
    int rq_ntrans;
    struct list_head rq_bc_list;
    long unsigned int rq_bc_pa_state;
    struct list_head rq_bc_pa_list;
}
```
</details>
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
<b>Field type changed. </b>
<code>struct list_head rq_bc_list</code> ➡️ <code>struct lwq_node rq_bc_list</code>
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
