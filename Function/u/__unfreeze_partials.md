# Function: <code>__unfreeze_partials</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __unfreeze_partials(struct kmem_cache * s, struct page * partial_page)
```

```json
{
  "name": "__unfreeze_partials",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582215552,
      "name": "__unfreeze_partials",
      "external": false,
      "loc": "mm/slub.c:2447",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab",
        "mm/slub.c:put_cpu_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582215552,
      "name": "__unfreeze_partials",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __unfreeze_partials(struct kmem_cache * s, struct slab * partial_slab)
```

```json
{
  "name": "__unfreeze_partials",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582680640,
      "name": "__unfreeze_partials",
      "external": false,
      "loc": "mm/slub.c:2493",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:put_cpu_partial",
        "mm/slub.c:unfreeze_partials"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582680640,
      "name": "__unfreeze_partials",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __unfreeze_partials(struct kmem_cache * s, struct slab * partial_slab)
```

```json
{
  "name": "__unfreeze_partials",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583207456,
      "name": "__unfreeze_partials",
      "external": false,
      "loc": "mm/slub.c:2582",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:bootstrap",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:put_cpu_partial",
        "mm/slub.c:unfreeze_partials"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583207456,
      "name": "__unfreeze_partials",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
void __unfreeze_partials(struct kmem_cache * s, struct slab * partial_slab)
```

```json
{
  "name": "__unfreeze_partials",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583425376,
      "name": "__unfreeze_partials",
      "external": false,
      "loc": "mm/slub.c:2592",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:bootstrap",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:put_cpu_partial",
        "mm/slub.c:unfreeze_partials"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583425376,
      "name": "__unfreeze_partials",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void __unfreeze_partials(struct kmem_cache * s, struct page * partial_page)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct slab * partial_slab</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * partial_page</code>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void __unfreeze_partials(struct kmem_cache * s, struct slab * partial_slab)
```
</details>
</li>
</ul>
