# Struct: <code>udp_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    __u16 len;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    void (*)(struct sock *) encap_destroy;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    __u16 len;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * * (*)(struct sock *, struct sk_buff * *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    __u16 len;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * * (*)(struct sock *, struct sk_buff * *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    __u16 len;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * * (*)(struct sock *, struct sk_buff * *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    __u16 len;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * * (*)(struct sock *, struct sk_buff * *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * * (*)(struct sock *, struct sk_buff * *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    unsigned char accept_udp_l4;
    unsigned char accept_udp_fraglist;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    unsigned char accept_udp_l4;
    unsigned char accept_udp_fraglist;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    unsigned char accept_udp_l4;
    unsigned char accept_udp_fraglist;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    unsigned char accept_udp_l4;
    unsigned char accept_udp_fraglist;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) encap_err_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
    int forward_threshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    unsigned char accept_udp_l4;
    unsigned char accept_udp_fraglist;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) encap_err_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
    int forward_threshold;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    long unsigned int udp_flags;
    int pending;
    __u8 encap_type;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) encap_err_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
    int forward_threshold;
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
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
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
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct udp_sock {
    struct inet_sock inet;
    int pending;
    unsigned int corkflag;
    __u8 encap_type;
    unsigned char no_check6_tx;
    unsigned char no_check6_rx;
    unsigned char encap_enabled;
    unsigned char gro_enabled;
    __u16 len;
    __u16 gso_size;
    __u16 pcslen;
    __u16 pcrlen;
    __u8 pcflag;
    __u8[3] unused;
    int (*)(struct sock *, struct sk_buff *) encap_rcv;
    int (*)(struct sock *, struct sk_buff *) encap_err_lookup;
    void (*)(struct sock *) encap_destroy;
    struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive;
    int (*)(struct sock *, struct sk_buff *, int) gro_complete;
    struct sk_buff_head reader_queue;
    int forward_deficit;
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
<code>struct sk_buff * * (*)(struct sock *, struct sk_buff * *, struct sk_buff *) gro_receive</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, struct sk_buff *, int) gro_complete</code>
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
<code>int forward_deficit</code>
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
<code>struct sk_buff_head reader_queue</code>
</li>
</ul>
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
<code>__u16 gso_size</code>
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
<code>unsigned char encap_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char gro_enabled</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct sock *, struct sk_buff *) encap_err_lookup</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct sk_buff * * (*)(struct sock *, struct sk_buff * *, struct sk_buff *) gro_receive</code> ➡️ <code>struct sk_buff * (*)(struct sock *, struct list_head *, struct sk_buff *) gro_receive</code>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned char accept_udp_l4</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char accept_udp_fraglist</code>
</li>
</ul>
</details>
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
<code>void (*)(struct sock *, struct sk_buff *, int, __be16, u32, u8 *) encap_err_rcv</code>
</li>
<li>
<b>Field added. </b>
<code>int forward_threshold</code>
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
<code>long unsigned int udp_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int corkflag</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char no_check6_tx</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char no_check6_rx</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char encap_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char gro_enabled</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char accept_udp_l4</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char accept_udp_fraglist</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8 pcflag</code>
</li>
<li>
<b>Field removed. </b>
<code>__u8[3] unused</code>
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
