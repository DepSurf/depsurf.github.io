# Function: <code>__cond_resched_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545392,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:4633",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:set_max_huge_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545392,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579556848,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:4884",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:set_max_huge_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556848,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579581680,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:4923",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581680,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579565248,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:4824",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565248,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579594912,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:4869",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579594912,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579626624,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:5008",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626624,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664160,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:4991",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664160,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579692848,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:5444",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579692848,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579733232,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:5635",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579733232,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579769728,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:5868",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769728,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579758432,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:6688",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758432,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579765664,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:6999",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765664,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579856064,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:8203",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856064,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939424,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:8335",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939424,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580096064,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:8519",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096064,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580154000,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:8629",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580154000,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580198896,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:8633",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198896,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490913592,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:5635",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/arm/mmu.c:stage2_wp_range",
        "virt/kvm/arm/mmu.c:stage2_wp_range",
        "virt/kvm/arm/mmu.c:unmap_stage2_range",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490913592,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224928908,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:5635",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224928908,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283758416,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:5635",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283758416,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271551640,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:5635",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271551640,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579709888,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:5635",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709888,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579637744,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:5635",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637744,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579699360,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:5635",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699360,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __cond_resched_lock(spinlock_t * lock)
```

```json
{
  "name": "__cond_resched_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579740448,
      "name": "__cond_resched_lock",
      "external": true,
      "loc": "kernel/sched/core.c:5635",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:return_unused_surplus_pages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740448,
      "name": "__cond_resched_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
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
