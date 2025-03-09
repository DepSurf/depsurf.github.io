# Function: <code>ext4_mb_init_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581791280,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1045",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy",
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791280,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986240,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1045",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986240,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582076464,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1045",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582076464,
      "name": "ext4_mb_init_group",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582040832,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1043",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040832,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582191200,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1043",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191200,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582381056,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1032",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381056,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 714
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480544,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1032",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480544,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 714
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582649616,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1032",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582649616,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 721
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582751616,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1032",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582751616,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583061744,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1093",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583061744,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583140192,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1072",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583140192,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166864,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1406",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166864,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1410",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583508656,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
    },
    {
      "addr": 18446744071592262812,
      "name": "ext4_mb_init_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1407",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584036992,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
    },
    {
      "addr": 18446744071594044513,
      "name": "ext4_mb_init_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1364",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669296,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 982
    },
    {
      "addr": 18446744071596077323,
      "name": "ext4_mb_init_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584892992,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1487",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584892992,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 917
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585123024,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1503",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585123024,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 905
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494416904,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1032",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494416904,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227850080,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1032",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227850080,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288158416,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1032",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288158416,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273830958,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1032",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273830958,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582720352,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1032",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582720352,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582657520,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1032",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582657520,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582710208,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1032",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582710208,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
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
int ext4_mb_init_group(struct super_block * sb, ext4_group_t group, gfp_t gfp)
```

```json
{
  "name": "ext4_mb_init_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582794736,
      "name": "ext4_mb_init_group",
      "external": false,
      "loc": "fs/ext4/mballoc.c:1032",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_mb_good_group",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582794736,
      "name": "ext4_mb_init_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
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
