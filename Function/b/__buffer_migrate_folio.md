# Function: <code>__buffer_migrate_folio</code>

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
int __buffer_migrate_folio(struct address_space * mapping, struct folio * dst, struct folio * src, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583252960,
      "name": "__buffer_migrate_folio",
      "external": false,
      "loc": "mm/migrate.c:716",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_folio_norefs",
        "mm/migrate.c:buffer_migrate_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583252960,
      "name": "__buffer_migrate_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
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
int __buffer_migrate_folio(struct address_space * mapping, struct folio * dst, struct folio * src, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583472416,
      "name": "__buffer_migrate_folio",
      "external": false,
      "loc": "mm/migrate.c:721",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_folio_norefs",
        "mm/migrate.c:buffer_migrate_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583472416,
      "name": "__buffer_migrate_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
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
int __buffer_migrate_folio(struct address_space * mapping, struct folio * dst, struct folio * src, enum migrate_mode mode, bool check_refs)
```

```json
{
  "name": "__buffer_migrate_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__buffer_migrate_folio",
      "external": false,
      "loc": "mm/migrate.c:730",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:buffer_migrate_folio_norefs",
        "mm/migrate.c:buffer_migrate_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583664816,
      "name": "__buffer_migrate_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
    },
    {
      "addr": 18446744071597473630,
      "name": "__buffer_migrate_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int __buffer_migrate_folio(struct address_space * mapping, struct folio * dst, struct folio * src, enum migrate_mode mode, bool check_refs)
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
