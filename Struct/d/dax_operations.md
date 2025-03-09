# Struct: <code>dax_operations</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    void (*)(struct dax_device *, long unsigned int, void *, size_t) flush;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
    int (*)(struct dax_device *, long unsigned int, size_t) zero_page_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
    int (*)(struct dax_device *, long unsigned int, size_t) zero_page_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
    int (*)(struct dax_device *, long unsigned int, size_t) zero_page_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
    int (*)(struct dax_device *, long unsigned int, size_t) zero_page_range;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, enum dax_access_mode, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    int (*)(struct dax_device *, long unsigned int, size_t) zero_page_range;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) recovery_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, enum dax_access_mode, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    int (*)(struct dax_device *, long unsigned int, size_t) zero_page_range;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) recovery_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, enum dax_access_mode, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    int (*)(struct dax_device *, long unsigned int, size_t) zero_page_range;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) recovery_write;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, enum dax_access_mode, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    int (*)(struct dax_device *, long unsigned int, size_t) zero_page_range;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) recovery_write;
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
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
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
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter;
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct dax_operations {
    long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access;
    size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter;
    void (*)(struct dax_device *, long unsigned int, void *, size_t) flush;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>void (*)(struct dax_device *, long unsigned int, void *, size_t) flush</code>
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
<code>size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter</code>
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
<code>bool (*)(struct dax_device *, struct block_device *, int, sector_t, sector_t) dax_supported</code>
</li>
</ul>
</details>
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
<code>int (*)(struct dax_device *, long unsigned int, size_t) zero_page_range</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) recovery_write</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_from_iter</code>
</li>
<li>
<b>Field removed. </b>
<code>size_t (*)(struct dax_device *, long unsigned int, void *, size_t, struct iov_iter *) copy_to_iter</code>
</li>
<li>
<b>Field type changed. </b>
<code>long int (*)(struct dax_device *, long unsigned int, long int, void * *, pfn_t *) direct_access</code> ➡️ <code>long int (*)(struct dax_device *, long unsigned int, long int, enum dax_access_mode, void * *, pfn_t *) direct_access</code>
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
