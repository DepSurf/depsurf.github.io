# Struct: <code>blk_crypto_profile</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct blk_crypto_profile {
    struct blk_crypto_ll_ops ll_ops;
    unsigned int max_dun_bytes_supported;
    unsigned int[4] modes_supported;
    struct device * dev;
    unsigned int num_slots;
    struct rw_semaphore lock;
    wait_queue_head_t idle_slots_wait_queue;
    struct list_head idle_slots;
    spinlock_t idle_slots_lock;
    struct hlist_head * slot_hashtable;
    unsigned int log_slot_ht_size;
    struct blk_crypto_keyslot * slots;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct blk_crypto_profile {
    struct blk_crypto_ll_ops ll_ops;
    unsigned int max_dun_bytes_supported;
    unsigned int[5] modes_supported;
    struct device * dev;
    unsigned int num_slots;
    struct rw_semaphore lock;
    wait_queue_head_t idle_slots_wait_queue;
    struct list_head idle_slots;
    spinlock_t idle_slots_lock;
    struct hlist_head * slot_hashtable;
    unsigned int log_slot_ht_size;
    struct blk_crypto_keyslot * slots;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct blk_crypto_profile {
    struct blk_crypto_ll_ops ll_ops;
    unsigned int max_dun_bytes_supported;
    unsigned int[5] modes_supported;
    struct device * dev;
    unsigned int num_slots;
    struct rw_semaphore lock;
    struct lock_class_key lockdep_key;
    wait_queue_head_t idle_slots_wait_queue;
    struct list_head idle_slots;
    spinlock_t idle_slots_lock;
    struct hlist_head * slot_hashtable;
    unsigned int log_slot_ht_size;
    struct blk_crypto_keyslot * slots;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct blk_crypto_profile {
    struct blk_crypto_ll_ops ll_ops;
    unsigned int max_dun_bytes_supported;
    unsigned int[5] modes_supported;
    struct device * dev;
    unsigned int num_slots;
    struct rw_semaphore lock;
    struct lock_class_key lockdep_key;
    wait_queue_head_t idle_slots_wait_queue;
    struct list_head idle_slots;
    spinlock_t idle_slots_lock;
    struct hlist_head * slot_hashtable;
    unsigned int log_slot_ht_size;
    struct blk_crypto_keyslot * slots;
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct blk_crypto_profile {
    struct blk_crypto_ll_ops ll_ops;
    unsigned int max_dun_bytes_supported;
    unsigned int[4] modes_supported;
    struct device * dev;
    unsigned int num_slots;
    struct rw_semaphore lock;
    wait_queue_head_t idle_slots_wait_queue;
    struct list_head idle_slots;
    spinlock_t idle_slots_lock;
    struct hlist_head * slot_hashtable;
    unsigned int log_slot_ht_size;
    struct blk_crypto_keyslot * slots;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned int[4] modes_supported</code> ➡️ <code>unsigned int[5] modes_supported</code>
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
<code>struct lock_class_key lockdep_key</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
