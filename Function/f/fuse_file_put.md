# Function: <code>fuse_file_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582078768,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:89",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_common",
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582078768,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void fuse_file_put(struct fuse_file * ff, bool sync)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582293888,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:89",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582293888,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void fuse_file_put(struct fuse_file * ff, bool sync)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582382272,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:89",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582382272,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void fuse_file_put(struct fuse_file * ff, bool sync)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582466976,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:89",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582466976,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void fuse_file_put(struct fuse_file * ff, bool sync)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582617888,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:89",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582617888,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void fuse_file_put(struct fuse_file * ff, bool sync)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582809712,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:89",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582809712,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582912704,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:92",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912704,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583091904,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:88",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091904,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583197136,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:111",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197136,
      "name": "fuse_file_put",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583524880,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:112",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583524880,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583634768,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:118",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583634768,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583655760,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:106",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_file_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583655760,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584014384,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:106",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_file_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014384,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584602048,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:106",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_file_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584602048,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585280816,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:106",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_file_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585280816,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585511184,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:107",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_file_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585511184,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585747952,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:108",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_file_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585747952,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494916568,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:111",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494916568,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228329012,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:111",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228329012,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288784368,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:111",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288784368,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274244988,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:111",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_common"
      ],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274225686,
      "name": "fuse_file_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583165872,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:111",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583165872,
      "name": "fuse_file_put",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583103024,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:111",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583103024,
      "name": "fuse_file_put",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583149904,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:111",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583149904,
      "name": "fuse_file_put",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
```

```json
{
  "name": "fuse_file_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583244608,
      "name": "fuse_file_put",
      "external": false,
      "loc": "fs/fuse/file.c:111",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages",
        "fs/fuse/file.c:fuse_write_inode",
        "fs/fuse/file.c:fuse_writepage_free",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_sync_release",
        "fs/fuse/file.c:fuse_release_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244608,
      "name": "fuse_file_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool isdir</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void fuse_file_put(struct fuse_file * ff, bool sync, bool isdir)
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
