# Struct: <code>slab</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct slab {
    long unsigned int __page_flags;
    struct list_head slab_list;
    struct callback_head callback_head;
    struct slab * next;
    int slabs;
    struct kmem_cache * slab_cache;
    void * freelist;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    unsigned int __unused;
    atomic_t __page_refcount;
    long unsigned int memcg_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct slab {
    long unsigned int __page_flags;
    struct kmem_cache * slab_cache;
    struct list_head slab_list;
    struct slab * next;
    int slabs;
    void * freelist;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    struct callback_head callback_head;
    unsigned int __unused;
    atomic_t __page_refcount;
    long unsigned int memcg_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct slab {
    long unsigned int __page_flags;
    struct kmem_cache * slab_cache;
    struct list_head slab_list;
    struct slab * next;
    int slabs;
    void * freelist;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    freelist_aba_t freelist_counter;
    struct callback_head callback_head;
    unsigned int __unused;
    atomic_t __page_refcount;
    long unsigned int memcg_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct slab {
    long unsigned int __page_flags;
    struct kmem_cache * slab_cache;
    struct list_head slab_list;
    struct slab * next;
    int slabs;
    void * freelist;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    freelist_aba_t freelist_counter;
    struct callback_head callback_head;
    unsigned int __unused;
    atomic_t __page_refcount;
    long unsigned int memcg_data;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct slab {
    long unsigned int __page_flags;
    struct list_head slab_list;
    struct callback_head callback_head;
    struct slab * next;
    int slabs;
    struct kmem_cache * slab_cache;
    void * freelist;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    unsigned int __unused;
    atomic_t __page_refcount;
    long unsigned int memcg_data;
}
```
</details>
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
<code>freelist_aba_t freelist_counter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
