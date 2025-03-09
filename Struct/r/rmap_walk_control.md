# Struct: <code>rmap_walk_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    int (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    int (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    int (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool try_lock;
    bool contended;
    bool (*)(struct folio *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct folio *) done;
    struct anon_vma * (*)(struct folio *, struct rmap_walk_control *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool try_lock;
    bool contended;
    bool (*)(struct folio *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct folio *) done;
    struct anon_vma * (*)(struct folio *, struct rmap_walk_control *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool try_lock;
    bool contended;
    bool (*)(struct folio *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct folio *) done;
    struct anon_vma * (*)(struct folio *, struct rmap_walk_control *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool try_lock;
    bool contended;
    bool (*)(struct folio *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct folio *) done;
    struct anon_vma * (*)(struct folio *, struct rmap_walk_control *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
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
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
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
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rmap_walk_control {
    void * arg;
    bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one;
    int (*)(struct page *) done;
    struct anon_vma * (*)(struct page *) anon_lock;
    bool (*)(struct vm_area_struct *, void *) invalid_vma;
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
<code>int (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one</code> ➡️ <code>bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool try_lock</code>
</li>
<li>
<b>Field added. </b>
<code>bool contended</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool (*)(struct page *, struct vm_area_struct *, long unsigned int, void *) rmap_one</code> ➡️ <code>bool (*)(struct folio *, struct vm_area_struct *, long unsigned int, void *) rmap_one</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct page *) done</code> ➡️ <code>int (*)(struct folio *) done</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct anon_vma * (*)(struct page *) anon_lock</code> ➡️ <code>struct anon_vma * (*)(struct folio *, struct rmap_walk_control *) anon_lock</code>
</li>
</ul>
</details>
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
