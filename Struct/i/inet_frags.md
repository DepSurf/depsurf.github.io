# Struct: <code>inet_frags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    struct inet_frag_bucket[1024] hash;
    struct work_struct frags_work;
    unsigned int next_bucket;
    long unsigned int last_rebuild_jiffies;
    bool rebuild;
    u32 rnd;
    seqlock_t rnd_seqlock;
    int qsize;
    unsigned int (*)(const struct inet_frag_queue *) hashfn;
    bool (*)(const struct inet_frag_queue *, const void *) match;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct sk_buff *) skb_free;
    void (*)(long unsigned int) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    struct inet_frag_bucket[1024] hash;
    struct work_struct frags_work;
    unsigned int next_bucket;
    long unsigned int last_rebuild_jiffies;
    bool rebuild;
    u32 rnd;
    seqlock_t rnd_seqlock;
    int qsize;
    unsigned int (*)(const struct inet_frag_queue *) hashfn;
    bool (*)(const struct inet_frag_queue *, const void *) match;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(long unsigned int) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    struct inet_frag_bucket[1024] hash;
    struct work_struct frags_work;
    unsigned int next_bucket;
    long unsigned int last_rebuild_jiffies;
    bool rebuild;
    u32 rnd;
    seqlock_t rnd_seqlock;
    int qsize;
    unsigned int (*)(const struct inet_frag_queue *) hashfn;
    bool (*)(const struct inet_frag_queue *, const void *) match;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(long unsigned int) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    struct inet_frag_bucket[1024] hash;
    struct work_struct frags_work;
    unsigned int next_bucket;
    long unsigned int last_rebuild_jiffies;
    bool rebuild;
    u32 rnd;
    seqlock_t rnd_seqlock;
    unsigned int qsize;
    unsigned int (*)(const struct inet_frag_queue *) hashfn;
    bool (*)(const struct inet_frag_queue *, const void *) match;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(long unsigned int) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    struct inet_frag_bucket[1024] hash;
    struct work_struct frags_work;
    unsigned int next_bucket;
    long unsigned int last_rebuild_jiffies;
    bool rebuild;
    u32 rnd;
    seqlock_t rnd_seqlock;
    unsigned int qsize;
    unsigned int (*)(const struct inet_frag_queue *) hashfn;
    bool (*)(const struct inet_frag_queue *, const void *) match;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
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
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
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
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct inet_frags {
    unsigned int qsize;
    void (*)(struct inet_frag_queue *, const void *) constructor;
    void (*)(struct inet_frag_queue *) destructor;
    void (*)(struct timer_list *) frag_expire;
    struct kmem_cache * frags_cachep;
    const char * frags_cache_name;
    struct rhashtable_params rhash_params;
    refcount_t refcnt;
    struct completion completion;
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
<code>void (*)(struct sk_buff *) skb_free</code>
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
<b>Field type changed. </b>
<code>int qsize</code> ➡️ <code>unsigned int qsize</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(long unsigned int) frag_expire</code> ➡️ <code>void (*)(struct timer_list *) frag_expire</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rhashtable_params rhash_params</code>
</li>
<li>
<b>Field removed. </b>
<code>struct inet_frag_bucket[1024] hash</code>
</li>
<li>
<b>Field removed. </b>
<code>struct work_struct frags_work</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int next_bucket</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int last_rebuild_jiffies</code>
</li>
<li>
<b>Field removed. </b>
<code>bool rebuild</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 rnd</code>
</li>
<li>
<b>Field removed. </b>
<code>seqlock_t rnd_seqlock</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int (*)(const struct inet_frag_queue *) hashfn</code>
</li>
<li>
<b>Field removed. </b>
<code>bool (*)(const struct inet_frag_queue *, const void *) match</code>
</li>
</ul>
</details>
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
<code>refcount_t refcnt</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion completion</code>
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
