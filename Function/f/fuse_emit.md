# Function: <code>fuse_emit</code>

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
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582948464,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582948464,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583129040,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
    },
    {
      "addr": 18446744071583133146,
      "name": "fuse_emit.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583235248,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583235248,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583563456,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583563456,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583675808,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583675808,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583696816,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583696816,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584056960,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056960,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584647744,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584647744,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585328928,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:114",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585328928,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585558912,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:114",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585558912,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585797328,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:114",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585797328,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494958296,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494958296,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228365900,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228365900,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288834832,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:parse_dirplusfile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288834832,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1068
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274260522,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274260522,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583203984,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203984,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583141136,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583141136,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583188016,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583188016,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```

```json
{
  "name": "fuse_emit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583282512,
      "name": "fuse_emit",
      "external": false,
      "loc": "fs/fuse/readdir.c:112",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583282512,
      "name": "fuse_emit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool fuse_emit(struct file * file, struct dir_context * ctx, struct fuse_dirent * dirent)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
