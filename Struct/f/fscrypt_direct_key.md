# Struct: <code>fscrypt_direct_key</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct crypto_skcipher * dk_ctfm;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct crypto_skcipher * dk_ctfm;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct fscrypt_prepared_key dk_key;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct fscrypt_prepared_key dk_key;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct fscrypt_prepared_key dk_key;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct fscrypt_prepared_key dk_key;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct super_block * dk_sb;
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct fscrypt_prepared_key dk_key;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct super_block * dk_sb;
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct fscrypt_prepared_key dk_key;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct super_block * dk_sb;
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct fscrypt_prepared_key dk_key;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
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
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct crypto_skcipher * dk_ctfm;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct crypto_skcipher * dk_ctfm;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct crypto_skcipher * dk_ctfm;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct crypto_skcipher * dk_ctfm;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
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
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct crypto_skcipher * dk_ctfm;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct crypto_skcipher * dk_ctfm;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct crypto_skcipher * dk_ctfm;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct crypto_skcipher * dk_ctfm;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct fscrypt_direct_key {
    struct hlist_node dk_node;
    refcount_t dk_refcount;
    const struct fscrypt_mode * dk_mode;
    struct crypto_skcipher * dk_ctfm;
    u8[8] dk_descriptor;
    u8[64] dk_raw;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct fscrypt_prepared_key dk_key</code>
</li>
<li>
<b>Field removed. </b>
<code>struct crypto_skcipher * dk_ctfm</code>
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
<code>struct super_block * dk_sb</code>
</li>
</ul>
</details>
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
