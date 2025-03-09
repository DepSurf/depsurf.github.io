# Struct: <code>page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct address_space * mapping;
    void * s_mem;
    long unsigned int index;
    void * freelist;
    long unsigned int counters;
    atomic_t _mapcount;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    int units;
    atomic_t _count;
    unsigned int active;
    struct list_head lru;
    struct page * next;
    int pages;
    int pobjects;
    struct callback_head callback_head;
    long unsigned int compound_head;
    unsigned int compound_dtor;
    unsigned int compound_order;
    long unsigned int __pad;
    pgtable_t pmd_huge_pte;
    long unsigned int private;
    spinlock_t ptl;
    struct kmem_cache * slab_cache;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct address_space * mapping;
    void * s_mem;
    atomic_t compound_mapcount;
    long unsigned int index;
    void * freelist;
    long unsigned int counters;
    atomic_t _mapcount;
    unsigned int active;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    int units;
    atomic_t _refcount;
    struct list_head lru;
    struct dev_pagemap * pgmap;
    struct page * next;
    int pages;
    int pobjects;
    struct callback_head callback_head;
    long unsigned int compound_head;
    unsigned int compound_dtor;
    unsigned int compound_order;
    long unsigned int __pad;
    pgtable_t pmd_huge_pte;
    long unsigned int private;
    spinlock_t ptl;
    struct kmem_cache * slab_cache;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct address_space * mapping;
    void * s_mem;
    atomic_t compound_mapcount;
    long unsigned int index;
    void * freelist;
    long unsigned int counters;
    atomic_t _mapcount;
    unsigned int active;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    int units;
    atomic_t _refcount;
    struct list_head lru;
    struct dev_pagemap * pgmap;
    struct page * next;
    int pages;
    int pobjects;
    struct callback_head callback_head;
    long unsigned int compound_head;
    unsigned int compound_dtor;
    unsigned int compound_order;
    long unsigned int __pad;
    pgtable_t pmd_huge_pte;
    long unsigned int private;
    spinlock_t ptl;
    struct kmem_cache * slab_cache;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct address_space * mapping;
    void * s_mem;
    atomic_t compound_mapcount;
    long unsigned int index;
    void * freelist;
    long unsigned int counters;
    atomic_t _mapcount;
    unsigned int active;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    int units;
    atomic_t _refcount;
    struct list_head lru;
    struct dev_pagemap * pgmap;
    struct page * next;
    int pages;
    int pobjects;
    struct callback_head callback_head;
    long unsigned int compound_head;
    unsigned int compound_dtor;
    unsigned int compound_order;
    long unsigned int __pad;
    pgtable_t pmd_huge_pte;
    long unsigned int private;
    spinlock_t ptl;
    struct kmem_cache * slab_cache;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct address_space * mapping;
    void * s_mem;
    atomic_t compound_mapcount;
    long unsigned int index;
    void * freelist;
    long unsigned int counters;
    atomic_t _mapcount;
    unsigned int active;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    int units;
    atomic_t _refcount;
    struct list_head lru;
    struct dev_pagemap * pgmap;
    struct page * next;
    int pages;
    int pobjects;
    struct callback_head callback_head;
    long unsigned int compound_head;
    unsigned int compound_dtor;
    unsigned int compound_order;
    long unsigned int __pad;
    pgtable_t pmd_huge_pte;
    long unsigned int private;
    spinlock_t ptl;
    struct kmem_cache * slab_cache;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    long unsigned int hmm_data;
    long unsigned int _zd_pad_1;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    long unsigned int hmm_data;
    long unsigned int _zd_pad_1;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    dma_addr_t dma_addr;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    dma_addr_t dma_addr;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    dma_addr_t dma_addr;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    long unsigned int _compound_pad_1;
    atomic_t hpage_pinned_refcount;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    dma_addr_t dma_addr;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    unsigned int compound_nr;
    long unsigned int _compound_pad_1;
    atomic_t hpage_pinned_refcount;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    long unsigned int memcg_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    long unsigned int[2] dma_addr;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    unsigned int compound_nr;
    long unsigned int _compound_pad_1;
    atomic_t hpage_pinned_refcount;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    long unsigned int memcg_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    long unsigned int pp_magic;
    struct page_pool * pp;
    long unsigned int _pp_mapping_pad;
    long unsigned int dma_addr;
    long unsigned int dma_addr_upper;
    atomic_long_t pp_frag_count;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    unsigned int compound_nr;
    long unsigned int _compound_pad_1;
    atomic_t hpage_pinned_refcount;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    long unsigned int memcg_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    void * __filler;
    unsigned int mlock_count;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    long unsigned int pp_magic;
    struct page_pool * pp;
    long unsigned int _pp_mapping_pad;
    long unsigned int dma_addr;
    long unsigned int dma_addr_upper;
    atomic_long_t pp_frag_count;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    atomic_t compound_pincount;
    unsigned int compound_nr;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    atomic_t _refcount;
    long unsigned int memcg_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    void * __filler;
    unsigned int mlock_count;
    struct list_head buddy_list;
    struct list_head pcp_list;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int share;
    long unsigned int private;
    long unsigned int pp_magic;
    struct page_pool * pp;
    long unsigned int _pp_mapping_pad;
    long unsigned int dma_addr;
    long unsigned int dma_addr_upper;
    atomic_long_t pp_frag_count;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    atomic_t subpages_mapcount;
    atomic_t compound_pincount;
    unsigned int compound_nr;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _hugetlb_pad_1;
    void * hugetlb_subpool;
    void * hugetlb_cgroup;
    void * hugetlb_cgroup_rsvd;
    void * hugetlb_hwpoison;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    atomic_t _refcount;
    long unsigned int memcg_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    void * __filler;
    unsigned int mlock_count;
    struct list_head buddy_list;
    struct list_head pcp_list;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int share;
    long unsigned int private;
    long unsigned int pp_magic;
    struct page_pool * pp;
    long unsigned int _pp_mapping_pad;
    long unsigned int dma_addr;
    long unsigned int dma_addr_upper;
    atomic_long_t pp_frag_count;
    long unsigned int compound_head;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    atomic_t _refcount;
    long unsigned int memcg_data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    void * __filler;
    unsigned int mlock_count;
    struct list_head buddy_list;
    struct list_head pcp_list;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int share;
    long unsigned int private;
    long unsigned int pp_magic;
    struct page_pool * pp;
    long unsigned int _pp_mapping_pad;
    long unsigned int dma_addr;
    atomic_long_t pp_ref_count;
    long unsigned int compound_head;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    atomic_t _refcount;
    long unsigned int memcg_data;
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
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    dma_addr_t dma_addr;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    dma_addr_t dma_addr;
    struct list_head slab_list;
    struct page * next;
    short int pages;
    short int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    dma_addr_t dma_addr;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    dma_addr_t dma_addr;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    struct mem_cgroup * mem_cgroup;
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
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    dma_addr_t dma_addr;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    dma_addr_t dma_addr;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    dma_addr_t dma_addr;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    struct mem_cgroup * mem_cgroup;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct page {
    long unsigned int flags;
    struct list_head lru;
    struct address_space * mapping;
    long unsigned int index;
    long unsigned int private;
    dma_addr_t dma_addr;
    struct list_head slab_list;
    struct page * next;
    int pages;
    int pobjects;
    struct kmem_cache * slab_cache;
    void * freelist;
    void * s_mem;
    long unsigned int counters;
    unsigned int inuse;
    unsigned int objects;
    unsigned int frozen;
    long unsigned int compound_head;
    unsigned char compound_dtor;
    unsigned char compound_order;
    atomic_t compound_mapcount;
    long unsigned int _compound_pad_1;
    long unsigned int _compound_pad_2;
    struct list_head deferred_list;
    long unsigned int _pt_pad_1;
    pgtable_t pmd_huge_pte;
    long unsigned int _pt_pad_2;
    struct mm_struct * pt_mm;
    atomic_t pt_frag_refcount;
    spinlock_t ptl;
    struct dev_pagemap * pgmap;
    void * zone_device_data;
    struct callback_head callback_head;
    atomic_t _mapcount;
    unsigned int page_type;
    unsigned int active;
    int units;
    atomic_t _refcount;
    struct mem_cgroup * mem_cgroup;
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
<code>atomic_t compound_mapcount</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t _refcount</code>
</li>
<li>
<b>Field added. </b>
<code>struct dev_pagemap * pgmap</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t _count</code>
</li>
</ul>
</details>
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
<code>struct list_head slab_list</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _compound_pad_1</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _compound_pad_2</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head deferred_list</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _pt_pad_1</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _pt_pad_2</code>
</li>
<li>
<b>Field added. </b>
<code>struct mm_struct * pt_mm</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t pt_frag_refcount</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int hmm_data</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _zd_pad_1</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int page_type</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int __pad</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int compound_dtor</code> ➡️ <code>unsigned char compound_dtor</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int compound_order</code> ➡️ <code>unsigned char compound_order</code>
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
<code>dma_addr_t dma_addr</code>
</li>
<li>
<b>Field added. </b>
<code>void * zone_device_data</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int hmm_data</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int _zd_pad_1</code>
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
<code>atomic_t hpage_pinned_refcount</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int _compound_pad_2</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int compound_nr</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int memcg_data</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mem_cgroup * mem_cgroup</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>dma_addr_t dma_addr</code> ➡️ <code>long unsigned int[2] dma_addr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int pp_magic</code>
</li>
<li>
<b>Field added. </b>
<code>struct page_pool * pp</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _pp_mapping_pad</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int dma_addr_upper</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_long_t pp_frag_count</code>
</li>
<li>
<b>Field type changed. </b>
<code>long unsigned int[2] dma_addr</code> ➡️ <code>long unsigned int dma_addr</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * __filler</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int mlock_count</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t compound_pincount</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _compound_pad_2</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head slab_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct page * next</code>
</li>
<li>
<b>Field removed. </b>
<code>int pages</code>
</li>
<li>
<b>Field removed. </b>
<code>int pobjects</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kmem_cache * slab_cache</code>
</li>
<li>
<b>Field removed. </b>
<code>void * freelist</code>
</li>
<li>
<b>Field removed. </b>
<code>void * s_mem</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int counters</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int inuse</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int objects</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int frozen</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t hpage_pinned_refcount</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int active</code>
</li>
<li>
<b>Field removed. </b>
<code>int units</code>
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
<code>struct list_head buddy_list</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head pcp_list</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int share</code>
</li>
<li>
<b>Field added. </b>
<code>atomic_t subpages_mapcount</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int _hugetlb_pad_1</code>
</li>
<li>
<b>Field added. </b>
<code>void * hugetlb_subpool</code>
</li>
<li>
<b>Field added. </b>
<code>void * hugetlb_cgroup</code>
</li>
<li>
<b>Field added. </b>
<code>void * hugetlb_cgroup_rsvd</code>
</li>
<li>
<b>Field added. </b>
<code>void * hugetlb_hwpoison</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned char compound_dtor</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned char compound_order</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t compound_mapcount</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t subpages_mapcount</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t compound_pincount</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int compound_nr</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int _compound_pad_1</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int _compound_pad_2</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head deferred_list</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int _hugetlb_pad_1</code>
</li>
<li>
<b>Field removed. </b>
<code>void * hugetlb_subpool</code>
</li>
<li>
<b>Field removed. </b>
<code>void * hugetlb_cgroup</code>
</li>
<li>
<b>Field removed. </b>
<code>void * hugetlb_cgroup_rsvd</code>
</li>
<li>
<b>Field removed. </b>
<code>void * hugetlb_hwpoison</code>
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
<code>atomic_long_t pp_ref_count</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int dma_addr_upper</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_long_t pp_frag_count</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int _pt_pad_1</code>
</li>
<li>
<b>Field removed. </b>
<code>pgtable_t pmd_huge_pte</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int _pt_pad_2</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mm_struct * pt_mm</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t pt_frag_refcount</code>
</li>
<li>
<b>Field removed. </b>
<code>spinlock_t ptl</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int pages</code> ➡️ <code>short int pages</code>
</li>
<li>
<b>Field type changed. </b>
<code>int pobjects</code> ➡️ <code>short int pobjects</code>
</li>
</ul>
</details>
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
