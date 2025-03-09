# Struct: <code>rhashtable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    atomic_t nelems;
    unsigned int key_len;
    unsigned int elasticity;
    struct rhashtable_params p;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    atomic_t nelems;
    unsigned int key_len;
    unsigned int elasticity;
    struct rhashtable_params p;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    atomic_t nelems;
    unsigned int key_len;
    unsigned int elasticity;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    atomic_t nelems;
    unsigned int key_len;
    struct rhashtable_params p;
    unsigned int max_elems;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    atomic_t nelems;
    unsigned int key_len;
    struct rhashtable_params p;
    unsigned int max_elems;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
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
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
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
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rhashtable {
    struct bucket_table * tbl;
    unsigned int key_len;
    unsigned int max_elems;
    struct rhashtable_params p;
    bool rhlist;
    struct work_struct run_work;
    struct mutex mutex;
    spinlock_t lock;
    atomic_t nelems;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool rhlist</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int max_elems</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int elasticity</code>
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
