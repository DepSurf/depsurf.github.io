# Function: <code>__es_scan_clu</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool __es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582359344,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:385",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_remove_blks",
        "fs/ext4/extents_status.c:ext4_es_remove_blks",
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359344,
      "name": "__es_scan_clu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool __es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582527360,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:385",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents_status.c:ext4_es_remove_blks",
        "fs/ext4/extents_status.c:ext4_es_remove_blks",
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582527360,
      "name": "__es_scan_clu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582631011,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:385",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582940168,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:385",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583014628,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:391",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583040164,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:391",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583377604,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:391",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583890550,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:391",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584515478,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:389",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584743686,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:389",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584976310,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:390",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494281272,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:385",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227715620,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:385",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287993892,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:385",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273727202,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:385",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582599747,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:385",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582536915,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:385",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582589859,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:385",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__es_scan_clu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582671543,
      "name": "__es_scan_clu",
      "external": false,
      "loc": "fs/ext4/extents_status.c:385",
      "file": "fs/ext4/extents_status.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_scan_clu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool __es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
bool __es_scan_clu(struct inode * inode, int (*)(struct extent_status *) matching_fn, ext4_lblk_t lblk)
```
</details>
</li>
</ul>
