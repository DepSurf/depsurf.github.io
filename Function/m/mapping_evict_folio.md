# Function: <code>mapping_evict_folio</code>

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
long int mapping_evict_folio(struct address_space * mapping, struct folio * folio)
```

```json
{
  "name": "mapping_evict_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582023360,
      "name": "mapping_evict_folio",
      "external": false,
      "loc": "mm/truncate.c:270",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_mapping_pagevec",
        "mm/truncate.c:invalidate_inode_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023360,
      "name": "mapping_evict_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
long int mapping_evict_folio(struct address_space * mapping, struct folio * folio)
```

```json
{
  "name": "mapping_evict_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582454464,
      "name": "mapping_evict_folio",
      "external": false,
      "loc": "mm/truncate.c:270",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_mapping_pagevec",
        "mm/truncate.c:invalidate_inode_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454464,
      "name": "mapping_evict_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
long int mapping_evict_folio(struct address_space * mapping, struct folio * folio)
```

```json
{
  "name": "mapping_evict_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582659728,
      "name": "mapping_evict_folio",
      "external": false,
      "loc": "mm/truncate.c:270",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:mapping_try_invalidate",
        "mm/truncate.c:invalidate_inode_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659728,
      "name": "mapping_evict_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
long int mapping_evict_folio(struct address_space * mapping, struct folio * folio)
```

```json
{
  "name": "mapping_evict_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582836480,
      "name": "mapping_evict_folio",
      "external": true,
      "loc": "mm/truncate.c:279",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:mapping_try_invalidate",
        "mm/memory.c:__do_fault",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:truncate_error_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836480,
      "name": "mapping_evict_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
long int mapping_evict_folio(struct address_space * mapping, struct folio * folio)
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
