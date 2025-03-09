# Struct: <code>tls_sw_context_tx</code>

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
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    int async_notify;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    int async_notify;
    int async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    int async_notify;
    int async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    spinlock_t encrypt_compl_lock;
    int async_notify;
    u8 async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    spinlock_t encrypt_compl_lock;
    int async_notify;
    u8 async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    spinlock_t encrypt_compl_lock;
    int async_notify;
    u8 async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    spinlock_t encrypt_compl_lock;
    int async_notify;
    u8 async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    spinlock_t encrypt_compl_lock;
    int async_notify;
    u8 async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    spinlock_t encrypt_compl_lock;
    int async_notify;
    u8 async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    spinlock_t encrypt_compl_lock;
    int async_notify;
    u8 async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    u8 async_capable;
    long unsigned int tx_bitmask;
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
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    int async_notify;
    int async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    int async_notify;
    int async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    int async_notify;
    int async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    int async_notify;
    int async_capable;
    long unsigned int tx_bitmask;
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
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    int async_notify;
    int async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    int async_notify;
    int async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    int async_notify;
    int async_capable;
    long unsigned int tx_bitmask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    int async_notify;
    int async_capable;
    long unsigned int tx_bitmask;
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
struct tls_sw_context_tx {
    struct crypto_aead * aead_send;
    struct crypto_wait async_wait;
    struct tx_work tx_work;
    struct tls_rec * open_rec;
    struct list_head tx_list;
    atomic_t encrypt_pending;
    int async_notify;
    long unsigned int tx_bitmask;
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
<code>int async_capable</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>spinlock_t encrypt_compl_lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>int async_capable</code> ➡️ <code>u8 async_capable</code>
</li>
</ul>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct tls_rec * open_rec</code> ➡️ <code>struct tls_rec * open_rec</code>
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
<code>spinlock_t encrypt_compl_lock</code>
</li>
<li>
<b>Field removed. </b>
<code>int async_notify</code>
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
