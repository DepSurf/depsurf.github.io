# Struct: <code>folio</code>

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
struct folio {
    long unsigned int flags;
    struct list_head lru;
    void * __filler;
    unsigned int mlock_count;
    struct address_space * mapping;
    long unsigned int index;
    void * private;
    atomic_t _mapcount;
    atomic_t _refcount;
    long unsigned int memcg_data;
    struct page page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct folio {
    long unsigned int flags;
    struct list_head lru;
    void * __filler;
    unsigned int mlock_count;
    struct address_space * mapping;
    long unsigned int index;
    void * private;
    atomic_t _mapcount;
    atomic_t _refcount;
    long unsigned int memcg_data;
    struct page page;
    long unsigned int _flags_1;
    long unsigned int _head_1;
    unsigned char _folio_dtor;
    unsigned char _folio_order;
    atomic_t _compound_mapcount;
    atomic_t _subpages_mapcount;
    atomic_t _pincount;
    unsigned int _folio_nr_pages;
    struct page __page_1;
    long unsigned int _flags_2;
    long unsigned int _head_2;
    void * _hugetlb_subpool;
    void * _hugetlb_cgroup;
    void * _hugetlb_cgroup_rsvd;
    void * _hugetlb_hwpoison;
    struct page __page_2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct folio {
    long unsigned int flags;
    struct list_head lru;
    void * __filler;
    unsigned int mlock_count;
    struct address_space * mapping;
    long unsigned int index;
    void * private;
    atomic_t _mapcount;
    atomic_t _refcount;
    long unsigned int memcg_data;
    struct page page;
    long unsigned int _flags_1;
    long unsigned int _head_1;
    unsigned char _folio_dtor;
    unsigned char _folio_order;
    atomic_t _entire_mapcount;
    atomic_t _nr_pages_mapped;
    atomic_t _pincount;
    unsigned int _folio_nr_pages;
    struct page __page_1;
    long unsigned int _flags_2;
    long unsigned int _head_2;
    void * _hugetlb_subpool;
    void * _hugetlb_cgroup;
    void * _hugetlb_cgroup_rsvd;
    void * _hugetlb_hwpoison;
    long unsigned int _flags_2a;
    long unsigned int _head_2a;
    struct list_head _deferred_list;
    struct page __page_2;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct folio {
    long unsigned int flags;
    struct list_head lru;
    void * __filler;
    unsigned int mlock_count;
    struct address_space * mapping;
    long unsigned int index;
    void * private;
    swp_entry_t swap;
    atomic_t _mapcount;
    atomic_t _refcount;
    long unsigned int memcg_data;
    struct page page;
    long unsigned int _flags_1;
    long unsigned int _head_1;
    long unsigned int _folio_avail;
    atomic_t _entire_mapcount;
    atomic_t _nr_pages_mapped;
    atomic_t _pincount;
    unsigned int _folio_nr_pages;
    struct page __page_1;
    long unsigned int _flags_2;
    long unsigned int _head_2;
    void * _hugetlb_subpool;
    void * _hugetlb_cgroup;
    void * _hugetlb_cgroup_rsvd;
    void * _hugetlb_hwpoison;
    long unsigned int _flags_2a;
    long unsigned int _head_2a;
    struct list_head _deferred_list;
    struct page __page_2;
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
struct folio {
    long unsigned int flags;
    struct list_head lru;
    void * __filler;
    unsigned int mlock_count;
    struct address_space * mapping;
    long unsigned int index;
    void * private;
    atomic_t _mapcount;
    atomic_t _refcount;
    long unsigned int memcg_data;
    struct page page;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int _flags_1</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _head_1</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char _folio_dtor</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char _folio_order</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t _compound_mapcount</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t _subpages_mapcount</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t _pincount</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int _folio_nr_pages</code>
</li>
<li>
<b>Field added. </b>
<code>struct page __page_1</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _flags_2</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _head_2</code>
</li>
<li>
<b>Field added. </b>
<code>void * _hugetlb_subpool</code>
</li>
<li>
<b>Field added. </b>
<code>void * _hugetlb_cgroup</code>
</li>
<li>
<b>Field added. </b>
<code>void * _hugetlb_cgroup_rsvd</code>
</li>
<li>
<b>Field added. </b>
<code>void * _hugetlb_hwpoison</code>
</li>
<li>
<b>Field added. </b>
<code>struct page __page_2</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_t _entire_mapcount</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t _nr_pages_mapped</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _flags_2a</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _head_2a</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head _deferred_list</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t _compound_mapcount</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t _subpages_mapcount</code>
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
<code>swp_entry_t swap</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _folio_avail</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char _folio_dtor</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char _folio_order</code>
</li>
</ul>
</details>
</li>
</ul>
