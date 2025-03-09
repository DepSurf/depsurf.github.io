# Function: <code>migrate_hugetlbs</code>

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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int migrate_hugetlbs(struct list_head * from, new_folio_t * get_new_folio, free_folio_t * put_new_folio, long unsigned int private, enum migrate_mode mode, int reason, struct migrate_pages_stats * stats, struct list_head * ret_folios)
```

```json
{
  "name": "migrate_hugetlbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "migrate_hugetlbs",
      "external": false,
      "loc": "mm/migrate.c:1506",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583474544,
      "name": "migrate_hugetlbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071596569450,
      "name": "migrate_hugetlbs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int migrate_hugetlbs(struct list_head * from, new_folio_t * get_new_folio, free_folio_t * put_new_folio, long unsigned int private, enum migrate_mode mode, int reason, struct migrate_pages_stats * stats, struct list_head * ret_folios)
```

```json
{
  "name": "migrate_hugetlbs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "migrate_hugetlbs",
      "external": false,
      "loc": "mm/migrate.c:1520",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666992,
      "name": "migrate_hugetlbs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
    },
    {
      "addr": 18446744071597473668,
      "name": "migrate_hugetlbs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int migrate_hugetlbs(struct list_head * from, new_folio_t * get_new_folio, free_folio_t * put_new_folio, long unsigned int private, enum migrate_mode mode, int reason, struct migrate_pages_stats * stats, struct list_head * ret_folios)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
