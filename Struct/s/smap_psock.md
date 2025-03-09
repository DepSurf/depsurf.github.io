# Struct: <code>smap_psock</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct smap_psock {
    struct callback_head rcu;
    u32 refcnt;
    struct sk_buff_head rxqueue;
    bool strp_enabled;
    int save_rem;
    int save_off;
    struct sk_buff * save_skb;
    struct strparser strp;
    struct bpf_prog * bpf_parse;
    struct bpf_prog * bpf_verdict;
    struct list_head maps;
    struct sock * sock;
    long unsigned int state;
    struct work_struct tx_work;
    struct work_struct gc_work;
    void (*)(struct sock *) save_data_ready;
    void (*)(struct sock *) save_write_space;
    void (*)(struct sock *) save_state_change;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct smap_psock {
    struct callback_head rcu;
    refcount_t refcnt;
    struct sk_buff_head rxqueue;
    bool strp_enabled;
    int save_rem;
    int save_off;
    struct sk_buff * save_skb;
    struct sock * sk_redir;
    int apply_bytes;
    int cork_bytes;
    int sg_size;
    int eval;
    struct sk_msg_buff * cork;
    struct list_head ingress;
    struct strparser strp;
    struct bpf_prog * bpf_tx_msg;
    struct bpf_prog * bpf_parse;
    struct bpf_prog * bpf_verdict;
    struct list_head maps;
    spinlock_t maps_lock;
    struct sock * sock;
    long unsigned int state;
    struct work_struct tx_work;
    struct work_struct gc_work;
    struct proto * sk_proto;
    void (*)(struct sock *, long int) save_close;
    void (*)(struct sock *) save_data_ready;
    void (*)(struct sock *) save_write_space;
}
```
</details>
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct smap_psock {
    struct callback_head rcu;
    u32 refcnt;
    struct sk_buff_head rxqueue;
    bool strp_enabled;
    int save_rem;
    int save_off;
    struct sk_buff * save_skb;
    struct strparser strp;
    struct bpf_prog * bpf_parse;
    struct bpf_prog * bpf_verdict;
    struct list_head maps;
    struct sock * sock;
    long unsigned int state;
    struct work_struct tx_work;
    struct work_struct gc_work;
    void (*)(struct sock *) save_data_ready;
    void (*)(struct sock *) save_write_space;
    void (*)(struct sock *) save_state_change;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct sock * sk_redir</code>
</li>
<li>
<b>Field added. </b>
<code>int apply_bytes</code>
</li>
<li>
<b>Field added. </b>
<code>int cork_bytes</code>
</li>
<li>
<b>Field added. </b>
<code>int sg_size</code>
</li>
<li>
<b>Field added. </b>
<code>int eval</code>
</li>
<li>
<b>Field added. </b>
<code>struct sk_msg_buff * cork</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head ingress</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_prog * bpf_tx_msg</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t maps_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct proto * sk_proto</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct sock *, long int) save_close</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct sock *) save_state_change</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 refcnt</code> ➡️ <code>refcount_t refcnt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct smap_psock {
    struct callback_head rcu;
    refcount_t refcnt;
    struct sk_buff_head rxqueue;
    bool strp_enabled;
    int save_rem;
    int save_off;
    struct sk_buff * save_skb;
    struct sock * sk_redir;
    int apply_bytes;
    int cork_bytes;
    int sg_size;
    int eval;
    struct sk_msg_buff * cork;
    struct list_head ingress;
    struct strparser strp;
    struct bpf_prog * bpf_tx_msg;
    struct bpf_prog * bpf_parse;
    struct bpf_prog * bpf_verdict;
    struct list_head maps;
    spinlock_t maps_lock;
    struct sock * sock;
    long unsigned int state;
    struct work_struct tx_work;
    struct work_struct gc_work;
    struct proto * sk_proto;
    void (*)(struct sock *, long int) save_close;
    void (*)(struct sock *) save_data_ready;
    void (*)(struct sock *) save_write_space;
}
```
</details>
</li>
</ul>
