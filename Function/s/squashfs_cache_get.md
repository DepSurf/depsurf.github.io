# Function: <code>squashfs_cache_get</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126752,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:65",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126752,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582216528,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:65",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216528,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 846
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
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301968,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:65",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301968,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 835
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
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582451088,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:65",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582451088,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 835
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:65",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582643932,
      "name": "squashfs_cache_get.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071582641696,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:65",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745708,
      "name": "squashfs_cache_get.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071582743472,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
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
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582919756,
      "name": "squashfs_cache_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071582917504,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 806
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583026300,
      "name": "squashfs_cache_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583024048,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 806
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344108,
      "name": "squashfs_cache_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583341840,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591351253,
      "name": "squashfs_cache_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583458352,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591294137,
      "name": "squashfs_cache_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583480320,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 765
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592275718,
      "name": "squashfs_cache_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583834720,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 762
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594057561,
      "name": "squashfs_cache_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071584402624,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585057728,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585057728,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 927
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
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585286912,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585286912,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 927
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
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585520528,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585520528,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 927
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
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494719152,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494719152,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1052
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
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228153980,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228153980,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
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
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288539920,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288539920,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1424
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
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274067602,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274067602,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1032
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582995036,
      "name": "squashfs_cache_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071582992784,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 806
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582932188,
      "name": "squashfs_cache_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071582929936,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 806
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983644,
      "name": "squashfs_cache_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071582981392,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 806
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
```

```json
{
  "name": "squashfs_cache_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_get",
      "external": true,
      "loc": "fs/squashfs/cache.c:52",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_get_datablock",
        "fs/squashfs/cache.c:squashfs_get_fragment",
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583072716,
      "name": "squashfs_cache_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583070480,
      "name": "squashfs_cache_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 786
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
struct squashfs_cache_entry * squashfs_cache_get(struct super_block * sb, struct squashfs_cache * cache, u64 block, int length)
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
