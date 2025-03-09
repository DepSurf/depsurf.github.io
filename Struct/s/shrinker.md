# Struct: <code>shrinker</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    int seeks;
    long int batch;
    long unsigned int flags;
    struct list_head list;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    int seeks;
    long int batch;
    long unsigned int flags;
    struct list_head list;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    int seeks;
    long int batch;
    long unsigned int flags;
    struct list_head list;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    int seeks;
    long int batch;
    long unsigned int flags;
    struct list_head list;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    int seeks;
    long int batch;
    long unsigned int flags;
    struct list_head list;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    int seeks;
    long int batch;
    long unsigned int flags;
    struct list_head list;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    refcount_t refcount;
    struct completion done;
    struct callback_head rcu;
    void * private_data;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
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
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
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
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct shrinker {
    long unsigned int (*)(struct shrinker *, struct shrink_control *) count_objects;
    long unsigned int (*)(struct shrinker *, struct shrink_control *) scan_objects;
    long int batch;
    int seeks;
    unsigned int flags;
    struct list_head list;
    int id;
    atomic_long_t * nr_deferred;
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int id</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int flags</code> ➡️ <code>unsigned int flags</code>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>refcount_t refcount</code>
</li>
<li>
<b>Field added. </b>
<code>struct completion done</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head rcu</code>
</li>
<li>
<b>Field added. </b>
<code>void * private_data</code>
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
