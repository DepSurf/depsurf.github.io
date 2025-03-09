# Function: <code>fuse_parse_cache</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582951237,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:363",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583132487,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:363",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583238776,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:377",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
enum fuse_parse_result fuse_parse_cache(struct fuse_file * ff, void * addr, unsigned int size, struct dir_context * ctx)
```

```json
{
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583562368,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:377",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583562368,
      "name": "fuse_parse_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
enum fuse_parse_result fuse_parse_cache(struct fuse_file * ff, void * addr, unsigned int size, struct dir_context * ctx)
```

```json
{
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583674720,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:377",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583674720,
      "name": "fuse_parse_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
enum fuse_parse_result fuse_parse_cache(struct fuse_file * ff, void * addr, unsigned int size, struct dir_context * ctx)
```

```json
{
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583695872,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:380",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583695872,
      "name": "fuse_parse_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584058617,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:380",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
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
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584650057,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:380",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
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
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585331669,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:382",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
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
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585561620,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:382",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
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
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585799999,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:390",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
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
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494962056,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:377",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
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
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228369688,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:377",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
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
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288839636,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:377",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
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
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274263772,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:377",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
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
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583207512,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:377",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
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
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583144664,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:377",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
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
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583191544,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:377",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
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
  "name": "fuse_parse_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583285448,
      "name": "fuse_parse_cache",
      "external": false,
      "loc": "fs/fuse/readdir.c:377",
      "file": "fs/fuse/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
enum fuse_parse_result fuse_parse_cache(struct fuse_file * ff, void * addr, unsigned int size, struct dir_context * ctx)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
enum fuse_parse_result fuse_parse_cache(struct fuse_file * ff, void * addr, unsigned int size, struct dir_context * ctx)
```
</details>
</li>
</ul>
