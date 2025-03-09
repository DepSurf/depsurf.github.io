# Function: <code>folio_wait_bit</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void folio_wait_bit(struct folio * folio, int bit_nr)
```

```json
{
  "name": "folio_wait_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581942100,
      "name": "folio_wait_bit",
      "external": true,
      "loc": "mm/filemap.c:1471",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:folio_wait_private_2"
      ],
      "caller_func": [
        "mm/page-writeback.c:folio_wait_writeback",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581932064,
      "name": "folio_wait_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void folio_wait_bit(struct folio * folio, int bit_nr)
```

```json
{
  "name": "folio_wait_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582383283,
      "name": "folio_wait_bit",
      "external": true,
      "loc": "mm/filemap.c:1439",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:folio_wait_private_2"
      ],
      "caller_func": [
        "mm/page-writeback.c:folio_wait_writeback",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582369344,
      "name": "folio_wait_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void folio_wait_bit(struct folio * folio, int bit_nr)
```

```json
{
  "name": "folio_wait_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582583929,
      "name": "folio_wait_bit",
      "external": true,
      "loc": "mm/filemap.c:1443",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:folio_wait_private_2"
      ],
      "caller_func": [
        "mm/page-writeback.c:folio_wait_writeback",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582574192,
      "name": "folio_wait_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void folio_wait_bit(struct folio * folio, int bit_nr)
```

```json
{
  "name": "folio_wait_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582755132,
      "name": "folio_wait_bit",
      "external": true,
      "loc": "mm/filemap.c:1413",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:folio_wait_private_2"
      ],
      "caller_func": [
        "mm/page-writeback.c:folio_wait_writeback",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582743856,
      "name": "folio_wait_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void folio_wait_bit(struct folio * folio, int bit_nr)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
