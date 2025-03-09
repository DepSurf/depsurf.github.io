# Struct: <code>dma_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    struct dma_block * next_block;
    size_t nr_blocks;
    size_t nr_active;
    size_t nr_pages;
    struct device * dev;
    unsigned int size;
    unsigned int allocation;
    unsigned int boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    struct dma_block * next_block;
    size_t nr_blocks;
    size_t nr_active;
    size_t nr_pages;
    struct device * dev;
    unsigned int size;
    unsigned int allocation;
    unsigned int boundary;
    char[32] name;
    struct list_head pools;
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
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
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
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dma_pool {
    struct list_head page_list;
    spinlock_t lock;
    size_t size;
    struct device * dev;
    size_t allocation;
    size_t boundary;
    char[32] name;
    struct list_head pools;
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
<b>Field added. </b>
<code>struct dma_block * next_block</code>
</li>
<li>
<b>Field added. </b>
<code>size_t nr_blocks</code>
</li>
<li>
<b>Field added. </b>
<code>size_t nr_active</code>
</li>
<li>
<b>Field added. </b>
<code>size_t nr_pages</code>
</li>
<li>
<b>Field type changed. </b>
<code>size_t size</code> ➡️ <code>unsigned int size</code>
</li>
<li>
<b>Field type changed. </b>
<code>size_t allocation</code> ➡️ <code>unsigned int allocation</code>
</li>
<li>
<b>Field type changed. </b>
<code>size_t boundary</code> ➡️ <code>unsigned int boundary</code>
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
