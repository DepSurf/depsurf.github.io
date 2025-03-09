# Struct: <code>bpf_htab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct hlist_head * buckets;
    raw_spinlock_t lock;
    u32 count;
    u32 n_buckets;
    u32 elem_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    void * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    void * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
    struct lock_class_key lockdep_key;
    int *[8] map_locked;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
    struct lock_class_key lockdep_key;
    int *[8] map_locked;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
    struct lock_class_key lockdep_key;
    int *[8] map_locked;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
    struct lock_class_key lockdep_key;
    int *[8] map_locked;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bpf_mem_alloc ma;
    struct bpf_mem_alloc pcpu_ma;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    struct percpu_counter pcount;
    atomic_t count;
    bool use_percpu_counter;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
    struct lock_class_key lockdep_key;
    int *[8] map_locked;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bpf_mem_alloc ma;
    struct bpf_mem_alloc pcpu_ma;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    struct percpu_counter pcount;
    atomic_t count;
    bool use_percpu_counter;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
    struct lock_class_key lockdep_key;
    int *[8] map_locked;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bpf_mem_alloc ma;
    struct bpf_mem_alloc pcpu_ma;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    struct percpu_counter pcount;
    atomic_t count;
    bool use_percpu_counter;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
    struct lock_class_key lockdep_key;
    int *[8] map_locked;
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
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
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
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_htab {
    struct bpf_map map;
    struct bucket * buckets;
    void * elems;
    struct pcpu_freelist freelist;
    struct bpf_lru lru;
    struct htab_elem * * extra_elems;
    atomic_t count;
    u32 n_buckets;
    u32 elem_size;
    u32 hashrnd;
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
<code>void * elems</code>
</li>
<li>
<b>Field added. </b>
<code>struct pcpu_freelist freelist</code>
</li>
<li>
<b>Field added. </b>
<code>void * extra_elems</code>
</li>
<li>
<b>Field removed. </b>
<code>raw_spinlock_t lock</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct hlist_head * buckets</code> ➡️ <code>struct bucket * buckets</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32 count</code> ➡️ <code>atomic_t count</code>
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
<code>struct bpf_lru lru</code>
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
<code>void * extra_elems</code> ➡️ <code>struct htab_elem * * extra_elems</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 hashrnd</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct lock_class_key lockdep_key</code>
</li>
<li>
<b>Field added. </b>
<code>int *[8] map_locked</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct bpf_mem_alloc ma</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_mem_alloc pcpu_ma</code>
</li>
<li>
<b>Field added. </b>
<code>struct percpu_counter pcount</code>
</li>
<li>
<b>Field added. </b>
<code>bool use_percpu_counter</code>
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
