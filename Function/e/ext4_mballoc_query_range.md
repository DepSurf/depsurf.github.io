# Function: <code>ext4_mballoc_query_range</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582068784,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5337",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582068784,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218224,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5341",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218224,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 805
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582408016,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5311",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582408016,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582507440,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5318",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582507440,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 793
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582676544,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5320",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582676544,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 655
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582778592,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5341",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582778592,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 655
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583090192,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5586",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583090192,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583169152,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5873",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169152,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583195984,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:6406",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195984,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 678
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583539200,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:6499",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583539200,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584072320,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:6591",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072320,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 713
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584705040,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:6560",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584705040,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584928768,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:7138",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584928768,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585160320,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:6978",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585160320,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494444784,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5341",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494444784,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227882428,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5341",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227882428,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288198624,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5341",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288198624,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1116
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273857292,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5341",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273857292,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582747328,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5341",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582747328,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 655
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582684496,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5341",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582684496,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 655
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582737184,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5341",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582737184,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 655
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
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```

```json
{
  "name": "ext4_mballoc_query_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582822464,
      "name": "ext4_mballoc_query_range",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5341",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582822464,
      "name": "ext4_mballoc_query_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 650
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int ext4_mballoc_query_range(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t end, ext4_mballoc_query_range_fn formatter, void * priv)
```
</details>
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
