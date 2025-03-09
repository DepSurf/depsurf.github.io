# Struct: <code>ecryptfs_crypt_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_ablkcipher * tfm;
    struct crypto_hash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_hash_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
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
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
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
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ecryptfs_crypt_stat {
    u32 flags;
    unsigned int file_version;
    size_t iv_bytes;
    size_t metadata_size;
    size_t extent_size;
    size_t key_size;
    size_t extent_shift;
    unsigned int extent_mask;
    struct ecryptfs_mount_crypt_stat * mount_crypt_stat;
    struct crypto_skcipher * tfm;
    struct crypto_shash * hash_tfm;
    unsigned char[32] cipher;
    unsigned char[64] key;
    unsigned char[16] root_iv;
    struct list_head keysig_list;
    struct mutex keysig_list_mutex;
    struct mutex cs_tfm_mutex;
    struct mutex cs_mutex;
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
<b>Field removed. </b>
<code>struct mutex cs_hash_tfm_mutex</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct crypto_ablkcipher * tfm</code> ➡️ <code>struct crypto_skcipher * tfm</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct crypto_hash * hash_tfm</code> ➡️ <code>struct crypto_shash * hash_tfm</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
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
