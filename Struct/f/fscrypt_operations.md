# Struct: <code>fscrypt_operations</code>

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
struct fscrypt_operations {
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, u8 * *) key_prefix;
    int (*)(struct inode *) prepare_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    int (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) is_encrypted;
    bool (*)(struct inode *) empty_dir;
    unsigned int (*)(struct inode *) max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, u8 * *) key_prefix;
    int (*)(struct inode *) prepare_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    int (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) is_encrypted;
    bool (*)(struct inode *) empty_dir;
    unsigned int (*)(struct inode *) max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) is_encrypted;
    bool (*)(struct inode *) empty_dir;
    unsigned int (*)(struct inode *) max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int (*)(struct inode *) max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    const union fscrypt_context * (*)(struct super_block *) get_dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
    bool (*)(struct super_block *) has_stable_inodes;
    void (*)(struct super_block *, int *, int *) get_ino_and_lblk_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    const union fscrypt_policy * (*)(struct super_block *) get_dummy_policy;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
    bool (*)(struct super_block *) has_stable_inodes;
    void (*)(struct super_block *, int *, int *) get_ino_and_lblk_bits;
    int (*)(struct super_block *) get_num_devices;
    void (*)(struct super_block *, struct request_queue * *) get_devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    const union fscrypt_policy * (*)(struct super_block *) get_dummy_policy;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
    bool (*)(struct super_block *) has_stable_inodes;
    void (*)(struct super_block *, int *, int *) get_ino_and_lblk_bits;
    int (*)(struct super_block *) get_num_devices;
    void (*)(struct super_block *, struct request_queue * *) get_devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    const union fscrypt_policy * (*)(struct super_block *) get_dummy_policy;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
    bool (*)(struct super_block *) has_stable_inodes;
    void (*)(struct super_block *, int *, int *) get_ino_and_lblk_bits;
    int (*)(struct super_block *) get_num_devices;
    void (*)(struct super_block *, struct request_queue * *) get_devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    const union fscrypt_policy * (*)(struct super_block *) get_dummy_policy;
    bool (*)(struct inode *) empty_dir;
    bool (*)(struct super_block *) has_stable_inodes;
    void (*)(struct super_block *, int *, int *) get_ino_and_lblk_bits;
    int (*)(struct super_block *) get_num_devices;
    void (*)(struct super_block *, struct request_queue * *) get_devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    const union fscrypt_policy * (*)(struct super_block *) get_dummy_policy;
    bool (*)(struct inode *) empty_dir;
    bool (*)(struct super_block *) has_stable_inodes;
    void (*)(struct super_block *, int *, int *) get_ino_and_lblk_bits;
    struct block_device * * (*)(struct super_block *, unsigned int *) get_devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    const union fscrypt_policy * (*)(struct super_block *) get_dummy_policy;
    bool (*)(struct inode *) empty_dir;
    bool (*)(struct super_block *) has_stable_inodes;
    void (*)(struct super_block *, int *, int *) get_ino_and_lblk_bits;
    struct block_device * * (*)(struct super_block *, unsigned int *) get_devices;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int needs_bounce_pages;
    unsigned int has_32bit_inodes;
    unsigned int supports_subblock_data_units;
    const char * legacy_key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    const union fscrypt_policy * (*)(struct super_block *) get_dummy_policy;
    bool (*)(struct inode *) empty_dir;
    bool (*)(struct super_block *) has_stable_inodes;
    struct block_device * * (*)(struct super_block *, unsigned int *) get_devices;
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
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
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
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fscrypt_operations {
    unsigned int flags;
    const char * key_prefix;
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    bool (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) empty_dir;
    unsigned int max_namelen;
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
struct fscrypt_operations {
    int (*)(struct inode *, void *, size_t) get_context;
    int (*)(struct inode *, u8 * *) key_prefix;
    int (*)(struct inode *) prepare_context;
    int (*)(struct inode *, const void *, size_t, void *) set_context;
    int (*)(struct inode *) dummy_context;
    bool (*)(struct inode *) is_encrypted;
    bool (*)(struct inode *) empty_dir;
    unsigned int (*)(struct inode *) max_namelen;
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
<code>unsigned int flags</code>
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
<code>int (*)(struct inode *) prepare_context</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, u8 * *) key_prefix</code> ➡️ <code>const char * key_prefix</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *) dummy_context</code> ➡️ <code>bool (*)(struct inode *) dummy_context</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool (*)(struct inode *) is_encrypted</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>unsigned int (*)(struct inode *) max_namelen</code> ➡️ <code>unsigned int max_namelen</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const union fscrypt_context * (*)(struct super_block *) get_dummy_context</code>
</li>
<li>
<b>Field added. </b>
<code>bool (*)(struct super_block *) has_stable_inodes</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct super_block *, int *, int *) get_ino_and_lblk_bits</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(struct inode *) dummy_context</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const union fscrypt_policy * (*)(struct super_block *) get_dummy_policy</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct super_block *) get_num_devices</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct super_block *, struct request_queue * *) get_devices</code>
</li>
<li>
<b>Field removed. </b>
<code>const union fscrypt_context * (*)(struct super_block *) get_dummy_context</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int max_namelen</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct super_block *) get_num_devices</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct super_block *, struct request_queue * *) get_devices</code> ➡️ <code>struct block_device * * (*)(struct super_block *, unsigned int *) get_devices</code>
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
<code>unsigned int needs_bounce_pages</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int has_32bit_inodes</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int supports_subblock_data_units</code>
</li>
<li>
<b>Field added. </b>
<code>const char * legacy_key_prefix</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Field removed. </b>
<code>const char * key_prefix</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct super_block *, int *, int *) get_ino_and_lblk_bits</code>
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
