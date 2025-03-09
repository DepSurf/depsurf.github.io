# Struct: <code>fscrypt_master_key</code>

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
struct fscrypt_master_key {
    struct hlist_node mk_node;
    refcount_t mk_refcount;
    const struct fscrypt_mode * mk_mode;
    struct crypto_skcipher * mk_ctfm;
    u8[8] mk_descriptor;
    u8[64] mk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct hlist_node mk_node;
    refcount_t mk_refcount;
    const struct fscrypt_mode * mk_mode;
    struct crypto_skcipher * mk_ctfm;
    u8[8] mk_descriptor;
    u8[64] mk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct rw_semaphore mk_secret_sem;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct crypto_skcipher *[10] mk_mode_keys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct rw_semaphore mk_secret_sem;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct crypto_skcipher *[10] mk_direct_keys;
    struct crypto_skcipher *[10] mk_iv_ino_lblk_64_keys;
    struct crypto_skcipher *[10] mk_iv_ino_lblk_32_keys;
    siphash_key_t mk_ino_hash_key;
    bool mk_ino_hash_key_initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct fscrypt_prepared_key[10] mk_direct_keys;
    struct fscrypt_prepared_key[10] mk_iv_ino_lblk_64_keys;
    struct fscrypt_prepared_key[10] mk_iv_ino_lblk_32_keys;
    siphash_key_t mk_ino_hash_key;
    bool mk_ino_hash_key_initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct fscrypt_prepared_key[10] mk_direct_keys;
    struct fscrypt_prepared_key[10] mk_iv_ino_lblk_64_keys;
    struct fscrypt_prepared_key[10] mk_iv_ino_lblk_32_keys;
    siphash_key_t mk_ino_hash_key;
    bool mk_ino_hash_key_initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct fscrypt_prepared_key[10] mk_direct_keys;
    struct fscrypt_prepared_key[10] mk_iv_ino_lblk_64_keys;
    struct fscrypt_prepared_key[10] mk_iv_ino_lblk_32_keys;
    siphash_key_t mk_ino_hash_key;
    bool mk_ino_hash_key_initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct fscrypt_prepared_key[10] mk_direct_keys;
    struct fscrypt_prepared_key[10] mk_iv_ino_lblk_64_keys;
    struct fscrypt_prepared_key[10] mk_iv_ino_lblk_32_keys;
    siphash_key_t mk_ino_hash_key;
    bool mk_ino_hash_key_initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct hlist_node mk_node;
    struct rw_semaphore mk_sem;
    refcount_t mk_active_refs;
    refcount_t mk_struct_refs;
    struct callback_head mk_rcu_head;
    struct fscrypt_master_key_secret mk_secret;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct fscrypt_prepared_key[11] mk_direct_keys;
    struct fscrypt_prepared_key[11] mk_iv_ino_lblk_64_keys;
    struct fscrypt_prepared_key[11] mk_iv_ino_lblk_32_keys;
    siphash_key_t mk_ino_hash_key;
    bool mk_ino_hash_key_initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct hlist_node mk_node;
    struct rw_semaphore mk_sem;
    refcount_t mk_active_refs;
    refcount_t mk_struct_refs;
    struct callback_head mk_rcu_head;
    struct fscrypt_master_key_secret mk_secret;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct fscrypt_prepared_key[11] mk_direct_keys;
    struct fscrypt_prepared_key[11] mk_iv_ino_lblk_64_keys;
    struct fscrypt_prepared_key[11] mk_iv_ino_lblk_32_keys;
    siphash_key_t mk_ino_hash_key;
    bool mk_ino_hash_key_initialized;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct hlist_node mk_node;
    struct rw_semaphore mk_sem;
    refcount_t mk_active_refs;
    refcount_t mk_struct_refs;
    struct callback_head mk_rcu_head;
    struct fscrypt_master_key_secret mk_secret;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct fscrypt_prepared_key[11] mk_direct_keys;
    struct fscrypt_prepared_key[11] mk_iv_ino_lblk_64_keys;
    struct fscrypt_prepared_key[11] mk_iv_ino_lblk_32_keys;
    siphash_key_t mk_ino_hash_key;
    bool mk_ino_hash_key_initialized;
    bool mk_present;
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
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct rw_semaphore mk_secret_sem;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct crypto_skcipher *[10] mk_mode_keys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct rw_semaphore mk_secret_sem;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct crypto_skcipher *[10] mk_mode_keys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct rw_semaphore mk_secret_sem;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct crypto_skcipher *[10] mk_mode_keys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct rw_semaphore mk_secret_sem;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct crypto_skcipher *[10] mk_mode_keys;
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
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct rw_semaphore mk_secret_sem;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct crypto_skcipher *[10] mk_mode_keys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct rw_semaphore mk_secret_sem;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct crypto_skcipher *[10] mk_mode_keys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct rw_semaphore mk_secret_sem;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct crypto_skcipher *[10] mk_mode_keys;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fscrypt_master_key {
    struct fscrypt_master_key_secret mk_secret;
    struct rw_semaphore mk_secret_sem;
    struct fscrypt_key_specifier mk_spec;
    struct key * mk_users;
    refcount_t mk_refcount;
    struct list_head mk_decrypted_inodes;
    spinlock_t mk_decrypted_inodes_lock;
    struct crypto_skcipher *[10] mk_mode_keys;
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
struct fscrypt_master_key {
    struct hlist_node mk_node;
    refcount_t mk_refcount;
    const struct fscrypt_mode * mk_mode;
    struct crypto_skcipher * mk_ctfm;
    u8[8] mk_descriptor;
    u8[64] mk_raw;
}
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct fscrypt_master_key_secret mk_secret</code>
</li>
<li>
<b>Field added. </b>
<code>struct rw_semaphore mk_secret_sem</code>
</li>
<li>
<b>Field added. </b>
<code>struct fscrypt_key_specifier mk_spec</code>
</li>
<li>
<b>Field added. </b>
<code>struct key * mk_users</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head mk_decrypted_inodes</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t mk_decrypted_inodes_lock</code>
</li>
<li>
<b>Field added. </b>
<code>struct crypto_skcipher *[10] mk_mode_keys</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_node mk_node</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct fscrypt_mode * mk_mode</code>
</li>
<li>
<b>Field removed. </b>
<code>struct crypto_skcipher * mk_ctfm</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[8] mk_descriptor</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[64] mk_raw</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct crypto_skcipher *[10] mk_direct_keys</code>
</li>
<li>
<b>Field added. </b>
<code>struct crypto_skcipher *[10] mk_iv_ino_lblk_64_keys</code>
</li>
<li>
<b>Field added. </b>
<code>struct crypto_skcipher *[10] mk_iv_ino_lblk_32_keys</code>
</li>
<li>
<b>Field added. </b>
<code>siphash_key_t mk_ino_hash_key</code>
</li>
<li>
<b>Field added. </b>
<code>bool mk_ino_hash_key_initialized</code>
</li>
<li>
<b>Field removed. </b>
<code>struct crypto_skcipher *[10] mk_mode_keys</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct rw_semaphore mk_secret_sem</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct crypto_skcipher *[10] mk_direct_keys</code> ➡️ <code>struct fscrypt_prepared_key[10] mk_direct_keys</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct crypto_skcipher *[10] mk_iv_ino_lblk_64_keys</code> ➡️ <code>struct fscrypt_prepared_key[10] mk_iv_ino_lblk_64_keys</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct crypto_skcipher *[10] mk_iv_ino_lblk_32_keys</code> ➡️ <code>struct fscrypt_prepared_key[10] mk_iv_ino_lblk_32_keys</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_node mk_node</code>
</li>
<li>
<b>Field added. </b>
<code>struct rw_semaphore mk_sem</code>
</li>
<li>
<b>Field added. </b>
<code>refcount_t mk_active_refs</code>
</li>
<li>
<b>Field added. </b>
<code>refcount_t mk_struct_refs</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head mk_rcu_head</code>
</li>
<li>
<b>Field removed. </b>
<code>refcount_t mk_refcount</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fscrypt_prepared_key[10] mk_direct_keys</code> ➡️ <code>struct fscrypt_prepared_key[11] mk_direct_keys</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fscrypt_prepared_key[10] mk_iv_ino_lblk_64_keys</code> ➡️ <code>struct fscrypt_prepared_key[11] mk_iv_ino_lblk_64_keys</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct fscrypt_prepared_key[10] mk_iv_ino_lblk_32_keys</code> ➡️ <code>struct fscrypt_prepared_key[11] mk_iv_ino_lblk_32_keys</code>
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
<code>bool mk_present</code>
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
