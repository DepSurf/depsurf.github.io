# Struct: <code>tls_context</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct tls_context {
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    struct net_device * netdev;
    refcount_t refcount;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    u8 tx_conf;
    u8 rx_conf;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    long unsigned int flags;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void (*)(struct sock *) sk_destruct;
    void (*)(struct sock *, long int) sk_proto_close;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    long unsigned int flags;
    struct proto * sk_proto;
    void (*)(struct sock *) sk_destruct;
    void (*)(struct sock *, long int) sk_proto_close;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    struct sock * sk;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    struct sock * sk;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    u8 zerocopy_sendfile;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    struct sock * sk;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    u8 zerocopy_sendfile;
    u8 rx_no_pad;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    struct sock * sk;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    u8 zerocopy_sendfile;
    u8 rx_no_pad;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool splicing_pages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    struct sock * sk;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    u8 zerocopy_sendfile;
    u8 rx_no_pad;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool splicing_pages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    struct sock * sk;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
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
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
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
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tls_context {
    struct tls_prot_info prot_info;
    u8 tx_conf;
    u8 rx_conf;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    struct net_device * netdev;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    struct mutex tx_lock;
    long unsigned int flags;
    struct proto * sk_proto;
    void (*)(struct sock *) sk_destruct;
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    refcount_t refcount;
    struct callback_head rcu;
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct tls_context {
    union tls_crypto_context crypto_send;
    union tls_crypto_context crypto_recv;
    struct list_head list;
    struct net_device * netdev;
    refcount_t refcount;
    void * priv_ctx_tx;
    void * priv_ctx_rx;
    u8 tx_conf;
    u8 rx_conf;
    struct cipher_context tx;
    struct cipher_context rx;
    struct scatterlist * partially_sent_record;
    u16 partially_sent_offset;
    long unsigned int flags;
    bool in_tcp_sendpages;
    bool pending_open_record_frags;
    int (*)(struct sock *, int) push_pending_record;
    void (*)(struct sock *) sk_write_space;
    void (*)(struct sock *) sk_destruct;
    void (*)(struct sock *, long int) sk_proto_close;
    int (*)(struct sock *, int, int, char *, unsigned int) setsockopt;
    int (*)(struct sock *, int, int, char *, int *) getsockopt;
    int (*)(struct sock *) hash;
    void (*)(struct sock *) unhash;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct tls_prot_info prot_info</code>
</li>
<li>
<b>Field added. </b>
<code>struct proto * sk_proto</code>
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
<code>struct mutex tx_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head rcu</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct sock *, long int) sk_proto_close</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, unsigned int) setsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *, int, int, char *, int *) getsockopt</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct sock *) hash</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct sock *) unhash</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct sock * sk</code>
</li>
</ul>
</details>
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
<code>u8 zerocopy_sendfile</code>
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
<code>u8 rx_no_pad</code>
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
<code>bool splicing_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>bool in_tcp_sendpages</code>
</li>
</ul>
</details>
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
