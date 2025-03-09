# Struct: <code>zswap_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct callback_head callback_head;
    struct notifier_block notifier;
    char[64] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct notifier_block notifier;
    char[64] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[64] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct release_work;
    struct work_struct shrink_work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_acomp_ctx * acomp_ctx;
    struct kref kref;
    struct list_head list;
    struct work_struct release_work;
    struct work_struct shrink_work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_acomp_ctx * acomp_ctx;
    struct kref kref;
    struct list_head list;
    struct work_struct release_work;
    struct work_struct shrink_work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_acomp_ctx * acomp_ctx;
    struct kref kref;
    struct list_head list;
    struct work_struct release_work;
    struct work_struct shrink_work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_acomp_ctx * acomp_ctx;
    struct kref kref;
    struct list_head list;
    struct work_struct release_work;
    struct work_struct shrink_work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_acomp_ctx * acomp_ctx;
    struct kref kref;
    struct list_head list;
    struct work_struct release_work;
    struct work_struct shrink_work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_acomp_ctx * acomp_ctx;
    struct kref kref;
    struct list_head list;
    struct work_struct release_work;
    struct work_struct shrink_work;
    struct hlist_node node;
    char[128] tfm_name;
    struct list_head lru;
    spinlock_t lru_lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool *[32] zpools;
    struct crypto_acomp_ctx * acomp_ctx;
    struct kref kref;
    struct list_head list;
    struct work_struct release_work;
    struct work_struct shrink_work;
    struct hlist_node node;
    char[128] tfm_name;
    struct list_lru list_lru;
    struct mem_cgroup * next_shrink;
    struct shrinker * shrinker;
    atomic_t nr_stored;
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
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
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
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct zswap_pool {
    struct zpool * zpool;
    struct crypto_comp * * tfm;
    struct kref kref;
    struct list_head list;
    struct work_struct work;
    struct hlist_node node;
    char[128] tfm_name;
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
<code>struct work_struct work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head callback_head</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct hlist_node node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct notifier_block notifier</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>char[64] tfm_name</code> ➡️ <code>char[128] tfm_name</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct work_struct release_work</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct shrink_work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct work</code>
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
<code>struct crypto_acomp_ctx * acomp_ctx</code>
</li>
<li>
<b>Field removed. </b>
<code>struct crypto_comp * * tfm</code>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head lru</code>
</li>
<li>
<b>Field added. </b>
<code>spinlock_t lru_lock</code>
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
<code>struct zpool *[32] zpools</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_lru list_lru</code>
</li>
<li>
<b>Field added. </b>
<code>struct mem_cgroup * next_shrink</code>
</li>
<li>
<b>Field added. </b>
<code>struct shrinker * shrinker</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t nr_stored</code>
</li>
<li>
<b>Field removed. </b>
<code>struct zpool * zpool</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head lru</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t lru_lock</code>
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
