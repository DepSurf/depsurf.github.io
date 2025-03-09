# Struct: <code>fscrypt_mode</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    bool logged_impl_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    bool logged_impl_name;
    bool needs_essiv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    bool logged_impl_name;
    bool needs_essiv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    bool logged_impl_name;
    bool needs_essiv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    int logged_impl_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    int logged_impl_name;
    enum blk_crypto_mode_num blk_crypto_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    int logged_impl_name;
    enum blk_crypto_mode_num blk_crypto_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int security_strength;
    int ivsize;
    int logged_impl_name;
    enum blk_crypto_mode_num blk_crypto_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int security_strength;
    int ivsize;
    int logged_cryptoapi_impl;
    int logged_blk_crypto_native;
    int logged_blk_crypto_fallback;
    enum blk_crypto_mode_num blk_crypto_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int security_strength;
    int ivsize;
    int logged_cryptoapi_impl;
    int logged_blk_crypto_native;
    int logged_blk_crypto_fallback;
    enum blk_crypto_mode_num blk_crypto_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int security_strength;
    int ivsize;
    int logged_cryptoapi_impl;
    int logged_blk_crypto_native;
    int logged_blk_crypto_fallback;
    enum blk_crypto_mode_num blk_crypto_mode;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int security_strength;
    int ivsize;
    int logged_cryptoapi_impl;
    int logged_blk_crypto_native;
    int logged_blk_crypto_fallback;
    enum blk_crypto_mode_num blk_crypto_mode;
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
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    bool logged_impl_name;
    bool needs_essiv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    bool logged_impl_name;
    bool needs_essiv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    bool logged_impl_name;
    bool needs_essiv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    bool logged_impl_name;
    bool needs_essiv;
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
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    bool logged_impl_name;
    bool needs_essiv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    bool logged_impl_name;
    bool needs_essiv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    bool logged_impl_name;
    bool needs_essiv;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    int ivsize;
    bool logged_impl_name;
    bool needs_essiv;
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct fscrypt_mode {
    const char * friendly_name;
    const char * cipher_str;
    int keysize;
    bool logged_impl_name;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int ivsize</code>
</li>
<li>
<b>Field added. </b>
<code>bool needs_essiv</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool needs_essiv</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool logged_impl_name</code> ➡️ <code>int logged_impl_name</code>
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
<code>enum blk_crypto_mode_num blk_crypto_mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int security_strength</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int logged_cryptoapi_impl</code>
</li>
<li>
<b>Field added. </b>
<code>int logged_blk_crypto_native</code>
</li>
<li>
<b>Field added. </b>
<code>int logged_blk_crypto_fallback</code>
</li>
<li>
<b>Field removed. </b>
<code>int logged_impl_name</code>
</li>
</ul>
</details>
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
