# Struct: <code>crypto_alg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    atomic_t cra_refcnt;
    char[64] cra_name;
    char[64] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    atomic_t cra_refcnt;
    char[64] cra_name;
    char[64] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    atomic_t cra_refcnt;
    char[64] cra_name;
    char[64] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    atomic_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    atomic_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
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
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
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
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct crypto_alg {
    struct list_head cra_list;
    struct list_head cra_users;
    u32 cra_flags;
    unsigned int cra_blocksize;
    unsigned int cra_ctxsize;
    unsigned int cra_alignmask;
    int cra_priority;
    refcount_t cra_refcnt;
    char[128] cra_name;
    char[128] cra_driver_name;
    const struct crypto_type * cra_type;
    union (anon) cra_u;
    int (*)(struct crypto_tfm *) cra_init;
    void (*)(struct crypto_tfm *) cra_exit;
    void (*)(struct crypto_alg *) cra_destroy;
    struct module * cra_module;
    union (anon) stats;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>char[64] cra_name</code> ➡️ <code>char[128] cra_name</code>
</li>
<li>
<b>Field type changed. </b>
<code>char[64] cra_driver_name</code> ➡️ <code>char[128] cra_driver_name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_t cra_refcnt</code> ➡️ <code>refcount_t cra_refcnt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>union (anon) stats</code>
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
<b>Field removed. </b>
<code>union (anon) stats</code>
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
