# Function: <code>migrate_pages_batch</code>

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
int migrate_pages_batch(struct list_head * from, new_folio_t * get_new_folio, free_folio_t * put_new_folio, long unsigned int private, enum migrate_mode mode, int reason, struct list_head * ret_folios, struct list_head * split_folios, struct migrate_pages_stats * stats, int nr_pass)
```

```json
{
  "name": "migrate_pages_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583475056,
      "name": "migrate_pages_batch",
      "external": false,
      "loc": "mm/migrate.c:1604",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages_sync",
        "mm/migrate.c:migrate_pages_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583475056,
      "name": "migrate_pages_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2314
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
int migrate_pages_batch(struct list_head * from, new_folio_t * get_new_folio, free_folio_t * put_new_folio, long unsigned int private, enum migrate_mode mode, int reason, struct list_head * ret_folios, struct list_head * split_folios, struct migrate_pages_stats * stats, int nr_pass)
```

```json
{
  "name": "migrate_pages_batch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583667520,
      "name": "migrate_pages_batch",
      "external": false,
      "loc": "mm/migrate.c:1618",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages_sync",
        "mm/migrate.c:migrate_pages_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583667520,
      "name": "migrate_pages_batch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2328
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
int migrate_pages_batch(struct list_head * from, new_folio_t * get_new_folio, free_folio_t * put_new_folio, long unsigned int private, enum migrate_mode mode, int reason, struct list_head * ret_folios, struct list_head * split_folios, struct migrate_pages_stats * stats, int nr_pass)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
