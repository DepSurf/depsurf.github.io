# Function: <code>__ext4_journalled_invalidate_folio</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __ext4_journalled_invalidate_folio(struct folio * folio, size_t offset, size_t length)
```

```json
{
  "name": "__ext4_journalled_invalidate_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_journalled_invalidate_folio",
      "external": false,
      "loc": "fs/ext4/inode.c:3248",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:ext4_journalled_invalidate_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583959776,
      "name": "__ext4_journalled_invalidate_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071594038935,
      "name": "__ext4_journalled_invalidate_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int __ext4_journalled_invalidate_folio(struct folio * folio, size_t offset, size_t length)
```

```json
{
  "name": "__ext4_journalled_invalidate_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_journalled_invalidate_folio",
      "external": false,
      "loc": "fs/ext4/inode.c:3336",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:ext4_journalled_invalidate_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584588000,
      "name": "__ext4_journalled_invalidate_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 18446744071596072118,
      "name": "__ext4_journalled_invalidate_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __ext4_journalled_invalidate_folio(struct folio * folio, size_t offset, size_t length)
```

```json
{
  "name": "__ext4_journalled_invalidate_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_journalled_invalidate_folio",
      "external": false,
      "loc": "fs/ext4/inode.c:3118",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:ext4_journalled_invalidate_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584816256,
      "name": "__ext4_journalled_invalidate_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071596595677,
      "name": "__ext4_journalled_invalidate_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __ext4_journalled_invalidate_folio(struct folio * folio, size_t offset, size_t length)
```

```json
{
  "name": "__ext4_journalled_invalidate_folio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_journalled_invalidate_folio",
      "external": false,
      "loc": "fs/ext4/inode.c:3157",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:ext4_journalled_invalidate_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585049248,
      "name": "__ext4_journalled_invalidate_folio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071597501200,
      "name": "__ext4_journalled_invalidate_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int __ext4_journalled_invalidate_folio(struct folio * folio, size_t offset, size_t length)
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
