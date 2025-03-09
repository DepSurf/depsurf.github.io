# Function: <code>folio_redirty_for_writepage</code>

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
bool folio_redirty_for_writepage(struct writeback_control * wbc, struct folio * folio)
```

```json
{
  "name": "folio_redirty_for_writepage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581992288,
      "name": "folio_redirty_for_writepage",
      "external": true,
      "loc": "mm/page-writeback.c:2678",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/folio-compat.c:redirty_page_for_writepage",
        "mm/folio-compat.c:redirty_page_for_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581992288,
      "name": "folio_redirty_for_writepage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool folio_redirty_for_writepage(struct writeback_control * wbc, struct folio * folio)
```

```json
{
  "name": "folio_redirty_for_writepage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428848,
      "name": "folio_redirty_for_writepage",
      "external": true,
      "loc": "mm/page-writeback.c:2816",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/folio-compat.c:redirty_page_for_writepage",
        "mm/folio-compat.c:redirty_page_for_writepage",
        "fs/iomap/buffered-io.c:iomap_do_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428848,
      "name": "folio_redirty_for_writepage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool folio_redirty_for_writepage(struct writeback_control * wbc, struct folio * folio)
```

```json
{
  "name": "folio_redirty_for_writepage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582634048,
      "name": "folio_redirty_for_writepage",
      "external": true,
      "loc": "mm/page-writeback.c:2757",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/folio-compat.c:redirty_page_for_writepage",
        "mm/folio-compat.c:redirty_page_for_writepage",
        "mm/folio-compat.c:redirty_page_for_writepage",
        "fs/buffer.c:__block_write_full_folio",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/super.c:ext4_journalled_writepage_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582634048,
      "name": "folio_redirty_for_writepage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
bool folio_redirty_for_writepage(struct writeback_control * wbc, struct folio * folio)
```

```json
{
  "name": "folio_redirty_for_writepage",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582805296,
      "name": "folio_redirty_for_writepage",
      "external": true,
      "loc": "mm/page-writeback.c:2726",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/folio-compat.c:redirty_page_for_writepage",
        "mm/folio-compat.c:redirty_page_for_writepage",
        "mm/folio-compat.c:redirty_page_for_writepage",
        "fs/buffer.c:__block_write_full_folio",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/page-io.c:ext4_bio_write_folio",
        "fs/ext4/super.c:ext4_journalled_writepage_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582805296,
      "name": "folio_redirty_for_writepage",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
bool folio_redirty_for_writepage(struct writeback_control * wbc, struct folio * folio)
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
