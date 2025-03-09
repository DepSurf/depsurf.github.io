# Function: <code>wbc_account_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void wbc_account_io(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581162528,
      "name": "wbc_account_io",
      "external": true,
      "loc": "fs/fs-writeback.c:674",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071581162528,
      "name": "wbc_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void wbc_account_io(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581332864,
      "name": "wbc_account_io",
      "external": true,
      "loc": "fs/fs-writeback.c:676",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071581332864,
      "name": "wbc_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void wbc_account_io(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_io",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412000,
      "name": "wbc_account_io",
      "external": true,
      "loc": "fs/fs-writeback.c:676",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
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
      "addr": 18446744071581412000,
      "name": "wbc_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_io(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_io",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581467632,
      "name": "wbc_account_io",
      "external": true,
      "loc": "fs/fs-writeback.c:690",
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
      "addr": 18446744071581467632,
      "name": "wbc_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_io(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_io",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581609760,
      "name": "wbc_account_io",
      "external": true,
      "loc": "fs/fs-writeback.c:690",
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
      "addr": 18446744071581609760,
      "name": "wbc_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_io(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_io",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581768048,
      "name": "wbc_account_io",
      "external": true,
      "loc": "fs/fs-writeback.c:690",
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
      "addr": 18446744071581768048,
      "name": "wbc_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wbc_account_io(struct writeback_control * wbc, struct page * page, size_t bytes)
```

```json
{
  "name": "wbc_account_io",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581854624,
      "name": "wbc_account_io",
      "external": true,
      "loc": "fs/fs-writeback.c:713",
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
      "addr": 18446744071581854624,
      "name": "wbc_account_io",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void wbc_account_io(struct writeback_control * wbc, struct page * page, size_t bytes)
```
</details>
</li>
</ul>
