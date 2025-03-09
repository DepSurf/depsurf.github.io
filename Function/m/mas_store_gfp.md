# Function: <code>mas_store_gfp</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int mas_store_gfp(struct ma_state * mas, void * entry, gfp_t gfp)
```

```json
{
  "name": "mas_store_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595850672,
      "name": "mas_store_gfp",
      "external": true,
      "loc": "lib/maple_tree.c:5676",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_mas_align_munmap",
        "mm/mmap.c:do_mas_align_munmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595850672,
      "name": "mas_store_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int mas_store_gfp(struct ma_state * mas, void * entry, gfp_t gfp)
```

```json
{
  "name": "mas_store_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596370976,
      "name": "mas_store_gfp",
      "external": true,
      "loc": "lib/maple_tree.c:5507",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_insert_block",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_drop",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_drop",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_drop",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596370976,
      "name": "mas_store_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int mas_store_gfp(struct ma_state * mas, void * entry, gfp_t gfp)
```

```json
{
  "name": "mas_store_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597261008,
      "name": "mas_store_gfp",
      "external": true,
      "loc": "lib/maple_tree.c:5407",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_mmap",
        "kernel/irq/irqdesc.c:early_irq_init",
        "kernel/irq/irqdesc.c:alloc_descs",
        "mm/mmap.c:do_brk_flags",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_insert_block",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_drop",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_drop",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597261008,
      "name": "mas_store_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int mas_store_gfp(struct ma_state * mas, void * entry, gfp_t gfp)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
