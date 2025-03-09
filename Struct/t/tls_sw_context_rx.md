# Struct: <code>tls_sw_context_rx</code>

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
struct tls_sw_context_rx {
    struct crypto_aead * aead_recv;
    struct crypto_wait async_wait;
    struct strparser strp;
    struct sk_buff_head rx_list;
    void (*)(struct sock *) saved_data_ready;
    struct sk_buff * recv_pkt;
    u8 control;
    u8 async_capable;
    u8 decrypted;
    atomic_t decrypt_pending;
    spinlock_t decrypt_compl_lock;
    bool async_notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_rx {
    struct crypto_aead * aead_recv;
    struct crypto_wait async_wait;
    struct strparser strp;
    struct sk_buff_head rx_list;
    void (*)(struct sock *) saved_data_ready;
    struct sk_buff * recv_pkt;
    u8 control;
    u8 async_capable;
    u8 decrypted;
    atomic_t decrypt_pending;
    spinlock_t decrypt_compl_lock;
    bool async_notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_rx {
    struct crypto_aead * aead_recv;
    struct crypto_wait async_wait;
    struct strparser strp;
    struct sk_buff_head rx_list;
    void (*)(struct sock *) saved_data_ready;
    struct sk_buff * recv_pkt;
    u8 control;
    u8 async_capable;
    u8 decrypted;
    atomic_t decrypt_pending;
    spinlock_t decrypt_compl_lock;
    bool async_notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_rx {
    struct crypto_aead * aead_recv;
    struct crypto_wait async_wait;
    struct strparser strp;
    struct sk_buff_head rx_list;
    void (*)(struct sock *) saved_data_ready;
    struct sk_buff * recv_pkt;
    u8 control;
    u8 async_capable;
    u8 decrypted;
    atomic_t decrypt_pending;
    spinlock_t decrypt_compl_lock;
    bool async_notify;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_rx {
    struct crypto_aead * aead_recv;
    struct crypto_wait async_wait;
    struct strparser strp;
    struct sk_buff_head rx_list;
    void (*)(struct sock *) saved_data_ready;
    struct sk_buff * recv_pkt;
    u8 async_capable;
    atomic_t decrypt_pending;
    spinlock_t decrypt_compl_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_rx {
    struct crypto_aead * aead_recv;
    struct crypto_wait async_wait;
    struct sk_buff_head rx_list;
    void (*)(struct sock *) saved_data_ready;
    u8 reader_present;
    u8 async_capable;
    u8 zc_capable;
    u8 reader_contended;
    struct tls_strparser strp;
    atomic_t decrypt_pending;
    spinlock_t decrypt_compl_lock;
    struct sk_buff_head async_hold;
    struct wait_queue_head wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_rx {
    struct crypto_aead * aead_recv;
    struct crypto_wait async_wait;
    struct sk_buff_head rx_list;
    void (*)(struct sock *) saved_data_ready;
    u8 reader_present;
    u8 async_capable;
    u8 zc_capable;
    u8 reader_contended;
    struct tls_strparser strp;
    atomic_t decrypt_pending;
    spinlock_t decrypt_compl_lock;
    struct sk_buff_head async_hold;
    struct wait_queue_head wq;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_rx {
    struct crypto_aead * aead_recv;
    struct crypto_wait async_wait;
    struct sk_buff_head rx_list;
    void (*)(struct sock *) saved_data_ready;
    u8 reader_present;
    u8 async_capable;
    u8 zc_capable;
    u8 reader_contended;
    struct tls_strparser strp;
    atomic_t decrypt_pending;
    struct sk_buff_head async_hold;
    struct wait_queue_head wq;
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
struct tls_sw_context_rx {
    struct crypto_aead * aead_recv;
    struct crypto_wait async_wait;
    struct strparser strp;
    struct sk_buff_head rx_list;
    void (*)(struct sock *) saved_data_ready;
    struct sk_buff * recv_pkt;
    u8 control;
    u8 async_capable;
    u8 decrypted;
    atomic_t decrypt_pending;
    spinlock_t decrypt_compl_lock;
    bool async_notify;
}
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u8 control</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 decrypted</code>
</li>
<li>
<b>Field removed. </b>
<code>bool async_notify</code>
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
<code>u8 reader_present</code>
</li>
<li>
<b>Field added. </b>
<code>u8 zc_capable</code>
</li>
<li>
<b>Field added. </b>
<code>u8 reader_contended</code>
</li>
<li>
<b>Field added. </b>
<code>struct sk_buff_head async_hold</code>
</li>
<li>
<b>Field added. </b>
<code>struct wait_queue_head wq</code>
</li>
<li>
<b>Field removed. </b>
<code>struct sk_buff * recv_pkt</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct strparser strp</code> ➡️ <code>struct tls_strparser strp</code>
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
<b>Field removed. </b>
<code>spinlock_t decrypt_compl_lock</code>
</li>
</ul>
</details>
</li>
</ul>
