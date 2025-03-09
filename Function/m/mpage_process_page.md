# Function: <code>mpage_process_page</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int mpage_process_page(struct mpage_da_data * mpd, struct page * page, ext4_lblk_t * m_lblk, ext4_fsblk_t * m_pblk, bool * map_bh)
```

```json
{
  "name": "mpage_process_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582998272,
      "name": "mpage_process_page",
      "external": false,
      "loc": "fs/ext4/inode.c:2221",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:mpage_map_and_submit_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998272,
      "name": "mpage_process_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int mpage_process_page(struct mpage_da_data * mpd, struct page * page, ext4_lblk_t * m_lblk, ext4_fsblk_t * m_pblk, bool * map_bh)
```

```json
{
  "name": "mpage_process_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583074400,
      "name": "mpage_process_page",
      "external": false,
      "loc": "fs/ext4/inode.c:2241",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:mpage_map_and_submit_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074400,
      "name": "mpage_process_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpage_process_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583099069,
      "name": "mpage_process_page",
      "external": false,
      "loc": "fs/ext4/inode.c:2240",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:mpage_map_and_submit_buffers"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int mpage_process_page(struct mpage_da_data * mpd, struct page * page, ext4_lblk_t * m_lblk, ext4_fsblk_t * m_pblk, bool * map_bh)
```

```json
{
  "name": "mpage_process_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpage_process_page",
      "external": false,
      "loc": "fs/ext4/inode.c:2219",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:mpage_map_and_submit_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583438592,
      "name": "mpage_process_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    },
    {
      "addr": 18446744071592257586,
      "name": "mpage_process_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int mpage_process_page(struct mpage_da_data * mpd, struct page * page, ext4_lblk_t * m_lblk, ext4_fsblk_t * m_pblk, bool * map_bh)
```

```json
{
  "name": "mpage_process_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpage_process_page",
      "external": false,
      "loc": "fs/ext4/inode.c:2251",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:mpage_map_and_submit_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583957808,
      "name": "mpage_process_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    },
    {
      "addr": 18446744071594038553,
      "name": "mpage_process_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int mpage_process_page(struct mpage_da_data * mpd, struct page * page, ext4_lblk_t * m_lblk, ext4_fsblk_t * m_pblk, bool * map_bh)
```

```json
{
  "name": "mpage_process_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpage_process_page",
      "external": false,
      "loc": "fs/ext4/inode.c:2269",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:mpage_map_and_submit_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584585232,
      "name": "mpage_process_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    },
    {
      "addr": 18446744071596071558,
      "name": "mpage_process_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int mpage_process_page(struct mpage_da_data * mpd, struct page * page, ext4_lblk_t * m_lblk, ext4_fsblk_t * m_pblk, bool * map_bh)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int mpage_process_page(struct mpage_da_data * mpd, struct page * page, ext4_lblk_t * m_lblk, ext4_fsblk_t * m_pblk, bool * map_bh)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int mpage_process_page(struct mpage_da_data * mpd, struct page * page, ext4_lblk_t * m_lblk, ext4_fsblk_t * m_pblk, bool * map_bh)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int mpage_process_page(struct mpage_da_data * mpd, struct page * page, ext4_lblk_t * m_lblk, ext4_fsblk_t * m_pblk, bool * map_bh)
```
</details>
</li>
</ul>
