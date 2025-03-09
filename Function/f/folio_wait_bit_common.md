# Function: <code>folio_wait_bit_common</code>

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
int folio_wait_bit_common(struct folio * folio, int bit_nr, int state, enum behavior behavior)
```

```json
{
  "name": "folio_wait_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581942100,
      "name": "folio_wait_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1242",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:folio_wait_private_2_killable",
        "mm/filemap.c:folio_wait_private_2"
      ],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581931168,
      "name": "folio_wait_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 886
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
int folio_wait_bit_common(struct folio * folio, int bit_nr, int state, enum behavior behavior)
```

```json
{
  "name": "folio_wait_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582368512,
      "name": "folio_wait_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1218",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_read_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:folio_wait_private_2_killable",
        "mm/filemap.c:folio_wait_private_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582368512,
      "name": "folio_wait_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
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
int folio_wait_bit_common(struct folio * folio, int bit_nr, int state, enum behavior behavior)
```

```json
{
  "name": "folio_wait_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582573360,
      "name": "folio_wait_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1227",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_read_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:folio_wait_private_2_killable",
        "mm/filemap.c:folio_wait_private_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582573360,
      "name": "folio_wait_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
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
int folio_wait_bit_common(struct folio * folio, int bit_nr, int state, enum behavior behavior)
```

```json
{
  "name": "folio_wait_bit_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582743024,
      "name": "folio_wait_bit_common",
      "external": false,
      "loc": "mm/filemap.c:1197",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_read_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:folio_wait_private_2_killable",
        "mm/filemap.c:folio_wait_private_2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582743024,
      "name": "folio_wait_bit_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
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
int folio_wait_bit_common(struct folio * folio, int bit_nr, int state, enum behavior behavior)
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
