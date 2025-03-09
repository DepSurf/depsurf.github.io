# Function: <code>prepend_copy</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool prepend_copy(void * dst, const void * src, int len)
```

```json
{
  "name": "prepend_copy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582739848,
      "name": "prepend_copy",
      "external": false,
      "loc": "fs/d_path.c:47",
      "file": "fs/d_path.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/d_path.c:simple_dname"
      ],
      "caller_func": [
        "fs/d_path.c:__dentry_path",
        "fs/d_path.c:__dentry_path",
        "fs/d_path.c:simple_dname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582736784,
      "name": "prepend_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
bool prepend_copy(void * dst, const void * src, int len)
```

```json
{
  "name": "prepend_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583282992,
      "name": "prepend_copy",
      "external": false,
      "loc": "fs/d_path.c:47",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__dentry_path",
        "fs/d_path.c:__dentry_path",
        "fs/d_path.c:simple_dname",
        "fs/d_path.c:simple_dname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583282992,
      "name": "prepend_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
bool prepend_copy(void * dst, const void * src, int len)
```

```json
{
  "name": "prepend_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583866144,
      "name": "prepend_copy",
      "external": false,
      "loc": "fs/d_path.c:47",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__dentry_path",
        "fs/d_path.c:__dentry_path",
        "fs/d_path.c:simple_dname",
        "fs/d_path.c:simple_dname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866144,
      "name": "prepend_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
bool prepend_copy(void * dst, const void * src, int len)
```

```json
{
  "name": "prepend_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584087904,
      "name": "prepend_copy",
      "external": false,
      "loc": "fs/d_path.c:48",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__dentry_path",
        "fs/d_path.c:__dentry_path",
        "fs/d_path.c:simple_dname",
        "fs/d_path.c:simple_dname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584087904,
      "name": "prepend_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
bool prepend_copy(void * dst, const void * src, int len)
```

```json
{
  "name": "prepend_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584304000,
      "name": "prepend_copy",
      "external": false,
      "loc": "fs/d_path.c:48",
      "file": "fs/d_path.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/d_path.c:__dentry_path",
        "fs/d_path.c:__dentry_path",
        "fs/d_path.c:simple_dname",
        "fs/d_path.c:simple_dname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304000,
      "name": "prepend_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool prepend_copy(void * dst, const void * src, int len)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
