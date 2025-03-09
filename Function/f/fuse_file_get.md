# Function: <code>fuse_file_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582076670,
      "name": "fuse_file_get",
      "external": true,
      "loc": "fs/fuse/file.c:78",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:__fuse_write_file_get",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_do_open",
        "fs/fuse/file.c:fuse_writepages_send"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086368,
      "name": "fuse_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582312882,
      "name": "fuse_file_get",
      "external": true,
      "loc": "fs/fuse/file.c:78",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:__fuse_write_file_get",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_do_open"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301696,
      "name": "fuse_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582401218,
      "name": "fuse_file_get",
      "external": true,
      "loc": "fs/fuse/file.c:78",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:__fuse_write_file_get",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_do_open"
      ],
      "caller_func": [
        "fs/fuse/dir.c:fuse_create_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582390032,
      "name": "fuse_file_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582485202,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:78",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:__fuse_write_file_get",
        "fs/fuse/file.c:fuse_writepage_end"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582615232,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:78",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:__fuse_write_file_get",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615232,
      "name": "fuse_file_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582808256,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:78",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:__fuse_write_file_get",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808256,
      "name": "fuse_file_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582911248,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:81",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:__fuse_write_file_get",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582911248,
      "name": "fuse_file_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583090496,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:77",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583090496,
      "name": "fuse_file_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583195760,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:96",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195760,
      "name": "fuse_file_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583545980,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:97",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_readpages"
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
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583657431,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:103",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_readpages"
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
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583678166,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:91",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_readahead"
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
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584035692,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:91",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_readahead"
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
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584624044,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:91",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_readahead"
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
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585303836,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:91",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_readahead"
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
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585533756,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:92",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_readahead"
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
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585771004,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:93",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_readahead"
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
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494939036,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:96",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_end"
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
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228349404,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:96",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_readpages"
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
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288812300,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:96",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_readpages"
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
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274244648,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:96",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_end",
        "fs/fuse/file.c:fuse_send_readpages"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583164496,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:96",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164496,
      "name": "fuse_file_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583101648,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:96",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583101648,
      "name": "fuse_file_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583148528,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:96",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583148528,
      "name": "fuse_file_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```

```json
{
  "name": "fuse_file_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583242128,
      "name": "fuse_file_get",
      "external": false,
      "loc": "fs/fuse/file.c:96",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_send",
        "fs/fuse/file.c:fuse_writepage_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583242128,
      "name": "fuse_file_get",
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct fuse_file * fuse_file_get(struct fuse_file * ff)
```
</details>
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
