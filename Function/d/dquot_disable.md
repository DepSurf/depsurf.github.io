# Function: <code>dquot_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413648,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2071",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/quota/dquot.c:dquot_quota_disable",
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413648,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1929
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581596096,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2104",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_disable",
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581596096,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1950
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581683488,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2093",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_disable",
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581683488,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1969
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581734976,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2127",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581734976,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1753
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581881936,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2163",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881936,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1790
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582067344,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2160",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582067344,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1797
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582161440,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2160",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582161440,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1797
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582324224,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2168",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582324224,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1783
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582423424,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2170",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582423424,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1783
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582717584,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2184",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582717584,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 888
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582788752,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2185",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582788752,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 888
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817840,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2183",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817840,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1149
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583147984,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2188",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583147984,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1448
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583631792,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2198",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:__ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583631792,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1445
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584236896,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2205",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:__ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584236896,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1445
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584467328,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2263",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:__ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584467328,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1545
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584690512,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2217",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:dquot_load_quota_sb",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:__ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690512,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1304
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494029904,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2170",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494029904,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2176
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227491436,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2170",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227491436,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2040
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287680512,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2170",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287680512,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2620
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273538970,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2170",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273538970,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1916
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582392160,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2170",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582392160,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1783
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582329856,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2170",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329856,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1783
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582382640,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2170",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582382640,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1783
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
int dquot_disable(struct super_block * sb, int type, unsigned int flags)
```

```json
{
  "name": "dquot_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582459136,
      "name": "dquot_disable",
      "external": true,
      "loc": "fs/quota/dquot.c:2170",
      "file": "fs/quota/dquot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:dquot_quota_enable",
        "fs/quota/dquot.c:vfs_load_quota_inode",
        "fs/quota/dquot.c:dquot_quota_off",
        "fs/ext4/super.c:ext4_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582459136,
      "name": "dquot_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1756
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
