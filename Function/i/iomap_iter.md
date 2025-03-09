# Function: <code>iomap_iter</code>

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
int iomap_iter(struct iomap_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583131200,
      "name": "iomap_iter",
      "external": true,
      "loc": "fs/iomap/iter.c:57",
      "file": "fs/iomap/iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_rw",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readpage",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583131200,
      "name": "iomap_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
int iomap_iter(struct iomap_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583595472,
      "name": "iomap_iter",
      "external": true,
      "loc": "fs/iomap/iter.c:57",
      "file": "fs/iomap/iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_rw",
        "fs/dax.c:dax_zero_range",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583595472,
      "name": "iomap_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int iomap_iter(struct iomap_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584200912,
      "name": "iomap_iter",
      "external": true,
      "loc": "fs/iomap/iter.c:74",
      "file": "fs/iomap/iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_dedupe_file_range_compare",
        "fs/dax.c:dax_dedupe_file_range_compare",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_rw",
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_file_unshare",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584200912,
      "name": "iomap_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int iomap_iter(struct iomap_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584430992,
      "name": "iomap_iter",
      "external": true,
      "loc": "fs/iomap/iter.c:74",
      "file": "fs/iomap/iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_dedupe_file_range_compare",
        "fs/dax.c:dax_dedupe_file_range_compare",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_rw",
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_file_unshare",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584430992,
      "name": "iomap_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int iomap_iter(struct iomap_iter * iter, const struct iomap_ops * ops)
```

```json
{
  "name": "iomap_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584652112,
      "name": "iomap_iter",
      "external": true,
      "loc": "fs/iomap/iter.c:74",
      "file": "fs/iomap/iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_dedupe_file_range_compare",
        "fs/dax.c:dax_dedupe_file_range_compare",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_rw",
        "fs/dax.c:dax_zero_range",
        "fs/dax.c:dax_file_unshare",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_zero_range",
        "fs/iomap/buffered-io.c:iomap_file_unshare",
        "fs/iomap/buffered-io.c:iomap_file_buffered_write",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/iomap/seek.c:iomap_seek_data",
        "fs/iomap/seek.c:iomap_seek_hole",
        "fs/iomap/swapfile.c:iomap_swapfile_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584652112,
      "name": "iomap_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int iomap_iter(struct iomap_iter * iter, const struct iomap_ops * ops)
```
</details>
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
