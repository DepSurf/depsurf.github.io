# Struct: <code>crypto_ahash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    bool has_setkey;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    bool has_setkey;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    bool has_setkey;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    bool has_setkey;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int statesize;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    bool using_shash;
    unsigned int statesize;
    unsigned int reqsize;
    struct crypto_tfm base;
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
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
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
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct crypto_ahash {
    int (*)(struct ahash_request *) init;
    int (*)(struct ahash_request *) update;
    int (*)(struct ahash_request *) final;
    int (*)(struct ahash_request *) finup;
    int (*)(struct ahash_request *) digest;
    int (*)(struct ahash_request *, void *) export;
    int (*)(struct ahash_request *, const void *) import;
    int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey;
    unsigned int reqsize;
    struct crypto_tfm base;
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>bool has_setkey</code>
</li>
</ul>
</details>
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
<code>unsigned int statesize</code>
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
<code>bool using_shash</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ahash_request *) init</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ahash_request *) update</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ahash_request *) final</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ahash_request *) finup</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ahash_request *) digest</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ahash_request *, void *) export</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct ahash_request *, const void *) import</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct crypto_ahash *, const u8 *, unsigned int) setkey</code>
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
