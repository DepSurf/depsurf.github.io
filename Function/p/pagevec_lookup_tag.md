# Function: <code>pagevec_lookup_tag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, int tag, unsigned int nr_pages)
```

```json
{
  "name": "pagevec_lookup_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580535504,
      "name": "pagevec_lookup_tag",
      "external": true,
      "loc": "mm/swap.c:1133",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580535504,
      "name": "pagevec_lookup_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, int tag, unsigned int nr_pages)
```

```json
{
  "name": "pagevec_lookup_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580621536,
      "name": "pagevec_lookup_tag",
      "external": true,
      "loc": "mm/swap.c:959",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621536,
      "name": "pagevec_lookup_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, int tag, unsigned int nr_pages)
```

```json
{
  "name": "pagevec_lookup_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580688704,
      "name": "pagevec_lookup_tag",
      "external": true,
      "loc": "mm/swap.c:959",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580688704,
      "name": "pagevec_lookup_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, int tag, unsigned int nr_pages)
```

```json
{
  "name": "pagevec_lookup_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580722352,
      "name": "pagevec_lookup_tag",
      "external": true,
      "loc": "mm/swap.c:972",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_cache_pages",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580722352,
      "name": "pagevec_lookup_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
unsigned int pagevec_lookup_tag(struct pagevec * pvec, struct address_space * mapping, long unsigned int * index, int tag, unsigned int nr_pages)
```
</details>
</li>
</ul>
