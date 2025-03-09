# Function: <code>shmem_alloc_and_acct_folio</code>

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
struct folio * shmem_alloc_and_acct_folio(gfp_t gfp, struct inode * inode, long unsigned int index, bool huge)
```

```json
{
  "name": "shmem_alloc_and_acct_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582084576,
      "name": "shmem_alloc_and_acct_folio",
      "external": false,
      "loc": "mm/shmem.c:1560",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582084576,
      "name": "shmem_alloc_and_acct_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
struct folio * shmem_alloc_and_acct_folio(gfp_t gfp, struct inode * inode, long unsigned int index, bool huge)
```

```json
{
  "name": "shmem_alloc_and_acct_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582563104,
      "name": "shmem_alloc_and_acct_folio",
      "external": false,
      "loc": "mm/shmem.c:1575",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582563104,
      "name": "shmem_alloc_and_acct_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
struct folio * shmem_alloc_and_acct_folio(gfp_t gfp, struct inode * inode, long unsigned int index, bool huge)
```

```json
{
  "name": "shmem_alloc_and_acct_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582768912,
      "name": "shmem_alloc_and_acct_folio",
      "external": false,
      "loc": "mm/shmem.c:1587",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582768912,
      "name": "shmem_alloc_and_acct_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct folio * shmem_alloc_and_acct_folio(gfp_t gfp, struct inode * inode, long unsigned int index, bool huge)
```
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
struct folio * shmem_alloc_and_acct_folio(gfp_t gfp, struct inode * inode, long unsigned int index, bool huge)
```
</details>
</li>
</ul>
