# Function: <code>ext4_es_delayed_clu</code>

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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582365072,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1683",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582365072,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:1682",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582533863,
      "name": "ext4_es_delayed_clu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071582533072,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582634576,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2073",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582634576,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943632,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2073",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943632,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583018048,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2097",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583018048,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583043584,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2095",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583043584,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583381024,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2095",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583381024,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583894608,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2095",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894608,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584519776,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2092",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584519776,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584748496,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2139",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584748496,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584981392,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2200",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584981392,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494285904,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2073",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494285904,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227719832,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2073",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227719832,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287999136,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2073",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287999136,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273730406,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2073",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273730406,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582603312,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2073",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603312,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582540480,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2073",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540480,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582593424,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2073",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582593424,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
```

```json
{
  "name": "ext4_es_delayed_clu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582675488,
      "name": "ext4_es_delayed_clu",
      "external": true,
      "loc": "fs/ext4/extents_status.c:2073",
      "file": "fs/ext4/extents_status.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582675488,
      "name": "ext4_es_delayed_clu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
unsigned int ext4_es_delayed_clu(struct inode * inode, ext4_lblk_t lblk, ext4_lblk_t len)
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
