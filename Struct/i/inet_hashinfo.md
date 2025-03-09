# Struct: <code>inet_hashinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    struct kmem_cache * bind2_bucket_cachep;
    struct inet_bind_hashbucket * bhash2;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    bool pernet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    struct kmem_cache * bind2_bucket_cachep;
    struct inet_bind_hashbucket * bhash2;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    bool pernet;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    struct kmem_cache * bind2_bucket_cachep;
    struct inet_bind_hashbucket * bhash2;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    bool pernet;
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
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
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
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inet_hashinfo {
    struct inet_ehash_bucket * ehash;
    spinlock_t * ehash_locks;
    unsigned int ehash_mask;
    unsigned int ehash_locks_mask;
    struct kmem_cache * bind_bucket_cachep;
    struct inet_bind_hashbucket * bhash;
    unsigned int bhash_size;
    unsigned int lhash2_mask;
    struct inet_listen_hashbucket * lhash2;
    struct inet_listen_hashbucket[32] listening_hash;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int lhash2_mask</code>
</li>
<li>
<b>Field added. </b>
<code>struct inet_listen_hashbucket * lhash2</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct inet_listen_hashbucket[32] listening_hash</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct kmem_cache * bind2_bucket_cachep</code>
</li>
<li>
<b>Field added. </b>
<code>struct inet_bind_hashbucket * bhash2</code>
</li>
<li>
<b>Field added. </b>
<code>bool pernet</code>
</li>
</ul>
</details>
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
