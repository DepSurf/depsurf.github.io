# Struct: <code>pkcs7_signed_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool trusted;
    bool unsupported_crypto;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct asymmetric_key_id * signing_cert_id;
    struct public_key_signature sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
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
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
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
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pkcs7_signed_info {
    struct pkcs7_signed_info * next;
    struct x509_certificate * signer;
    unsigned int index;
    bool unsupported_crypto;
    bool blacklisted;
    const void * msgdigest;
    unsigned int msgdigest_len;
    unsigned int authattrs_len;
    const void * authattrs;
    long unsigned int aa_set;
    time64_t signing_time;
    struct public_key_signature * sig;
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
<code>bool trusted</code>
</li>
<li>
<b>Field removed. </b>
<code>struct asymmetric_key_id * signing_cert_id</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct public_key_signature sig</code> ➡️ <code>struct public_key_signature * sig</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool blacklisted</code>
</li>
</ul>
</details>
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
