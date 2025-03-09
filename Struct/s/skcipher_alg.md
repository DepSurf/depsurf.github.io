# Struct: <code>skcipher_alg</code>

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
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_istat_cipher stat;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct skcipher_request *, void *) export;
    int (*)(struct skcipher_request *, const void *) import;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int walksize;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int statesize;
    struct crypto_istat_cipher stat;
    struct crypto_alg base;
    struct skcipher_alg_common co;
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
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
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
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    unsigned int walksize;
    struct crypto_alg base;
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
struct skcipher_alg {
    int (*)(struct crypto_skcipher *, const u8 *, unsigned int) setkey;
    int (*)(struct skcipher_request *) encrypt;
    int (*)(struct skcipher_request *) decrypt;
    int (*)(struct crypto_skcipher *) init;
    void (*)(struct crypto_skcipher *) exit;
    unsigned int min_keysize;
    unsigned int max_keysize;
    unsigned int ivsize;
    unsigned int chunksize;
    struct crypto_alg base;
}
```
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
<code>unsigned int walksize</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct crypto_istat_cipher stat</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct skcipher_request *, void *) export</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct skcipher_request *, const void *) import</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int statesize</code>
</li>
<li>
<b>Field added. </b>
<code>struct skcipher_alg_common co</code>
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
