# Function: <code>fuse_release_user_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582078928,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:519",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_aio_complete_req",
        "fs/fuse/file.c:fuse_direct_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582078928,
      "name": "fuse_release_user_pages.isra.19",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_req * req, bool should_dirty)
```

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582298800,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:533",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582298800,
      "name": "fuse_release_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void fuse_release_user_pages(struct fuse_req * req, bool should_dirty)
```

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582387136,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:534",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582387136,
      "name": "fuse_release_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_req * req, bool should_dirty)
```

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470352,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:529",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470352,
      "name": "fuse_release_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void fuse_release_user_pages(struct fuse_req * req, bool should_dirty)
```

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582622592,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:529",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582622592,
      "name": "fuse_release_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
void fuse_release_user_pages(struct fuse_req * req, bool should_dirty)
```

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812512,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:529",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812512,
      "name": "fuse_release_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void fuse_release_user_pages(struct fuse_req * req, bool should_dirty)
```

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582915344,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:534",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915344,
      "name": "fuse_release_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void fuse_release_user_pages(struct fuse_req * req, bool should_dirty)
```

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583094736,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:546",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583094736,
      "name": "fuse_release_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void fuse_release_user_pages(struct fuse_args_pages * ap, bool should_dirty)
```

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583197648,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:571",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197648,
      "name": "fuse_release_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583537114,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:587",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
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
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583646973,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:610",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
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
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583667174,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:614",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
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
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584026322,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:618",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
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
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584614275,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:627",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
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
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585293569,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:627",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
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
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585523931,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:628",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
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
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585760893,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:629",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
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
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494917192,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:571",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494917192,
      "name": "fuse_release_user_pages.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void fuse_release_user_pages(struct fuse_args_pages * ap, bool should_dirty)
```

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228330328,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:571",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228330328,
      "name": "fuse_release_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288787120,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:571",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288787120,
      "name": "fuse_release_user_pages.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274226106,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:571",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274226106,
      "name": "fuse_release_user_pages.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void fuse_release_user_pages(struct fuse_args_pages * ap, bool should_dirty)
```

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166384,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:571",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166384,
      "name": "fuse_release_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void fuse_release_user_pages(struct fuse_args_pages * ap, bool should_dirty)
```

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583103536,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:571",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583103536,
      "name": "fuse_release_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void fuse_release_user_pages(struct fuse_args_pages * ap, bool should_dirty)
```

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583150416,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:571",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583150416,
      "name": "fuse_release_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void fuse_release_user_pages(struct fuse_args_pages * ap, bool should_dirty)
```

```json
{
  "name": "fuse_release_user_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583245984,
      "name": "fuse_release_user_pages",
      "external": false,
      "loc": "fs/fuse/file.c:571",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_aio_complete_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583245984,
      "name": "fuse_release_user_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void fuse_release_user_pages(struct fuse_req * req, bool should_dirty)
```
</details>
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_args_pages * ap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_req * req</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void fuse_release_user_pages(struct fuse_args_pages * ap, bool should_dirty)
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
void fuse_release_user_pages(struct fuse_args_pages * ap, bool should_dirty)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void fuse_release_user_pages(struct fuse_args_pages * ap, bool should_dirty)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void fuse_release_user_pages(struct fuse_args_pages * ap, bool should_dirty)
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
