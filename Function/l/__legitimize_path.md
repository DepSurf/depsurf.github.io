# Function: <code>__legitimize_path</code>

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
bool __legitimize_path(struct path * path, unsigned int seq, unsigned int mseq)
```

```json
{
  "name": "__legitimize_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125728,
      "name": "__legitimize_path",
      "external": false,
      "loc": "fs/namei.c:608",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:pick_link",
        "fs/namei.c:choose_mountpoint",
        "fs/namei.c:unlazy_walk",
        "fs/namei.c:legitimize_root",
        "fs/namei.c:legitimize_links"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125728,
      "name": "__legitimize_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
bool __legitimize_path(struct path * path, unsigned int seq, unsigned int mseq)
```

```json
{
  "name": "__legitimize_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582172208,
      "name": "__legitimize_path",
      "external": false,
      "loc": "fs/namei.c:608",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:pick_link",
        "fs/namei.c:choose_mountpoint",
        "fs/namei.c:try_to_unlazy",
        "fs/namei.c:legitimize_root",
        "fs/namei.c:legitimize_links"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582172208,
      "name": "__legitimize_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool __legitimize_path(struct path * path, unsigned int seq, unsigned int mseq)
```

```json
{
  "name": "__legitimize_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196848,
      "name": "__legitimize_path",
      "external": false,
      "loc": "fs/namei.c:662",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:pick_link",
        "fs/namei.c:try_to_unlazy",
        "fs/namei.c:legitimize_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196848,
      "name": "__legitimize_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool __legitimize_path(struct path * path, unsigned int seq, unsigned int mseq)
```

```json
{
  "name": "__legitimize_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582514176,
      "name": "__legitimize_path",
      "external": false,
      "loc": "fs/namei.c:689",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:pick_link",
        "fs/namei.c:try_to_unlazy",
        "fs/namei.c:legitimize_root"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582514176,
      "name": "__legitimize_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
bool __legitimize_path(struct path * path, unsigned int seq, unsigned int mseq)
```

```json
{
  "name": "__legitimize_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583039056,
      "name": "__legitimize_path",
      "external": false,
      "loc": "fs/namei.c:690",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:handle_dots",
        "fs/namei.c:pick_link",
        "fs/namei.c:try_to_unlazy_next",
        "fs/namei.c:try_to_unlazy",
        "fs/namei.c:try_to_unlazy",
        "fs/namei.c:legitimize_links"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583039056,
      "name": "__legitimize_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
bool __legitimize_path(struct path * path, unsigned int seq, unsigned int mseq)
```

```json
{
  "name": "__legitimize_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583604336,
      "name": "__legitimize_path",
      "external": false,
      "loc": "fs/namei.c:696",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:handle_dots",
        "fs/namei.c:pick_link",
        "fs/namei.c:try_to_unlazy_next",
        "fs/namei.c:try_to_unlazy",
        "fs/namei.c:try_to_unlazy",
        "fs/namei.c:legitimize_links"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583604336,
      "name": "__legitimize_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
bool __legitimize_path(struct path * path, unsigned int seq, unsigned int mseq)
```

```json
{
  "name": "__legitimize_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583821408,
      "name": "__legitimize_path",
      "external": false,
      "loc": "fs/namei.c:699",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:handle_dots",
        "fs/namei.c:pick_link",
        "fs/namei.c:try_to_unlazy_next",
        "fs/namei.c:try_to_unlazy",
        "fs/namei.c:try_to_unlazy",
        "fs/namei.c:legitimize_links"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583821408,
      "name": "__legitimize_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
bool __legitimize_path(struct path * path, unsigned int seq, unsigned int mseq)
```

```json
{
  "name": "__legitimize_path",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584027360,
      "name": "__legitimize_path",
      "external": false,
      "loc": "fs/namei.c:702",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:handle_dots",
        "fs/namei.c:pick_link",
        "fs/namei.c:try_to_unlazy_next",
        "fs/namei.c:try_to_unlazy",
        "fs/namei.c:try_to_unlazy",
        "fs/namei.c:legitimize_links"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027360,
      "name": "__legitimize_path",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool __legitimize_path(struct path * path, unsigned int seq, unsigned int mseq)
```
</details>
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
