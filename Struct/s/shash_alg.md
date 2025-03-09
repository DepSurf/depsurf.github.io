# Struct: <code>shash_alg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    int (*)(struct crypto_shash *) init_tfm;
    void (*)(struct crypto_shash *) exit_tfm;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    int (*)(struct crypto_shash *) init_tfm;
    void (*)(struct crypto_shash *) exit_tfm;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    int (*)(struct crypto_shash *) init_tfm;
    void (*)(struct crypto_shash *) exit_tfm;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    int (*)(struct crypto_shash *) init_tfm;
    void (*)(struct crypto_shash *) exit_tfm;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    int (*)(struct crypto_shash *) init_tfm;
    void (*)(struct crypto_shash *) exit_tfm;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    int (*)(struct crypto_shash *) init_tfm;
    void (*)(struct crypto_shash *) exit_tfm;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    int (*)(struct crypto_shash *) init_tfm;
    void (*)(struct crypto_shash *) exit_tfm;
    int (*)(struct crypto_shash *, struct crypto_shash *) clone_tfm;
    unsigned int descsize;
    struct crypto_istat_hash stat;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
    struct hash_alg_common halg;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    int (*)(struct crypto_shash *) init_tfm;
    void (*)(struct crypto_shash *) exit_tfm;
    int (*)(struct crypto_shash *, struct crypto_shash *) clone_tfm;
    unsigned int descsize;
    struct crypto_istat_hash stat;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
    struct hash_alg_common halg;
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
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
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
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
    struct crypto_alg base;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct shash_alg {
    int (*)(struct shash_desc *) init;
    int (*)(struct shash_desc *, const u8 *, unsigned int) update;
    int (*)(struct shash_desc *, u8 *) final;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) finup;
    int (*)(struct shash_desc *, const u8 *, unsigned int, u8 *) digest;
    int (*)(struct shash_desc *, void *) export;
    int (*)(struct shash_desc *, const void *) import;
    int (*)(struct crypto_shash *, const u8 *, unsigned int) setkey;
    unsigned int descsize;
    unsigned int digestsize;
    unsigned int statesize;
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
<code>int (*)(struct crypto_shash *) init_tfm</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct crypto_shash *) exit_tfm</code>
</li>
</ul>
</details>
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
<code>int (*)(struct crypto_shash *, struct crypto_shash *) clone_tfm</code>
</li>
<li>
<b>Field added. </b>
<code>struct crypto_istat_hash stat</code>
</li>
<li>
<b>Field added. </b>
<code>struct hash_alg_common halg</code>
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
