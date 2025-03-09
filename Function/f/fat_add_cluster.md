# Function: <code>fat_add_cluster</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581972219,
      "name": "fat_add_cluster",
      "external": false,
      "loc": "fs/fat/inode.c:96",
      "file": "fs/fat/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_get_block"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582193648,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:96",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582193648,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582283152,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:96",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582283152,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582367680,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:96",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582367680,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582518464,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:96",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582518464,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582708816,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:97",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582708816,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582812400,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:97",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812400,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582987408,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:98",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582987408,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583093616,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:103",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583093616,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583412384,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:104",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412384,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583527920,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:104",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583527920,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583551072,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:104",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583551072,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583909248,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:104",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583909248,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584486592,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:104",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486592,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585151840,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:104",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151840,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585380992,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:104",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585380992,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585615840,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:104",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585615840,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494800976,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:103",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494800976,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228220356,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:103",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228220356,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288639152,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:103",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288639152,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274130118,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:103",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274130118,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583062352,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:103",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583062352,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582999504,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:103",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582999504,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583050960,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:103",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583050960,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int fat_add_cluster(struct inode * inode)
```

```json
{
  "name": "fat_add_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583140144,
      "name": "fat_add_cluster",
      "external": true,
      "loc": "fs/fat/inode.c:103",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/file.c:fat_fallocate",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583140144,
      "name": "fat_add_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int fat_add_cluster(struct inode * inode)
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
