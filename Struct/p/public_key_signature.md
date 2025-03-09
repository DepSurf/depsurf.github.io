# Struct: <code>public_key_signature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    u8 * digest;
    u8 digest_size;
    u8 nr_mpi;
    enum pkey_algo pkey_algo;
    enum hash_algo pkey_hash_algo;
    MPI[2] mpi;
    struct (anon) rsa;
    struct (anon) dsa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
    const void * data;
    unsigned int data_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
    const void * data;
    unsigned int data_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u8 * digest;
    u32 s_size;
    u32 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
    const void * data;
    unsigned int data_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[3] auth_ids;
    u8 * s;
    u8 * digest;
    u32 s_size;
    u32 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
    const void * data;
    unsigned int data_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[3] auth_ids;
    u8 * s;
    u8 * digest;
    u32 s_size;
    u32 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
    const void * data;
    unsigned int data_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[3] auth_ids;
    u8 * s;
    u8 * digest;
    u32 s_size;
    u32 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[3] auth_ids;
    u8 * s;
    u8 * digest;
    u32 s_size;
    u32 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
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
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
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
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct public_key_signature {
    struct asymmetric_key_id *[2] auth_ids;
    u8 * s;
    u32 s_size;
    u8 * digest;
    u8 digest_size;
    const char * pkey_algo;
    const char * hash_algo;
    const char * encoding;
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
<b>Field added. </b>
<code>struct asymmetric_key_id *[2] auth_ids</code>
</li>
<li>
<b>Field added. </b>
<code>u8 * s</code>
</li>
<li>
<b>Field added. </b>
<code>u32 s_size</code>
</li>
<li>
<b>Field added. </b>
<code>const char * hash_algo</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 nr_mpi</code>
</li>
<li>
<b>Field removed. </b>
<code>enum hash_algo pkey_hash_algo</code>
</li>
<li>
<b>Field removed. </b>
<code>MPI[2] mpi</code>
</li>
<li>
<b>Field removed. </b>
<code>struct (anon) rsa</code>
</li>
<li>
<b>Field removed. </b>
<code>struct (anon) dsa</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum pkey_algo pkey_algo</code> ➡️ <code>const char * pkey_algo</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const char * encoding</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const void * data</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int data_size</code>
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
<b>Field type changed. </b>
<code>u8 digest_size</code> ➡️ <code>u32 digest_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct asymmetric_key_id *[2] auth_ids</code> ➡️ <code>struct asymmetric_key_id *[3] auth_ids</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>const void * data</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int data_size</code>
</li>
</ul>
</details>
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
