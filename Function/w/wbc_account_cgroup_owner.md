# Function: <code>wbc_account_cgroup_owner</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581979216,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:718",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581979216,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582054208,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:723",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054208,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582289296,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:724",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582289296,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582342384,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:724",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342384,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582370000,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:730",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370000,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582690592,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:854",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582690592,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583243168,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:857",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243168,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583824944,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:859",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824944,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584042288,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:859",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/ext4/page-io.c:ext4_bio_write_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584042288,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584257088,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:876",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/iomap/buffered-io.c:iomap_add_to_ioend",
        "fs/ext4/page-io.c:ext4_bio_write_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584257088,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493577064,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:723",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493577064,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227128944,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:723",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227128944,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287164192,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:723",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287164192,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273235494,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:723",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273235494,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582022944,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:723",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582022944,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581960512,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:723",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960512,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582014224,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:723",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582014224,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_cgroup_owner",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582085200,
      "name": "wbc_account_cgroup_owner",
      "external": true,
      "loc": "fs/fs-writeback.c:723",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:submit_bh_wbc",
        "fs/mpage.c:__mpage_writepage",
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582085200,
      "name": "wbc_account_cgroup_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void wbc_account_cgroup_owner(struct writeback_control * wbc, struct page * page, size_t bytes)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
