# Struct: <code>x509_parse_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID sig_algo;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID sig_algo;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID sig_algo;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID sig_algo;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
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
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
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
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct x509_parse_context {
    struct x509_certificate * cert;
    long unsigned int data;
    const void * cert_start;
    const void * key;
    size_t key_size;
    const void * params;
    size_t params_size;
    enum OID key_algo;
    enum OID last_oid;
    enum OID algo_oid;
    unsigned char nr_mpi;
    u8 o_size;
    u8 cn_size;
    u8 email_size;
    u16 o_offset;
    u16 cn_offset;
    u16 email_offset;
    unsigned int raw_akid_size;
    const void * raw_akid;
    const void * akid_raw_issuer;
    unsigned int akid_raw_issuer_size;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const void * params</code>
</li>
<li>
<b>Field added. </b>
<code>size_t params_size</code>
</li>
<li>
<b>Field added. </b>
<code>enum OID key_algo</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum OID sig_algo</code>
</li>
<li>
<b>Field removed. </b>
<code>const void * cert_start</code>
</li>
<li>
<b>Field removed. </b>
<code>enum OID algo_oid</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char nr_mpi</code>
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
