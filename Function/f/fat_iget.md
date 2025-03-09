# Function: <code>fat_iget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581981456,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:405",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981456,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582194336,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:436",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582194336,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582283840,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:436",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283840,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582368368,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:436",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582368368,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582519152,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:436",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582519152,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582709520,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:443",
      "file": "fs/fat/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582709520,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582813120,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:443",
      "file": "fs/fat/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582813120,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582988096,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:444",
      "file": "fs/fat/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582988096,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583094304,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:449",
      "file": "fs/fat/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583094304,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583413136,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:449",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583413136,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583528672,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:449",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528672,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583551840,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:449",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583551840,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583910112,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:450",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583910112,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584487536,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:451",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584487536,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585152912,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:446",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585152912,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585382064,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:446",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585382064,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585616912,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:446",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585616912,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494801832,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:449",
      "file": "fs/fat/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494801832,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228221376,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:449",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228221376,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288640288,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:449",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288640288,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274130750,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:449",
      "file": "fs/fat/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274130750,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583063040,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:449",
      "file": "fs/fat/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583063040,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583000192,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:449",
      "file": "fs/fat/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583000192,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583051648,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:449",
      "file": "fs/fat/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583051648,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct inode * fat_iget(struct super_block * sb, loff_t i_pos)
```

```json
{
  "name": "fat_iget",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583140832,
      "name": "fat_iget",
      "external": true,
      "loc": "fs/fat/inode.c:449",
      "file": "fs/fat/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:__fat_readdir",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583140832,
      "name": "fat_iget",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
