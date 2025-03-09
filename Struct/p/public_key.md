# Struct: <code>public_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    const struct public_key_algorithm * algo;
    u8 capabilities;
    enum pkey_algo pkey_algo;
    enum pkey_id_type id_type;
    MPI[5] mpi;
    struct (anon) dsa;
    struct (anon) rsa;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
    long unsigned int key_eflags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
    long unsigned int key_eflags;
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
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
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
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct public_key {
    void * key;
    u32 keylen;
    enum OID algo;
    void * params;
    u32 paramlen;
    bool key_is_private;
    const char * id_type;
    const char * pkey_algo;
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
<code>void * key</code>
</li>
<li>
<b>Field added. </b>
<code>u32 keylen</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct public_key_algorithm * algo</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 capabilities</code>
</li>
<li>
<b>Field removed. </b>
<code>MPI[5] mpi</code>
</li>
<li>
<b>Field removed. </b>
<code>struct (anon) dsa</code>
</li>
<li>
<b>Field removed. </b>
<code>struct (anon) rsa</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum pkey_algo pkey_algo</code> ➡️ <code>const char * pkey_algo</code>
</li>
<li>
<b>Field type changed. </b>
<code>enum pkey_id_type id_type</code> ➡️ <code>const char * id_type</code>
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
<code>bool key_is_private</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum OID algo</code>
</li>
<li>
<b>Field added. </b>
<code>void * params</code>
</li>
<li>
<b>Field added. </b>
<code>u32 paramlen</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int key_eflags</code>
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
