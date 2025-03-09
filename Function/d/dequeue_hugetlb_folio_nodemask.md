# Function: <code>dequeue_hugetlb_folio_nodemask</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct folio * dequeue_hugetlb_folio_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_hugetlb_folio_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583272848,
      "name": "dequeue_hugetlb_folio_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:1310",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_hugetlb_folio_nodemask",
        "mm/hugetlb.c:dequeue_hugetlb_folio_vma",
        "mm/hugetlb.c:dequeue_hugetlb_folio_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583272848,
      "name": "dequeue_hugetlb_folio_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
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
struct folio * dequeue_hugetlb_folio_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```

```json
{
  "name": "dequeue_hugetlb_folio_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583509184,
      "name": "dequeue_hugetlb_folio_nodemask",
      "external": false,
      "loc": "mm/hugetlb.c:1348",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_hugetlb_folio_nodemask",
        "mm/hugetlb.c:dequeue_hugetlb_folio_vma",
        "mm/hugetlb.c:dequeue_hugetlb_folio_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583509184,
      "name": "dequeue_hugetlb_folio_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct folio * dequeue_hugetlb_folio_nodemask(struct hstate * h, gfp_t gfp_mask, int nid, nodemask_t * nmask)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
